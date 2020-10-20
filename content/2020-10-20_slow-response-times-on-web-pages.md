---toml
title = "Slow response times on web pages"
date = "2020-10-20T07:05:07.631Z"
severity = "degraded-performance"
affectedsystems = ["webpage", "matrix", "kurse"]
modified = "2020-10-20T21:14:25.138Z"
resolved = true
---
We are seeing slow response times for all web services hosted on our main server. We are investigating the issue.

So far, we are suspecting the problem to be within the Apache web server, as both CPU/RAM and network load are looking good.

::: update Monitoring | 2020-10-20T07:49:08.000Z
We increased the number of workers that handle incoming requests and will monitor the situation.
:::

<!--- language code: en -->
