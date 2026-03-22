# OpenTelemetry (opentelemetry)
Vendor-neutral open-source observability framework for cloud-native software, providing a collection of tools, APIs, and SDKs for instrumenting, generating, collecting, and exporting telemetry data including metrics, logs, and traces.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/opentelemetry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Observability, Monitoring, Tracing, Metrics, Logging, Cloud Native, Open Source

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### OpenTelemetry Protocol (OTLP) HTTP API
The OTLP HTTP API provides endpoints for exporting traces, metrics, and logs using the OpenTelemetry Protocol, the native wire format for transmitting telemetry data between instrumented applications, collectors, and observability backends.

**Human URL:** [https://opentelemetry.io/docs/specs/otlp/](https://opentelemetry.io/docs/specs/otlp/)


#### Tags:

 - Observability, Tracing, Metrics, Logging

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

 - gRPC, Observability, Tracing, Metrics, Logging

#### Properties

- [Documentation](https://opentelemetry.io/docs/specs/otlp/#otlpgrpc)
- [Reference](https://opentelemetry.io/docs/specs/otlp/#otlpgrpc-response)
- [GitHubRepository](https://github.com/open-telemetry/opentelemetry-proto)

### OpenTelemetry Collector API
The OpenTelemetry Collector is a vendor-agnostic proxy for receiving, processing, and exporting telemetry data. It exposes HTTP and gRPC endpoints for receiving OTLP data and provides a configuration API for managing pipelines, receivers, processors, and exporters at runtime via the zPages diagnostic extension and config file hot-reloading.

**Human URL:** [https://opentelemetry.io/docs/collector/](https://opentelemetry.io/docs/collector/)


#### Tags:

 - Collector, Pipeline, Observability, Configuration

#### Properties

- [Documentation](https://opentelemetry.io/docs/collector/)
- [Reference](https://opentelemetry.io/docs/collector/configuration/)
- [GitHubRepository](https://github.com/open-telemetry/opentelemetry-collector)

### OpenTelemetry SDK API
The OpenTelemetry SDK API specifies language-level interfaces for instrumentation, including the Tracer, Meter, and Logger APIs used by application code to create spans, record metrics, and emit log records. Implementations are available for all major programming languages including Java, Python, Go, JavaScript, .NET, Ruby, and others.

**Human URL:** [https://opentelemetry.io/docs/specs/otel/](https://opentelemetry.io/docs/specs/otel/)


#### Tags:

 - SDK, Instrumentation, Tracing, Metrics, Logging

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
