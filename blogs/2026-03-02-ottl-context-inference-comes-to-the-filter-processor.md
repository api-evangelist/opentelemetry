---
title: "OTTL context inference comes to the Filter Processor"
url: "https://opentelemetry.io/blog/2026/ottl-context-inference-come-to-filterprocessor/"
date: "Mon, 02 Mar 2026 13:04:59 +0000"
author: ""
feed_url: "https://opentelemetry.io/blog/index.xml"
---
Last year, the OpenTelemetry project introduced OTTL context inference for the transform processor . The goal was to allow users to write OTTL statements without worrying about internal telemetry contexts. Starting with collector-contrib v0.146.0 , context inference is available in the Filter Processor through four new top-level config fields: trace_conditions , metric_conditions , log_conditions , and profile_conditions .
