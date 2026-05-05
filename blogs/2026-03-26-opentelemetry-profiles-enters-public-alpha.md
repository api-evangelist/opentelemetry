---
title: "OpenTelemetry Profiles Enters Public Alpha"
url: "https://opentelemetry.io/blog/2026/profiles-alpha/"
date: "Thu, 26 Mar 2026 08:12:06 -0700"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
<p>Since OpenTelemetry first <a href="https://opentelemetry.io/blog/2024/profiling/">introduced</a> Profiles, momentum
has only grown towards building a unified industry standard for continuous
production profiling, standing alongside traces, metrics, and logs. Today, the
Profiling SIG is proud to announce that the Profiles signal has officially
entered
<a class="external-link" href="https://github.com/open-telemetry/opentelemetry-specification/blob/v1.55.0/oteps/0232-maturity-of-otel.md#alpha" rel="noopener" target="_blank">public Alpha</a>,
and we are ready for broader community use and feedback.</p>
<h2 id="production-profiling-for-all">Production profiling for all<a class="td-heading-self-link" href="#production-profiling-for-all"></a></h2>
<p>Continuously capturing low-overhead performance profiles in production is a
technique that
<a class="external-link" href="https://www.waldspurger.org/carl/papers/dcpi-sosp97.pdf" rel="noopener" target="_blank">has been used for decades</a>.
It helps troubleshoot production incidents, improves user experience by making
software faster and reduces computation costs by making the same work take less
resources. Historically, the industry lacked a common framework and protocol for
continuous profiling, even with formats like JFR and pprof being popular.</p>
