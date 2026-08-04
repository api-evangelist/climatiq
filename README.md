# Climatiq (climatiq)

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

Climatiq provides a developer-first API for carbon accounting and emissions calculations. The platform packages a curated emission-factor database together with calculation endpoints that turn activity or spend data into auditable CO2-equivalent estimates aligned with the GHG Protocol. Capabilities span search across the factor catalog, generic activity-based estimation, and purpose-built endpoints for travel, freight (GLEC), energy, cloud computing, procurement, and the EU Carbon Border Adjustment Mechanism. The API is keyed (Bearer token) and hosted at api.climatiq.io.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Carbon Accounting
- Carbon Emissions
- Climate
- Energy
- Environment
- GHG Protocol
- Sustainability

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-05-19

## APIs

### Climatiq API

The Climatiq API is a single REST surface at api.climatiq.io that groups search, estimation, and reference operations under a shared API-key (Bearer) auth model. It exposes /data/v1/search for discovering emission factors; /data/v1/estimate for activity-based estimation; family endpoints under /travel, /freight, /energy, /compute, /procurement, /autopilot, /classifications, and /cbam for purpose-built calculations; and reference endpoints for regions and unit types. All endpoints return CO2e in kilograms together with the underlying factor and gas breakdown.

- **Human URL:** [https://www.climatiq.io/docs/api-reference](https://www.climatiq.io/docs/api-reference)
- **Base URL:** `https://api.climatiq.io`

#### Tags

- Carbon Emissions
- Emission Factors
- GHG Protocol
- Sustainability

#### Properties

- [Documentation](https://www.climatiq.io/docs/api-reference)
- [Getting Started](https://www.climatiq.io/docs/guides/tutorials/quickstart)
- [Reference](https://www.climatiq.io/docs/api-reference/search)
- [Reference](https://www.climatiq.io/docs/api-reference/estimate)
- [Reference](https://www.climatiq.io/docs/api-reference/travel)
- [Reference](https://www.climatiq.io/docs/api-reference/intermodal-freight)
- [Reference](https://www.climatiq.io/docs/api-reference/energy)
- [Reference](https://www.climatiq.io/docs/api-reference/computing)
- [Reference](https://www.climatiq.io/docs/api-reference/procurement)
- [Reference](https://www.climatiq.io/docs/api-reference/autopilot)
- [Reference](https://www.climatiq.io/docs/api-reference/classifications)
- [Reference](https://www.climatiq.io/docs/api-reference/custom-mappings)
- [Reference](https://www.climatiq.io/docs/api-reference/cbam)
- [Changelog](https://www.climatiq.io/docs/changelogs/api-release)
- [OpenAPI](openapi/climatiq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climatiq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climatiq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/climatiq)
- [LinkedIn](https://www.linkedin.com/company/climatiq)
- [Website](https://www.climatiq.io/)
- [Portal](https://www.climatiq.io/docs)
- [Documentation](https://www.climatiq.io/docs/api-reference)
- [Getting Started](https://www.climatiq.io/docs/guides/tutorials/quickstart)
- [Pricing](https://www.climatiq.io/pricing)
- [Blog](https://www.climatiq.io/blog)
- [Trust](https://trust.climatiq.io/)
- [Support](https://www.climatiq.io/support)
- [Customers](https://www.climatiq.io/customers)
- [Login](https://auth.climatiq.io/login)
- [Playground](https://www.climatiq.io/demo)
- [Partners](https://www.climatiq.io/partner-with-climatiq)
- [Newsletter](https://www.climatiq.io/newsletter)
- [Versioning](https://www.climatiq.io/docs/changelogs/api-release)
- [OpenAPI](openapi/climatiq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/climatiq-emission-estimate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/climatiq-context.jsonld)
- [Spectral Rules](rules/climatiq-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
