# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.1.0](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v1.1.1...v1.1.0) (2025-07-28)

## [1.1.1](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v1.0.2...v1.1.1) (2025-07-28)


### 🐛 Fixes

* Revert "Merge pull request #22 from schubergphilis/add_keyvault_secre… ([#23](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/23)) ([782c59e](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/782c59ef3e88abab15c74f11ae1c6905115dc64f))

## [1.0.2](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v1.0.1...v1.0.2) (2025-04-22)


### 🐛 Fixes

* Correct the role name ([#18](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/18)) ([2ccdc91](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/2ccdc91ed3541482e73359a48de82bf238757735))

## [1.0.1](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v1.0.0...v1.0.1) (2025-04-02)


### 🐛 Fixes

* shift key rotation policy ([#16](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/16)) ([dd59182](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/dd59182b07fa1efaf93c93fbf92ead7f7a6f66e4))

## [1.0.0](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.3.2...v1.0.0) (2025-04-02)


### 🚀 Features

* add cmk_time_before_expiry variable ([#15](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/15)) ([3ddd8fe](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/3ddd8fe1b2a4cf7e896368b63a736d703898db06))
* make var for cmk key size ([#13](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/13)) ([2154916](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/2154916292ffef31f8d877ad7fcecb8b753af3ed))
* breaking: add private endpoints, role assignments, move vars to top level ([#11](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/11)) ([43167ee](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/43167ee8e8539624c1ef5f56c9b11b67b2c0b337))

### 🐛 Fixes

* switch to maps ([#14](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/14)) ([28bd783](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/28bd7835f3ba07f88027d8edbc6e406e591921ba))
* better check for private endpoints ([#12](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/12)) ([83d3d88](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/83d3d88f5b1e58408ee9e1577928fa6bd9074a0f))

## [0.3.2](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.3.1...v0.3.2) (2025-01-20)


### 🚀 Features

* add expiration date option for CMKs ([#8](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/8)) ([6428101](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/64281010ed3b5432092e18f9328ad5073864f7bb))

## [0.3.1](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.3.0...v0.3.1) (2024-12-03)


### 🐛 Fixes

* bug: adding missing optional param in the resources for keys ([#7](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/7)) ([9494f45](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/9494f45a695a9a4bf22881c0b7716c5ed10769ad))

## [0.3.0](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.2.2...v0.3.0) (2024-12-03)


### 🚀 Features

* Add expiry ([#6](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/6)) ([d3ea7ae](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/d3ea7aed8c529d54c5e687d002ebadb50ef6778e))

## [0.2.2](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.2.1...v0.2.2) (2024-11-28)


### 🚀 Features

* enhancement: Update outputs.tf ([#5](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/5)) ([fd8d4a0](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/fd8d4a0bd20dbbf9a77ababa3a0d347791ab03d6))

## [0.2.1](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.2.0...v0.2.1) (2024-11-25)


### 🚀 Features

* adding public_network_access_enabled as well ([#4](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/4)) ([3148282](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/314828218942af6eeff5d06302d5af293a6efabb))

## [0.2.0](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.1.1...v0.2.0) (2024-11-25)


### 🚀 Features

* adding the option to set default action via parameter ([#3](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/3)) ([b4ba265](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/b4ba265b92384e4a02354598832efbad9535adc2))

## [0.1.1](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/compare/v0.1.0...v0.1.1) (2024-11-07)


### 🐛 Fixes

* misc: fix some naming inconsistencies ([#2](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/2)) ([5efba0a](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/5efba0afbaca83339397c43317a2ab5deb16b65f))

## 0.1.0 (2024-10-07)


### 🚀 Features

* first release ([#1](https://github.com/schubergphilis/terraform-azure-mcaf-key-vault/pull/1)) ([fb49df9](https://github.com/schubergphilis-ep/terraform-azure-mcaf-key-vault/commit/fb49df90be075e1192eed3422cd02624ebfe9ce8))

