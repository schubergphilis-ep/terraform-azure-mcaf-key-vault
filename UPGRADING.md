# Upgrading

## 1.x to 2.0

### azurerm 5 is required

azurerm v5 renamed `azurerm_key_vault.enable_rbac_authorization` to `rbac_authorization_enabled`.
A module can only spell the argument one way, so v2 requires `azurerm >= 5`. v1.x declared
`>= 4`, which let a fresh `terraform init` resolve v5 and fail `terraform validate`; the rename
landed on `main` as a fix and this release gives it the major version it needs. The module input
keeps its name, `enable_rbac_authorization`.

1. Move the root to `azurerm ~> 5.0` and read the
   [azurerm 5.0 upgrade guide](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/5.0-upgrade-guide)
   for the renames it applies outside this module.
2. Pin this module to `~> 2.0` and run `terraform init -upgrade`.
3. `terraform plan`: the rename is in place and replaces no vault or key.

Consumers who cannot move to azurerm 5 stay on `~> 1.0`, which keeps working on 4.x.

### Also in 2.0

Both additions are backwards compatible; `terraform init -upgrade` is the only step.

- The module waits for the deploying identity's Key Vault Administrator grant to propagate
  before creating keys. `hashicorp/time` becomes a required provider. The new input `role_assignment_propagation_delay` defaults to
  `"30s"`; set it to `"0s"` to skip the wait.
- Two new role inputs, `key_vault_crypto_officers` and `key_vault_readers`, follow the shape of
  the existing role variables.
