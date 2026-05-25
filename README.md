# Transcend

San-Francisco-based privacy and data permissioning platform. Transcend helps
enterprises decide in real time whether customer data can be used for a given
purpose — across data inventory, data subject request (DSR) automation,
consent and preference management, privacy assessments, and AI governance.
Transcend's Sombra security gateway runs inside customer environments so
Transcend itself never accesses customer data or API keys.

## Surface

- REST API at `https://api.transcend.io` (EU default) and `https://api.us.transcend.io` (US)
- GraphQL API for non-personal-data tasks (data silo config, account management)
- TypeScript SDK and CLI distributed under `@transcend-io/*` from the `transcend-io/tools` monorepo
- Eight per-domain MCP servers plus an aggregate `@transcend-io/mcp` package for AI agents
- Terraform provider, Terraform Sombra module, Helm charts
- Native iOS and Android consent SDKs
- airgap.js consent edge for client-side `/sync`
- Webhooks: DSR jobs, preflight requests, manual DSR (AVC), Consent Manager deployed
- LLM Classifier for PII/PHI/PCI text classification and Named Entity Recognition

## Repository Layout

| Folder | Contents |
|---|---|
| `apis.yml` | APIs.json index of the Transcend platform |
| `openapi/` | OpenAPI 3.1 spec for the Transcend REST API |
| `examples/` | Request/response examples for key operations and webhooks |
| `rules/` | Spectral ruleset enforcing Transcend API conventions |
| `capabilities/` | Naftiko capability definitions (shared + per-workflow) |
| `json-schema/` | JSON Schema for DSR, preference, data silo, classification |
| `json-structure/` | API Commons JSON Structure documents |
| `json-ld/` | JSON-LD context aligning Transcend types with DPV and schema.org |
| `vocabulary/` | Vocabulary mapping DSR types, consent, and purposes to DPV/GDPR/CCPA |
| `plans/` | API Commons Plans 0.1 scaffold of Transcend's commercial offerings |
| `rate-limits/` | API Commons Rate Limits 0.1 with headers and recovery strategies |
| `finops/` | FinOps Framework alignment (FOCUS v1.3) |
| `review.yml` | API Evangelist review of the Transcend developer surface |

## Capabilities

- `capabilities/dsr-fulfillment.yaml` — End-to-end DSR fulfillment
- `capabilities/consent-and-preferences.yaml` — Sync consent across web, mobile, backend
- `capabilities/ai-governance.yaml` — Real-time AI data permissioning + PII screening
- `capabilities/custom-integration.yaml` — Connect a custom data silo to Transcend

## References

- Website: <https://transcend.io/>
- Documentation: <https://docs.transcend.io/docs>
- API Reference: <https://docs.transcend.io/docs/api-reference>
- OpenAPI: <https://docs.transcend.io/api/oas.json>
- GitHub: <https://github.com/transcend-io>
- Developer Tools Monorepo: <https://github.com/transcend-io/tools>
- Status: <https://status.transcend.io>
- LLMs.txt: <https://docs.transcend.io/llms.txt>

## Provenance

This profile was authored with [Claude Code](https://www.anthropic.com/) by
Anthropic. The Transcend MCP servers profiled here are designed to be
consumed by MCP-capable AI hosts including Claude.
