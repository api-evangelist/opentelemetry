---
title: "The Voyage of a Small Environment Variable"
url: "https://opentelemetry.io/blog/2026/spring-boot-declarative-config/"
date: "2026-07-14"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
The OpenTelemetry Spring Boot starter gained declarative-configuration support starting in version 2.26.0 — the same YAML schema the Java agent introduced in late 2025 , now embedded inside application.yaml . This post traces what one env var, OTEL_SERVICE_NAME=petclinic , does in that new world, and where the seams are. In a hurry?
