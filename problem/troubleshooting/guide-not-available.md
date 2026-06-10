---
layout: default
tags: error
service: troubleshooting
title: Guide Not Available
---
# Guide Not Available

The guide backing the session was withdrawn while the session was in flight, so
the session can no longer proceed (for example when starting it, or while it is
active).

```yaml
{
    "type": "https://api.dezide.dev/problem/troubleshooting/guide-not-available",
    "title": "Guide Not Available",
    "status": 422,
    "detail": "Guide is no longer available"
}
```
