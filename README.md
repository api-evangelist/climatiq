# Climatiq (climatiq)
Climatiq provides a developer-first API for carbon accounting and emissions calculations. The platform packages a curated emission-factor database together with calculation endpoints that turn activity or spend data into auditable CO2-equivalent estimates aligned with the GHG Protocol. Capabilities span search across the factor catalog, generic activity-based estimation, and purpose-built endpoints for travel, freight (GLEC), energy, cloud computing, procurement, and the EU Carbon Border Adjustment Mechanism.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Carbon Accounting, Carbon Emissions, Climate, Energy, Environment, GHG Protocol, Sustainability

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-27

## APIs

### Climatiq API
The Climatiq API is a single REST surface at api.climatiq.io that groups search, estimation, and reference operations under a shared API-key (Bearer) auth model. It exposes /data/v1/search for discovering emission factors; /data/v1/estimate for activity-based estimation; family endpoints under /travel, /freight, /energy, /compute, /procurement, /autopilot, /classifications, and /cbam for purpose-built calculations; and reference endpoints for regions and unit types. All endpoints return CO2e in kilograms together with the underlying factor and gas breakdown.

**Human URL:** [https://www.climatiq.io/docs/api-reference](https://www.climatiq.io/docs/api-reference)

**Base URL:** https://api.climatiq.io

#### Tags

- Carbon Emissions, Emission Factors, GHG Protocol, Sustainability

#### Properties

- [Documentation](https://www.climatiq.io/docs/api-reference)
- [Getting Started](https://www.climatiq.io/docs/guides/tutorials/quickstart)
- [Search Reference](https://www.climatiq.io/docs/api-reference/search)
- [Estimate Reference](https://www.climatiq.io/docs/api-reference/estimate)
- [Travel Reference](https://www.climatiq.io/docs/api-reference/travel)
- [Intermodal Freight Reference](https://www.climatiq.io/docs/api-reference/intermodal-freight)
- [Energy Reference](https://www.climatiq.io/docs/api-reference/energy)
- [Computing Reference](https://www.climatiq.io/docs/api-reference/computing)
- [Procurement Reference](https://www.climatiq.io/docs/api-reference/procurement)
- [Autopilot Reference](https://www.climatiq.io/docs/api-reference/autopilot)
- [Classifications Reference](https://www.climatiq.io/docs/api-reference/classifications)
- [Custom Mappings Reference](https://www.climatiq.io/docs/api-reference/custom-mappings)
- [CBAM Reference](https://www.climatiq.io/docs/api-reference/cbam)
- [Change Log](https://www.climatiq.io/docs/changelogs/api-release)
- [OpenAPI](openapi/climatiq-openapi.yml)

## Common Properties

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
- [OpenAPI](openapi/climatiq-openapi.yml)
- [JSON Schema](json-schema/climatiq-emission-estimate-schema.json)
- [JSON-LD Context](json-ld/climatiq-context.jsonld)
- [Spectral Ruleset](rules/climatiq-rules.yml)
- [Naftiko Capabilities](capabilities/climatiq-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
