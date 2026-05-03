# UpKeep

UpKeep is an asset operations management and CMMS (Computerized Maintenance Management System) platform for maintenance teams and facility managers. The UpKeep API provides programmatic access to work orders, assets, locations, preventive maintenance schedules, parts inventory, purchase orders, meters, and maintenance requests.

**Developer Documentation:** https://developers.onupkeep.com/
**Website:** https://upkeep.com

## APIs

| API | Description |
|---|---|
| [UpKeep API](openapi/upkeep-openapi.yml) | CMMS REST API v2022-09-14 — work orders, assets, PM schedules, parts, purchase orders, meters, requests, webhooks |

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [upkeep-openapi.yml](openapi/upkeep-openapi.yml) | UpKeep CMMS API covering work orders, assets, locations, PM schedules, parts, purchase orders, meters, requests, and webhooks |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [upkeep-rules.yml](rules/upkeep-rules.yml) | Spectral ruleset enforcing UpKeep API conventions including session token auth, response envelopes, and path naming |

## Naftiko Capabilities

### Shared Definitions

| File | APIs Covered |
|---|---|
| [shared/upkeep.yaml](capabilities/shared/upkeep.yaml) | UpKeep CMMS API (work orders, assets, PM, parts, meters, requests) |

### Workflow Capabilities

| Workflow | Description | Tools |
|---|---|---|
| [maintenance-operations.yaml](capabilities/maintenance-operations.yaml) | End-to-end maintenance operations — work orders, assets, PM schedules, parts, meters, and requests | 13 tools |

## JSON Schemas

| Schema | Description |
|---|---|
| [upkeep-work-order-schema.json](json-schema/upkeep-work-order-schema.json) | Maintenance work order resource |
| [upkeep-asset-schema.json](json-schema/upkeep-asset-schema.json) | Physical asset resource |

## JSON Structure

| Structure | Description |
|---|---|
| [upkeep-work-order-structure.json](json-structure/upkeep-work-order-structure.json) | Field-level documentation for the Work Order resource |

## JSON-LD

| Context | Description |
|---|---|
| [upkeep-context.jsonld](json-ld/upkeep-context.jsonld) | Linked data context mapping UpKeep resources to schema.org |

## Examples

| Example | Description |
|---|---|
| [upkeep-create-work-order-example.json](examples/upkeep-create-work-order-example.json) | POST /work-orders request and response |
| [upkeep-list-assets-example.json](examples/upkeep-list-assets-example.json) | GET /assets with location filter response |

## Vocabulary

| File | Description |
|---|---|
| [upkeep-vocabulary.yml](vocabulary/upkeep-vocabulary.yml) | Domain vocabulary for UpKeep CMMS including maintenance, asset, and facility management concepts |

## Links

- **Website:** https://upkeep.com
- **Developer Documentation:** https://developers.onupkeep.com/
- **REST API Integration:** https://upkeep.com/integrations/rest-api/

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
