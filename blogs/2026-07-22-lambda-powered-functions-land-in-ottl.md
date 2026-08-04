---
title: "Lambda-powered functions land in OTTL"
url: "https://opentelemetry.io/blog/2026/lambda-powered-function-land-in-ottl/"
date: "2026-07-22"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
As telemetry pipelines become more sophisticated, so do the transformations they need to perform: sanitizing sensitive data, normalizing inconsistent schemas, and enforcing attribute contracts. While OTTL provides a rich set of transformation functions, expressing collection operations has required dedicated functions with hardcoded behavior for each new use case. OpenTelemetry Collector Contrib v0.157.0 changes that by introducing lambda expressions to OTTL.
