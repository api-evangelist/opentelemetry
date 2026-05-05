---
title: "OBI Gives Incident Response the Request Context It Needs"
url: "https://opentelemetry.io/blog/2026/obi-http-header-enrichment/"
date: "Fri, 10 Apr 2026 00:41:53 -0700"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
<p>When incidents are active, traces usually tell you that something is wrong. The
harder problem is figuring out who is affected and why, quickly.</p>
<p><a class="external-link" href="https://github.com/open-telemetry/opentelemetry-ebpf-instrumentation" rel="noopener" target="_blank">OpenTelemetry eBPF Instrumentation (OBI)</a>
<a class="external-link" href="https://github.com/open-telemetry/opentelemetry-ebpf-instrumentation/releases/tag/v0.7.0" rel="noopener" target="_blank">v0.7.0</a>
adds HTTP header enrichment so spans can carry request context like tenant or
user segment. That context is often exactly what helps you move from &ldquo;error rate
is up&rdquo; to &ldquo;this is isolated to one customer cohort&rdquo;.</p>
<p>The best part: this is a config change on OBI itself. You do not need to rebuild
or redeploy your existing applications.</p>
