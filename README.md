# TIAA

TIAA (Teachers Insurance and Annuity Association of America) is a leading provider of financial services in the academic, research, medical, cultural, and government fields. Originally founded to provide retirement security for educators, TIAA now offers retirement services, insurance, brokerage, and investment management products to individuals and institutions. TIAA operates a developer portal at developer.tiaa.org exposing APIs for financial data aggregation (FDX standard), secure income account management, and gateway integrations enabling plan portability and fintech connectivity.

**Website:** [https://www.tiaa.org](https://www.tiaa.org)  
**Developer Portal:** [https://developer.tiaa.org](https://developer.tiaa.org)

## APIs

| API | Description | Docs |
|-----|-------------|------|
| TIAA Financial Data Exchange API | Customer-consented account, transaction, and investment data via FDX standard | [Docs](https://developer.tiaa.org/public/fdx) |
| TIAA Secure Income Account API | Plan administration and participant management for guaranteed income product | [Docs](https://developer.tiaa.org/public/sia) |
| TIAA Gateway API | Cloud-based API layer for plan portability and partner integrations | [Docs](https://www.tiaa.org/public/pdf/t/tiaa-gateway-drives-product-portability.pdf) |
| TIAA Payroll360 API | HR and payroll system integrations for plan administration | [Docs](https://developer.tiaa.org/public/payroll360) |

## OpenAPI Specifications

| Spec | Path |
|------|------|
| TIAA FDX API | [openapi/tiaa-fdx-openapi.yml](openapi/tiaa-fdx-openapi.yml) |
| TIAA SIA API | [openapi/tiaa-sia-openapi.yml](openapi/tiaa-sia-openapi.yml) |

## JSON Schemas

| Schema | Path |
|--------|------|
| TIAA Account | [json-schema/tiaa-account-schema.json](json-schema/tiaa-account-schema.json) |
| TIAA SIA Participant | [json-schema/tiaa-participant-schema.json](json-schema/tiaa-participant-schema.json) |

## JSON Structure

| Structure | Path |
|-----------|------|
| TIAA Account Structure | [json-structure/tiaa-account-structure.json](json-structure/tiaa-account-structure.json) |

## JSON-LD

| Context | Path |
|---------|------|
| TIAA Context | [json-ld/tiaa-context.jsonld](json-ld/tiaa-context.jsonld) |

## Examples

| Example | Path |
|---------|------|
| FDX List Accounts | [examples/tiaa-fdx-list-accounts-example.json](examples/tiaa-fdx-list-accounts-example.json) |
| FDX List Transactions | [examples/tiaa-fdx-list-transactions-example.json](examples/tiaa-fdx-list-transactions-example.json) |
| SIA Enroll Participant | [examples/tiaa-sia-enroll-participant-example.json](examples/tiaa-sia-enroll-participant-example.json) |
| SIA Get Income Projection | [examples/tiaa-sia-get-income-projection-example.json](examples/tiaa-sia-get-income-projection-example.json) |

## Spectral Rules

| Ruleset | Path |
|---------|------|
| TIAA API Rules | [rules/tiaa-rules.yml](rules/tiaa-rules.yml) |

## Naftiko Capabilities

### Shared API Definitions

| API | Path |
|-----|------|
| TIAA FDX | [capabilities/shared/tiaa-fdx.yaml](capabilities/shared/tiaa-fdx.yaml) |
| TIAA SIA | [capabilities/shared/tiaa-sia.yaml](capabilities/shared/tiaa-sia.yaml) |

### Workflow Capabilities

| Workflow | APIs | Description |
|----------|------|-------------|
| [Retirement Data Access](capabilities/retirement-data-access.yaml) | FDX + SIA | Unified access to TIAA retirement account data and plan administration |

## Vocabulary

| Vocabulary | Path |
|------------|------|
| TIAA Vocabulary | [vocabulary/tiaa-vocabulary.yml](vocabulary/tiaa-vocabulary.yml) |
