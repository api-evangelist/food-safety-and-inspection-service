# Food Safety and Inspection Service (food-safety-and-inspection-service)

The Food Safety and Inspection Service (FSIS) is a branch of the United States
Department of Agriculture (USDA) responsible for ensuring the safety of the
nation's commercial supply of meat, poultry, and egg products. FSIS publishes a
Recall API that provides machine-readable access to recall and public health
alert records.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/food-safety-and-inspection-service/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Federal Government, Food, Food Safety, Inspections, Recalls, Meat, Poultry, Eggs

## APIs

### FSIS Recall API

- **Human URL:** https://www.fsis.usda.gov/science-data/developer-resources/recall-api
- **Base URL:** https://www.fsis.usda.gov/fsis/api
- **Authentication:** None (open data)
- **Endpoint:** `GET /recall/v/1` returns the full corpus of FSIS recall and public health alert records as JSON.

## Machine-readable artifacts

- [OpenAPI 3.0](./openapi/fsis-recall-openapi.yml)
- [Capabilities](./capabilities/fsis-recall-capabilities.yml)
- [Rules](./rules/fsis-recall-rules.yml)

## Common Properties

- [Website](https://www.fsis.usda.gov/)
- [Documentation](https://www.fsis.usda.gov/science-data/developer-resources/recall-api)
- [Recalls](https://www.fsis.usda.gov/recalls)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
