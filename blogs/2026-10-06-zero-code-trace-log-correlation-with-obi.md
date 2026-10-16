---
title: "Zero-code trace-log correlation with OBI"
url: "https://opentelemetry.io/blog/2026/obi-trace-log-correlation/"
date: "2026-10-06"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
You get paged. A trace shows a request failing in one of your services, and you know the answer is in the logs — but which log lines belong to that request? If the service never adopted structured logging with trace context, the honest answer is: you grep by timestamp and hope.
