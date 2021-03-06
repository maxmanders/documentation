---
title: Synthetics Metrics
kind: documentation
description: These metrics are generated by Synthetics checks.
---

## Metrics

The following metrics are generated by Synthetics tests:

* Metrics starting with `synthetics.browser.*` come from your [browser tests][1].
* Metrics starting with `synthetics.http.*` come from your [API HTTP tests][2].
* Metrics starting with `synthetics.ssl.*` come from your [API SSL tests][3].

{{< get-metrics-from-git "synthetics" >}}

[1]: /synthetics/browser_tests/
[2]: /synthetics/api_tests/?tab=httptest
[3]: /synthetics/api_tests/?tab=ssltest
