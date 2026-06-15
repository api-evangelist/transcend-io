# Transcend (transcend-io)

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
