# Salsa (salsa)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Salsa is embedded payroll infrastructure that lets SaaS platforms add native, multi-country (US and Canada) payroll to their products through REST and GraphQL APIs, embeddable UI components (Salsa Express), and real-time webhooks. Partner platforms provision employers and workers, run payroll, disburse worker payments, and handle tax setup and filings without leaving their own app. API access is partner-gated - Salsa issues sandbox and production Bearer API keys to approved platform partners.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salsa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salsa/refs/heads/main/apis.yml)

> Note: Salsa's real operating domain is **salsa.dev** (site www.salsa.dev, docs docs.salsa.dev, API api.salsa.dev). salsa.com / docs.salsa.com do not resolve to this provider; this catalog uses the accurate salsa.dev endpoints.

## Tags

- Payroll
- Embedded Finance
- Payroll as a Service
- Fintech
- Payments
- HR
- Tax
- Multi-Country

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Salsa Companies API

Create and manage employer (company) entities - business identity, addresses, bank accounts, signatories, work weeks, worker pay groups, and per-employer pay/deduction/benefit/time-off type configuration - representing a business that employs and pays workers through the partner platform.

- **Human URL:** [https://docs.salsa.dev/reference](https://docs.salsa.dev/reference)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Employers
- Companies
- Onboarding

#### Properties

- [Documentation](https://docs.salsa.dev/docs/building-with-salsa)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Workers API

Create and manage workers under an employer - W-2 employees and 1099 contractors - including contracts, work locations, bank accounts, personal information, capabilities, and terminations.

- **Human URL:** [https://docs.salsa.dev/reference](https://docs.salsa.dev/reference)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Workers
- Employees
- Contractors

#### Properties

- [Documentation](https://docs.salsa.dev/docs/building-with-salsa)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Pay Schedules API

Configure how and when workers are paid via worker pay groups, work weeks, and pay types that define pay frequency and cadence for an employer's payroll.

- **Human URL:** [https://docs.salsa.dev/reference](https://docs.salsa.dev/reference)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Pay Schedules
- Pay Groups
- Work Weeks

#### Properties

- [Documentation](https://docs.salsa.dev/docs/building-with-salsa)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Payrolls API

Create, preview, modify, confirm, and delete payroll runs for an employer, inspect payroll run state and payment records, and pull payroll journal, cash requirements, and overtime reports.

- **Human URL:** [https://docs.salsa.dev/docs/payroll-run-via-api](https://docs.salsa.dev/docs/payroll-run-via-api)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Payroll
- Pay Runs
- Reports

#### Properties

- [Documentation](https://docs.salsa.dev/docs/payroll-run-via-api)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Payments API

Create and manage individual worker payments with pay, compensations, and deductions; confirm, advance, and inspect payment records for off-cycle or per-worker disbursements outside a full payroll run.

- **Human URL:** [https://docs.salsa.dev/reference](https://docs.salsa.dev/reference)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Payments
- Disbursements
- Compensation

#### Properties

- [Documentation](https://docs.salsa.dev/docs/building-with-salsa)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Onboarding & Sessions API

Mint scoped user API tokens (EMPLOYER_ADMIN) that power the embeddable Salsa Express UI components, and create hosted onboarding flows plus mock-onboard helpers for employers and workers in the sandbox.

- **Human URL:** [https://docs.salsa.dev/docs/express-embedded-ui](https://docs.salsa.dev/docs/express-embedded-ui)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Onboarding
- Sessions
- Tokens

#### Properties

- [Documentation](https://docs.salsa.dev/docs/express-embedded-ui)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Tax API

Manage employer and worker tax setup and withholding configuration, surface tax documents, and receive tax-rate updates from agencies; tax calculation, filing, and remittance run inside Salsa's payroll engine for US and Canada.

- **Human URL:** [https://docs.salsa.dev/reference](https://docs.salsa.dev/reference)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Tax
- Withholding
- Compliance

#### Properties

- [Documentation](https://docs.salsa.dev/docs/building-with-salsa)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salsa Webhooks API

Register and manage webhook endpoints to receive real-time events - employer and worker lifecycle, onboarding status, bank account verification, payroll run status, funding and disbursement money movement, tax updates, and operational notifications.

- **Human URL:** [https://docs.salsa.dev/reference](https://docs.salsa.dev/reference)
- **Base URL:** `https://api.salsa.dev/api/rest/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.salsa.dev/docs/building-with-salsa)
- [API Reference](https://docs.salsa.dev/reference)
- [OpenAPI](openapi/salsa-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salsa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salsa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/salsa-payroll)
- [LinkedIn](https://www.linkedin.com/company/salsa-dev)
- [Website](https://www.salsa.dev/)
- [Documentation](https://docs.salsa.dev/)
- [Plans](plans/salsa-plans-pricing.yml)
- [Rate Limits](rate-limits/salsa-rate-limits.yml)
- [Fin Ops](finops/salsa-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
