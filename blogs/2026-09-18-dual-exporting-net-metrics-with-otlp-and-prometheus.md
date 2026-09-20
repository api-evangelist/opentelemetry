---
title: "Dual-exporting .NET metrics with OTLP and Prometheus"
url: "https://opentelemetry.io/blog/2026/dual-dotnet-metrics-export-with-otlp-and-prometheus/"
date: "2026-09-18"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
Many applications export their metrics directly to Prometheus . If you’re unfamiliar with Prometheus, in a nutshell it’s a time-series database for storing metrics, like counters and histograms. Applications that store their metrics in Prometheus typically use a popular Prometheus client as part of the integration.
