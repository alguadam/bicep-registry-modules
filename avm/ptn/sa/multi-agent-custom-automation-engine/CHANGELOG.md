# Changelog

The latest version of the changelog can be found [here](https://github.com/Azure/bicep-registry-modules/blob/main/avm/ptn/sa/multi-agent-custom-automation-engine/CHANGELOG.md).

## 0.2.0

### Changes

- Updated log analytics workspace configuration to become WAF compliant with replica configuration.
- Removed module to deploy container app environment as log analytics workspace allows to use secure outputs.
- Added private networking and private endpoints for web app and containers app.
- Failover location in CosmosDB and replica location in log analytics workspace calculated based on `location` parameter.

### Breaking Changes

- Removed parameter `failoverLocation`.
- Renamed parameter `solutionPrefix` to `solutionName`.
- Renamed parameter `solutionLocation` to `location`, and limited to supported regions.
- Renamed parameter `azureOpenAILocation` to `azureAiServiceLocation`.

## 0.1.0

### Changes

- Initial version

### Breaking Changes

- None
