---
title: Deluge
description: Deluge Widget Configuration
layout: ../../../layouts/MainLayout.astro
---

Uses the same username and password used to login from the web.

If you are using the linuxserver.io image, please see https://docs.linuxserver.io/images/docker-deluge on how to configure the username and password via environment variables.  The default username is admin.

There are additional authentication options outlined in Deluge's docs here, https://dev.deluge-torrent.org/wiki/UserGuide/Authentication.

Allowed fields: `["leech", "download", "seed", "upload"]`.

```yaml
widget:
    type: deluge
    url: http://deluge.host.or.ip
    username: username
    password: password
```

*Added in v0.5.0*
