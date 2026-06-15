# TIAA (tiaa)

TIAA (Teachers Insurance and Annuity Association of America) is a leading provider of financial services in the academic, research, medical, cultural, and government fields. Originally founded to provide retirement security for educators, TIAA now offers retirement services, insurance, brokerage, and investment management products to individuals and institutions. TIAA operates a developer portal at developer.tiaa.org exposing APIs for financial data aggregation (FDX standard), secure income account management, and gateway integrations enabling plan portability and fintech connectivity.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/apis.yml)

## Tags

- Finance
- Financial Data
- Fintech
- Insurance
- Investment Management
- Retirement
- Wealth Management

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### TIAA Financial Data Exchange API

The TIAA Financial Data Exchange (FDX) API provides customer account details to authorized fintechs and financial aggregators with customer consent. Built on the FDX open-standard (OAuth 2.0), it offers a secure alternative to screen scraping and enables third-party apps to retrieve account balances, transactions, investment positions, and income data from TIAA retirement and brokerage accounts.

- **Human URL:** [https://developer.tiaa.org/public/fdx](https://developer.tiaa.org/public/fdx)
- **Base URL:** `https://api.tiaa.org/fdx/v6`

#### Tags

- Account Aggregation
- Financial Data
- FDX
- Open Finance
- Retirement

#### Properties

- [Documentation](https://developer.tiaa.org/public/fdx)
- [Authentication](https://developer.tiaa.org/public/fdx#authentication)
- [OpenAPI](openapi/tiaa-fdx-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiaa-fdx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiaa-fdx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIAA Secure Income Account API

The TIAA Secure Income Account (SIA) API enables recordkeepers and plan administrators to integrate TIAA's guaranteed lifetime income product into custom target-date model portfolios and managed account solutions. Built using the OpenAPI Specification (OAS) and authenticated via OAuth 2.0 Client Credentials Flow, the SIA API supports account setup, contribution management, and participant income projections for defined contribution plan participants.

- **Human URL:** [https://developer.tiaa.org/public/sia](https://developer.tiaa.org/public/sia)
- **Base URL:** `https://api.tiaa.org/sia/v1`

#### Tags

- Annuity
- Guaranteed Income
- Plan Administration
- Recordkeeping
- Retirement
- Secure Income

#### Properties

- [Documentation](https://developer.tiaa.org/public/sia)
- [Authentication](https://developer.tiaa.org/public/sia#authentication)
- [OpenAPI](openapi/tiaa-sia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tiaa-sia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiaa-sia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIAA Gateway API

The TIAA Gateway is a cloud-based API layer enabling product portability and interoperability across retirement ecosystem partners. It allows banking institutions, financial aggregators, and plan sponsor platforms to expose TIAA retirement account data within their own apps and experiences. The Gateway supports FDX, ACORD, and SPARK standards and has more than 10 external partners connected.

- **Human URL:** [https://www.tiaa.org/public/pdf/t/tiaa-gateway-drives-product-portability.pdf](https://www.tiaa.org/public/pdf/t/tiaa-gateway-drives-product-portability.pdf)
- **Base URL:** `https://api.tiaa.org/gateway/v1`

#### Tags

- Financial Data
- Integration
- Open Finance
- Plan Portability
- Retirement

#### Properties

- [Documentation](https://www.tiaa.org/public/pdf/t/tiaa-gateway-drives-product-portability.pdf)
- [Portal](https://developer.tiaa.org)
- [Postman Collection](collections/tiaa-fdx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiaa-fdx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tiaa-sia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiaa-sia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TIAA Payroll360 API

TIAA Payroll360 enables direct API connections between HR and payroll systems and TIAA's plan administration platform, automating deductions management, employer onboarding, and payroll data integrity. Supports SPARK 2.0 CR and TIAA-specific FLEX and OPS formats.

- **Human URL:** [https://developer.tiaa.org/public/payroll360](https://developer.tiaa.org/public/payroll360)
- **Base URL:** `https://api.tiaa.org/payroll360/v1`

#### Tags

- HR
- Payroll
- Plan Administration
- Retirement
- SPARK

#### Properties

- [Documentation](https://developer.tiaa.org/public/payroll360)
- [Postman Collection](collections/tiaa-fdx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiaa-fdx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/tiaa-sia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tiaa-sia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.tiaa.org)
- [Website](https://www.tiaa.org)
- [Documentation](https://developer.tiaa.org/public/fdx)
- [Blog](https://www.tiaa.org/public/learn)
- [LinkedIn](https://www.linkedin.com/company/tiaa)
- [Twitter](https://twitter.com/tiaa)
- [Privacy Policy](https://www.tiaa.org/public/pdf/t/privacy_notice.pdf)
- [Terms of Service](https://www.tiaa.org/public/pdf/t/tiaa_website_terms_of_use.pdf)
- [JSON-LD](json-ld/tiaa-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/tiaa-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tiaa-participant-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
