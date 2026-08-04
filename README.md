# OpenTelemetry (opentelemetry)

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

Vendor-neutral open-source observability framework for cloud-native software, providing a collection of tools, APIs, and SDKs for instrumenting, generating, collecting, and exporting telemetry data including metrics, logs, and traces.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/opentelemetry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Cloud Native, Logging, Metrics, Monitoring, Observability, Open Source, Tracing

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### OpenTelemetry Protocol (OTLP) HTTP API
The OTLP HTTP API provides endpoints for exporting traces, metrics, and logs using the OpenTelemetry Protocol, the native wire format for transmitting telemetry data between instrumented applications, collectors, and observability backends.

**Human URL:** [https://opentelemetry.io/docs/specs/otlp/](https://opentelemetry.io/docs/specs/otlp/)

#### Tags:

 - Logging, Metrics, Observability, Tracing

#### Properties

- [Documentation](https://opentelemetry.io/docs/specs/otlp/)
- [OpenAPI](openapi.yml)
- [AsyncAPI](asyncapi/opentelemetry-otlp-asyncapi.yml)
- [JSONSchema](json-schema.json)
- [JSON-LD](context.jsonld)
- [Reference](https://opentelemetry.io/docs/specs/otlp/#otlphttp)
- [Getting Started](https://opentelemetry.io/docs/collector/)
- [Client Libraries](https://opentelemetry.io/docs/languages/)

### OpenTelemetry Protocol (OTLP) gRPC API
The OTLP gRPC API defines Protocol Buffers service definitions for exporting traces, metrics, and logs over gRPC. It is the primary transport for OpenTelemetry data between SDK instrumentation, the OpenTelemetry Collector, and observability backends, offering bidirectional streaming and efficient binary encoding.

**Human URL:** [https://opentelemetry.io/docs/specs/otlp/#otlpgrpc](https://opentelemetry.io/docs/specs/otlp/#otlpgrpc)

#### Tags:

 - gRPC, Logging, Metrics, Observability, Tracing

#### Properties

- [Documentation](https://opentelemetry.io/docs/specs/otlp/#otlpgrpc)
- [Reference](https://opentelemetry.io/docs/specs/otlp/#otlpgrpc-response)
- [GitHubRepository](https://github.com/open-telemetry/opentelemetry-proto)

### OpenTelemetry Collector API
The OpenTelemetry Collector is a vendor-agnostic proxy for receiving, processing, and exporting telemetry data. It exposes HTTP and gRPC endpoints for receiving OTLP data and provides a configuration API for managing pipelines, receivers, processors, and exporters at runtime via the zPages diagnostic extension and config file hot-reloading.

**Human URL:** [https://opentelemetry.io/docs/collector/](https://opentelemetry.io/docs/collector/)

#### Tags:

 - Collector, Configuration, Observability, Pipeline

#### Properties

- [Documentation](https://opentelemetry.io/docs/collector/)
- [Reference](https://opentelemetry.io/docs/collector/configuration/)
- [GitHubRepository](https://github.com/open-telemetry/opentelemetry-collector)

### OpenTelemetry SDK API
The OpenTelemetry SDK API specifies language-level interfaces for instrumentation, including the Tracer, Meter, and Logger APIs used by application code to create spans, record metrics, and emit log records. Implementations are available for all major programming languages including Java, Python, Go, JavaScript, .NET, Ruby, and others.

**Human URL:** [https://opentelemetry.io/docs/specs/otel/](https://opentelemetry.io/docs/specs/otel/)

#### Tags:

 - Instrumentation, Logging, Metrics, SDK, Tracing

#### Properties

- [Documentation](https://opentelemetry.io/docs/specs/otel/)
- [Reference](https://opentelemetry.io/docs/specs/otel/trace/api/)
- [Client Libraries](https://opentelemetry.io/docs/languages/)
- [GitHubRepository](https://github.com/open-telemetry/opentelemetry-specification)

## Common Properties

- [Website](https://opentelemetry.io/)
- [Documentation](https://opentelemetry.io/docs/)
- [Getting Started](https://opentelemetry.io/docs/getting-started/)
- [GitHub Organization](https://github.com/open-telemetry)
- [GitHubRepository](https://github.com/open-telemetry/opentelemetry-specification)
- [SDKs](https://opentelemetry.io/docs/languages/)
- [Blog](https://opentelemetry.io/blog/)
- [Community](https://opentelemetry.io/community/)
- [Slack](https://cloud-native.slack.com/archives/CJFCJHG4Q)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/open-telemetry)
- [Change Log](https://github.com/open-telemetry/opentelemetry-specification/blob/main/CHANGELOG.md)
- [Security](https://github.com/open-telemetry/opentelemetry-collector/security/policy)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
