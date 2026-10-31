# OpenTelemetry

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

Vendor-neutral open-source observability framework for cloud-native software, providing a collection of tools, APIs, and SDKs for instrumenting, generating, collecting, and exporting telemetry data including metrics, logs, and traces.

**Areas:** Cloud-Native · Logging · Metrics · Monitoring · Observability · Open Source · Tracing

## OpenTelemetry on APIs.io

Everything profiled for OpenTelemetry is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/opentelemetry/](https://apis.io/providers/opentelemetry/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [OpenTelemetry Protocol (OTLP) gRPC API](https://apis.io/apis/opentelemetry/opentelemetry-protocol-otlp-grpc-api/) — The OTLP gRPC API defines Protocol Buffers service definitions for exporting traces, metrics, and logs over gRPC. It is the primary transport for…
- [OpenTelemetry Collector API](https://apis.io/apis/opentelemetry/opentelemetry-collector-api/) — The OpenTelemetry Collector is a vendor-agnostic proxy for receiving, processing, and exporting telemetry data. It exposes HTTP and gRPC endpoints for…
- [OpenTelemetry SDK API](https://apis.io/apis/opentelemetry/opentelemetry-sdk-api/) — The OpenTelemetry SDK API specifies language-level interfaces for instrumentation, including the Tracer, Meter, and Logger APIs used by application code to…
- [OpenTelemetry Logs API](https://apis.io/apis/opentelemetry/opentelemetry-logs-api/) — The Logs API from OpenTelemetry — 1 operation(s) for logs.
- [OpenTelemetry Metrics API](https://apis.io/apis/opentelemetry/opentelemetry-metrics-api/) — The Metrics API from OpenTelemetry — 1 operation(s) for metrics.
- [OpenTelemetry Traces API](https://apis.io/apis/opentelemetry/opentelemetry-traces-api/) — The Traces API from OpenTelemetry — 1 operation(s) for traces.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [OpenTelemetry Protocol (OTLP) Telemetry Events](https://apis.io/asyncapis/opentelemetry/opentelemetry-otlp-asyncapi/)

#### Event channels (3)

Individual events and webhooks the provider emits.

- [/v1/logs](https://apis.io/channels/opentelemetry/v1-logs/)
- [/v1/metrics](https://apis.io/channels/opentelemetry/v1-metrics/)
- [/v1/traces](https://apis.io/channels/opentelemetry/v1-traces/)

#### Collections (3)

Postman and Open Collection request collections.

- [OpenTelemetry Protocol (OTLP) HTTP Logs API](https://apis.io/collections/opentelemetry/open-opentelemetry-logs-api/)
- [OpenTelemetry Protocol (OTLP) HTTP Metrics API](https://apis.io/collections/opentelemetry/open-opentelemetry-metrics-api/)
- [OpenTelemetry Protocol (OTLP) HTTP Traces API](https://apis.io/collections/opentelemetry/open-opentelemetry-traces-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [OpenTelemetry — asyncapi rules](https://apis.io/rules/opentelemetry/opentelemetry-asyncapi-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Opentelemetry Domain Security](https://apis.io/security/opentelemetry/opentelemetry-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Opentelemetry Plans Pricing](https://apis.io/plans/opentelemetry/opentelemetry-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Opentelemetry Rate Limits](https://apis.io/rate-limits/opentelemetry/opentelemetry-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Opentelemetry Finops](https://apis.io/finops/opentelemetry/opentelemetry-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://opentelemetry.io/)
- [Documentation](https://opentelemetry.io/docs/)
- [Getting started](https://opentelemetry.io/docs/getting-started/)
- [Changelog](https://github.com/open-telemetry/opentelemetry-specification/blob/main/CHANGELOG.md)
- [Blog](https://opentelemetry.io/blog/)
- [Security](https://github.com/open-telemetry/opentelemetry-collector/security/policy)
- [GitHub](https://github.com/open-telemetry)

## API Evangelist rating

**Kin Score 38.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 57.6 |
| Contract governance | 13.6 |
| Operational transparency | 39.5 |
| Developer ergonomics | 42.9 |
| Access clarity | 7.9 |

**Agent readiness 27.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | verified |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/opentelemetry/](https://apis.io/providers/opentelemetry/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OpenTelemetry: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/opentelemetry/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
