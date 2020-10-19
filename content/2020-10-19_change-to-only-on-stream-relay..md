---toml
title = "Degraded stream and chat performance"
date = "2020-10-19T07:35:21.866Z"
severity = "degraded-performance"
affectedsystems = ["stream", "chat"]
resolved = false
---
We are seeing degraded stream quality and chat disconnects.

::: update Investigating | 2020-10-19T09:35:00.000Z
We have deactivated one of the two streaming mirrors.
:::

::: update Monitoring | 2020-10-19T11:00:00.000Z
We doubled the stream capacity by mirroring it which should automatically reduce the strain on the web chat as well.
:::

<!--- language code: en -->
