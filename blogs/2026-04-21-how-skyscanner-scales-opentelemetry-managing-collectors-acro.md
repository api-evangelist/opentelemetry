---
title: "How Skyscanner scales OpenTelemetry: managing collectors across 24 production clusters"
url: "https://opentelemetry.io/blog/2026/devex-skyscanner/"
date: "Tue, 21 Apr 2026 09:54:19 +0200"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
<p>The Developer Experience SIG is publishing a series of blog posts featuring
real-world OpenTelemetry deployments from companies across different industries
and scales. This post features <a class="external-link" href="https://www.skyscanner.net/" rel="noopener" target="_blank">Skyscanner</a>, a
global travel search platform based in Edinburgh, Scotland.</p>
<p>With 1,400 employees worldwide running over 1,000 microservices across 24
production Kubernetes clusters, Skyscanner&rsquo;s journey with OpenTelemetry offers
valuable lessons for organizations operating at scale.</p>
<h2 id="organizational-structure">Organizational structure<a class="td-heading-self-link" href="#organizational-structure"></a></h2>
<p>The Hubble team, consisting of six platform engineers, manages most of
Skyscanner&rsquo;s collectors. As part of the wider platform engineering organization,
they handle the compute platform that runs Skyscanner&rsquo;s primarily Java-based
microservices architecture.</p>
