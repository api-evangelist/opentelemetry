---
title: "Inside Adobe's OpenTelemetry pipeline: simplicity at scale"
url: "https://opentelemetry.io/blog/2026/devex-adobe/"
date: "Wed, 08 Apr 2026 16:29:48 +0200"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
<p>As part of an ongoing series, the Developer Experience SIG interviews
organizations about their real-world OpenTelemetry Collector deployments to
share practical lessons with the broader community. This post features Adobe, a
global software company whose observability team has built an
OpenTelemetry-based telemetry pipeline designed for simplicity at massive scale,
with thousands of collectors running per signal type across the company&rsquo;s
infrastructure.</p>
<h2 id="organizational-structure">Organizational structure<a class="td-heading-self-link" href="#organizational-structure"></a></h2>
<p>Adobe&rsquo;s central observability team is responsible for providing observability
infrastructure across the company. However, as
<a class="external-link" href="https://github.com/bogdan-st" rel="noopener" target="_blank">Bogdan Stancu</a>, Senior Software Engineer,
explained, Adobe&rsquo;s history of acquisitions means the landscape is not fully
consolidated. Some large product groups have their own dedicated observability
teams, while the central team serves as the primary provider.</p>
