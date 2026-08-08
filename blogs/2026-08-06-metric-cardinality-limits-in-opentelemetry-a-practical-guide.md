---
title: "Metric cardinality limits in OpenTelemetry: a practical guide"
url: "https://opentelemetry.io/blog/2026/cardinality-limits-in-opentelemetry/"
date: "2026-08-06"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
OpenTelemetry metrics are designed to be safe to use in production. One part of that safety is the cardinality limit in the metrics SDK. The limit protects your process from unbounded memory growth when a metric receives too many unique attribute combinations.
