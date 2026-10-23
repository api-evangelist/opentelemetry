---
title: "Versioned metrics: Shipping the first Release Candidate metrics in hostmetrics"
url: "https://opentelemetry.io/blog/2026/hostmetrics-process-scraper-rc/"
date: "2026-10-13"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
OpenTelemetry Collector Contrib v0.160.0 adds the ability to emit release candidate (RC) process semantic conventions metrics to the hostmetrics receiver’s process scraper, the last stage before a stable v1. The System SIG has worked on this for the better part of a year, and we think that the process metrics are in a good shape – but RC exists so the community can prove that. If you collect process metrics, we’d like you to try the new versioned output and tell us what breaks.
