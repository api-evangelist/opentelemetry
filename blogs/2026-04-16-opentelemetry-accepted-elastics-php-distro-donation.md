---
title: "OpenTelemetry Accepted Elastic's PHP Distro Donation"
url: "https://opentelemetry.io/blog/2026/otel-php-distro-donation-update/"
date: "Thu, 16 Apr 2026 08:49:17 -0700"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
<p>The OpenTelemetry community accepted the donation of the OpenTelemetry PHP
Distro project. This post summarizes what the donation enables, how it relates
to existing PHP instrumentation paths, and where contributors can help next.</p>
<h2 id="why-this-donation-matters">Why this donation matters<a class="td-heading-self-link" href="#why-this-donation-matters"></a></h2>
<p>OpenTelemetry provides a common observability standard, but OpenTelemetry PHP
adoption can still be difficult in environments where installing or compiling
native extensions is restricted. Common blockers include:</p>
<ul>
<li>Restricted or hardened systems where native extensions cannot be built during
deployment.</li>
<li>Runtime images that are not rebuilt frequently.</li>
<li>Operational workflows that rely on OS package managers.</li>
</ul>
<p>The PHP Distro addresses these constraints by focusing on an operations-first
installation model.</p>
