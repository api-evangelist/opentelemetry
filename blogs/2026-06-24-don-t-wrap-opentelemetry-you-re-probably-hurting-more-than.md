---
title: "Don't Wrap OpenTelemetry — You're Probably Hurting More Than Helping"
url: "https://opentelemetry.io/blog/2026/dont-wrap-opentelemetry/"
date: "2026-06-24"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
There’s a pattern I’ve seen across many teams adopting OpenTelemetry, and it’s well-intentioned every single time. An engineer wants to make things easier for the team. They build a thin abstraction over the OTel API — an IMetric interface, a TelemetryHelper class, a MetricsWrapper module — and ship it as the team’s standard.
