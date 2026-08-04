---
title: "Announcing v1 of OpenTelemetry Go Compile-Time Instrumentation"
url: "https://opentelemetry.io/blog/2026/go-compile-time-instrumentation-v1/"
date: "2026-07-16"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
If you write Java, Python, Node.js, or .NET, you have been able to add OpenTelemetry to an application without editing its code for years: attach an agent at startup and telemetry starts flowing. Go has been the exception. A Go program compiles to a single static binary with no runtime to hook into at startup, so Go developers have had to instrument by hand or reach for an out-of-process eBPF agent.
