---
title: "Help us stabilize environment variable context propagation"
url: "https://opentelemetry.io/blog/2026/environment-variable-context-propagation/"
date: "2026-09-11"
feed_url: "https://opentelemetry.io/blog/index.xml"
---
A trace does not always cross a network boundary. A workflow runner starts a shell, the shell launches a build tool, and the build tool starts test processes. Batch and data-processing systems create similar chains of child processes.
