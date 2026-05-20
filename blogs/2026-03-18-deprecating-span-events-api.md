---
title: "Deprecating Span Events API"
url: "https://opentelemetry.io/blog/2026/deprecating-span-events/"
date: "Wed, 18 Mar 2026 10:28:12 +0100"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
OpenTelemetry is deprecating the Span Event API. This post explains why we’re making this change, what it means at a high level, and how you can prepare. In short: We want to remove confusion and duplication caused by having two overlapping ways to emit events: span events and log-based events.
