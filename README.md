# Transcend (transcend-io)

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

Transcend is a privacy and data permissioning platform that helps enterprises decide in real time whether customer data can be used for a given purpose. The platform spans data discovery and inventory, data subject request automation, consent and preference management, privacy assessments, and an AI governance layer that enforces policies at the source. Transcend's Sombra security gateway runs inside customer environments so Transcend itself never accesses customer data or API keys. Developers integrate via a REST API documented with OpenAPI, a GraphQL API for non-personal data and configuration tasks, an official CLI distributed on npm, and a transcend.yml configuration file that lets teams manage their data map as code. The platform serves AI, consumer, healthcare, fintech, media, and B2B enterprises.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/transcend-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/transcend-io/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Transcend
- Privacy
- Data Governance
- Consent
- Preference Management
- DSR
- Data Inventory
- AI Governance
- GDPR
- CCPA
- Compliance
- Webhooks
- GraphQL
- MCP
- SDK
- Terraform
- Helm

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Transcend API

REST API that powers Transcend's privacy operations, including data subject requests, preflight identifier enrichment, custom integrations for access and erasure, preferences and consent management, an LLM classifier for NER and text classification, public JWT signing keys, and webhooks for DSR jobs, preflight requests, and consent manager deployment. The API is described by an OpenAPI specification and is available on both EU and US backends, with the EU backend as the CLI default.

- **Human URL:** [https://docs.transcend.io/docs/api-reference](https://docs.transcend.io/docs/api-reference)
- **Base URL:** `https://api.transcend.io`

#### Tags

- DSR
- Consent
- Preferences
- Webhooks
- LLM Classifier
- Custom Integration

#### Properties

- [Documentation](https://docs.transcend.io/docs/api-reference)
- [OpenAPI](https://docs.transcend.io/api/oas.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A P I30](https://docs.transcend.io/api/oas.json?v=3.0)
- [U S Backend](https://api.us.transcend.io)
- [Webhooks](https://docs.transcend.io/docs/api-reference)
- [Status](https://status.transcend.io)
- [Sign Up](https://app.transcend.io/login)
- [Local Open A P I](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/openapi/transcend-io-openapi.yml)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/rules/transcend-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/json-schema/transcend-data-subject-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/json-schema/transcend-preference-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/json-ld/transcend-io-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/vocabulary/transcend-io-vocabulary.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/plans/transcend-io-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/rate-limits/transcend-io-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/transcend-io/main/finops/transcend-io-finops.yml)

### Transcend GraphQL API

GraphQL API and Developer Tools wrapper for non-personal data tasks such as creating data silos, account management, and other configuration operations on the Transcend platform.

- **Human URL:** [https://docs.transcend.io/docs/api-reference](https://docs.transcend.io/docs/api-reference)

#### Tags

- GraphQL
- Data Silos
- Configuration
- Admin

#### Properties

- [Documentation](https://docs.transcend.io/docs/api-reference)
- [Graph Q L](https://docs.transcend.io/docs/api-reference)

### Transcend CLI

Official command line interface for Transcend, distributed on npm as @transcend-io/cli. Supports schema sync, transcend.yml-based data map definitions, and a wide range of platform operations. Defaults to the EU backend, with a flag to target the US backend.

- **Human URL:** [https://github.com/transcend-io/cli](https://github.com/transcend-io/cli)

#### Tags

- CLI
- npm
- Configuration
- Data Map

#### Properties

- [Source Code](https://github.com/transcend-io/cli)
- [Package Manager](https://www.npmjs.com/package/@transcend-io/cli)
- [Documentation](https://docs.transcend.io/docs/api-reference)

### Transcend MCP Servers

Model Context Protocol servers published under @transcend-io/* so AI agents can manage Transcend privacy operations. Includes per-domain servers for admin, assessments, consent, data discovery, DSR, inventory, preferences, and workflows, plus a meta MCP package that aggregates them. Distributed from the transcend-io/tools monorepo.

- **Human URL:** [https://github.com/transcend-io/tools/tree/main/packages/mcp](https://github.com/transcend-io/tools/tree/main/packages/mcp)

#### Tags

- MCP
- AI Agents
- Tooling

#### Properties

- [Source Code](https://github.com/transcend-io/tools/tree/main/packages/mcp)
- [Package Manager](https://www.npmjs.com/package/@transcend-io/mcp)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-admin)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-assessment)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-consent)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-discovery)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-dsr)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-inventory)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-preferences)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp-server-workflows)

## Common Properties

- [Website](https://transcend.io/)
- [Documentation](https://docs.transcend.io/docs)
- [OpenAPI](https://docs.transcend.io/api/oas.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Source Code](https://github.com/transcend-io)
- [GitHub Organization](https://github.com/transcend-io)
- [Status](https://status.transcend.io)
- [Sign Up](https://app.transcend.io/login)
- [L L Ms Txt](https://docs.transcend.io/llms.txt)
- [C L I](https://github.com/transcend-io/tools/tree/main/packages/cli)
- [SDK](https://github.com/transcend-io/tools/tree/main/packages/sdk)
- [Tools](https://github.com/transcend-io/tools)
- [Tools](https://github.com/transcend-io/tools/tree/main/packages/mcp/mcp)
- [Tools](https://github.com/transcend-io/terraform-provider-transcend)
- [Tools](https://github.com/transcend-io/terraform-aws-sombra)
- [Tools](https://github.com/transcend-io/helm-charts)
- [Tools](https://github.com/transcend-io/consent-manager-ui)
- [Tools](https://github.com/transcend-io/Transcend-spm-sdk)
- [Code Examples](https://github.com/transcend-io/examples)
- [Privacy Types](https://github.com/transcend-io/tools/tree/main/packages/privacy-types)
- [Press Releases](https://transcend.io/press)
- [Blog](https://transcend.io/blog)
- [Security](https://transcend.io/security)
- [Pricing](https://transcend.io/pricing)
- [Customers](https://transcend.io/customers)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
