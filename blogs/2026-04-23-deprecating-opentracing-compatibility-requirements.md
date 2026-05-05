---
title: "Deprecating OpenTracing compatibility requirements"
url: "https://opentelemetry.io/blog/2026/deprecating-opentracing-compatibility/"
date: "Thu, 23 Apr 2026 00:54:39 -0700"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
<p>On March 19, 2026, the OpenTelemetry Specification project merged
<a class="external-link" href="https://github.com/open-telemetry/opentelemetry-specification/pull/4938" rel="noopener" target="_blank">PR #4938</a>,
deprecating OpenTracing compatibility requirements in the specification.</p>
<p>This change updates the specification to match where the ecosystem already is:
OpenTracing has been archived for years, and new integrations are expected to
use native OpenTelemetry APIs and SDKs instead of building on OpenTracing shim
requirements.</p>
<p>This is a deprecation of specification requirements, not an immediate removal of
compatibility material and not a requirement to remove existing shim artifacts
right away.</p>
