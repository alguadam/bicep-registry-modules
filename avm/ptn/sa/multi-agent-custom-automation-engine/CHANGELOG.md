# Changelog

The latest version of the changelog can be found [here](https://github.com/Azure/bicep-registry-modules/blob/main/avm/ptn/sa/multi-agent-custom-automation-engine/CHANGELOG.md).

## 0.2.0

### Changes

- Updated log analytics workspace configuration to become WAF compliant.
- Removed module to deploy container app environment as log analytics workspace allows to use secure outputs..
- Added private networking and private endpoints for web app and containers app.

### Breaking Changes

- Change parameter `failoverLocation` to `secondaryLocation`.

## 0.1.0

### Changes

- Initial version

### Breaking Changes

- None
