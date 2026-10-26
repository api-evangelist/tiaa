# TIAA (tiaa)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
