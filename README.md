# Transcend

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

Transcend is a privacy and data permissioning platform that helps enterprises decide in real time whether customer data can be used for a given purpose. The platform spans data discovery and inventory, data subject request automation, consent and preference management, privacy assessments, and an AI governance layer that enforces policies at the source. Transcend's Sombra security gateway runs inside customer environments so Transcend itself never accesses customer data or API keys. Developers integrate via a REST API documented with OpenAPI, a GraphQL API for non-personal data and configuration tasks, an official CLI distributed on npm, and a transcend.yml configuration file that lets teams manage their data map as code. The platform serves AI, consumer, healthcare, fintech, media, and B2B enterprises.

**Areas:** Transcend · Privacy · Data Governance · Consent · Preference Management · DSR · Data Inventory · AI Governance · GDPR · CCPA · Compliance · Webhook

## Transcend on APIs.io

Everything profiled for Transcend is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/transcend-io/](https://apis.io/providers/transcend-io/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Transcend GraphQL API](https://apis.io/apis/transcend-io/transcend-graphql-api/) — GraphQL API and Developer Tools wrapper for non-personal data tasks such as creating data silos, account management, and other configuration operations on…
- [Transcend CLI](https://apis.io/apis/transcend-io/transcend-cli/) — Official command line interface for Transcend, distributed on npm as @transcend-io/cli. Supports schema sync, transcend.yml-based data map definitions, and…
- [Transcend MCP Servers](https://apis.io/apis/transcend-io/transcend-mcp/) — Model Context Protocol servers published under @transcend-io/* so AI agents can manage Transcend privacy operations. Includes per-domain servers for admin,…
- [Transcend Consent API](https://apis.io/apis/transcend-io/transcend-io-consent-api/) — Client-side consent sync used by the Consent Manager.
- [Transcend Custom Integration API](https://apis.io/apis/transcend-io/transcend-io-custom-integration-api/) — Stream files, push datapoints, and respond to access, erasure, opt-in, and opt-out requests.
- [Transcend Data Subject Request API](https://apis.io/apis/transcend-io/transcend-io-data-subject-request-api/) — Submit, poll, and download data subject requests.
- [Transcend LLM Classifier API](https://apis.io/apis/transcend-io/transcend-io-llm-classifier-api/) — Text classification and Named Entity Recognition for unstructured data discovery.
- [Transcend Preferences API](https://apis.io/apis/transcend-io/transcend-io-preferences-api/) — Server-side preference store CRUD and query operations.
- [Transcend Preflight API](https://apis.io/apis/transcend-io/transcend-io-preflight-api/) — Enrich identifiers before downstream DSR processing.
- [Transcend Public Keys API](https://apis.io/apis/transcend-io/transcend-io-public-keys-api/) — Public JWT signing keys exposed by the Sombra gateway.
- [Transcend API](https://apis.io/apis/transcend-io/transcend-io-transcend-api-api/) — The Transcend API API from Transcend — 0 operation(s) for transcend api.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Transcend GraphQL API](https://apis.io/graphqls/transcend-io/transcend-io-graphql/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Classification](https://apis.io/schemas/transcend-io/transcend-classification/)
- [DataSilo](https://apis.io/schemas/transcend-io/transcend-data-silo/)
- [DataSubjectRequest](https://apis.io/schemas/transcend-io/transcend-data-subject-request/)
- [PreferenceRecord](https://apis.io/schemas/transcend-io/transcend-preference-record/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Transcend Data Subject Request Structure](https://apis.io/json-structure/transcend-io/transcend-data-subject-request-structure/)
- [Transcend Preference Record Structure](https://apis.io/json-structure/transcend-io/transcend-preference-record-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Transcend Io Context](https://apis.io/jsonld/transcend-io/transcend-io-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Transcend Privacy and Data Permissioning Vocabulary](https://apis.io/vocabularies/transcend-io/transcend-io-vocabulary/)

#### Examples (8)

Example requests and responses.

- [Transcend Classify Text Example](https://apis.io/examples/transcend-io/transcend-classify-text-example/)
- [Transcend Consent Sync Example](https://apis.io/examples/transcend-io/transcend-consent-sync-example/)
- [Transcend Data Silo Example](https://apis.io/examples/transcend-io/transcend-data-silo-example/)
- [Transcend Enrich Identifiers Example](https://apis.io/examples/transcend-io/transcend-enrich-identifiers-example/)
- [Transcend Get Dsr Example](https://apis.io/examples/transcend-io/transcend-get-dsr-example/)
- [Transcend Submit Dsr Example](https://apis.io/examples/transcend-io/transcend-submit-dsr-example/)
- [Transcend Upsert Preferences Example](https://apis.io/examples/transcend-io/transcend-upsert-preferences-example/)
- [Transcend Webhook Dsr Job Example](https://apis.io/examples/transcend-io/transcend-webhook-dsr-job-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [Transcend Consent API](https://apis.io/collections/transcend-io/open-transcend-io-consent-api/)
- [Transcend Custom Integration API](https://apis.io/collections/transcend-io/open-transcend-io-custom-integration-api/)
- [Transcend Data Subject Request API](https://apis.io/collections/transcend-io/open-transcend-io-data-subject-request-api/)
- [Transcend LLM Classifier API](https://apis.io/collections/transcend-io/open-transcend-io-llm-classifier-api/)
- [Transcend Preferences API](https://apis.io/collections/transcend-io/open-transcend-io-preferences-api/)
- [Transcend Preflight API](https://apis.io/collections/transcend-io/open-transcend-io-preflight-api/)
- [Transcend Public Keys API](https://apis.io/collections/transcend-io/open-transcend-io-public-keys-api/)
- [Transcend Transcend API API](https://apis.io/collections/transcend-io/open-transcend-io-transcend-api-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Transcend — jsonschema rules](https://apis.io/rules/transcend-io/transcend-io-jsonschema-spectral-rules/)
- [Transcend — transcend rules](https://apis.io/rules/transcend-io/transcend-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Transcend Io Domain Security](https://apis.io/security/transcend-io/transcend-io-domain-security/)
- [Transcend Io Trust Center](https://apis.io/security/transcend-io/transcend-io-trust-center/)
- [Transcend Io Vulnerability Disclosure](https://apis.io/security/transcend-io/transcend-io-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Transcend Io Plans Pricing](https://apis.io/plans/transcend-io/transcend-io-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Transcend Io Rate Limits](https://apis.io/rate-limits/transcend-io/transcend-io-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Transcend Io Finops](https://apis.io/finops/transcend-io/transcend-io-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://transcend.io/)
- [Documentation](https://docs.transcend.io/docs)
- [Pricing](https://transcend.io/pricing)
- [Blog](https://transcend.io/blog)
- [Security](https://transcend.io/security)
- [GitHub](https://github.com/transcend-io)

## API Evangelist rating

**Kin Score 44.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.2 |
| Contract quality | 60.3 |
| Contract governance | 27.3 |
| Operational transparency | 28.9 |
| Developer ergonomics | 26.2 |
| Access clarity | 39.5 |

**Agent readiness 26.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/transcend-io/](https://apis.io/providers/transcend-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Transcend: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/transcend-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
