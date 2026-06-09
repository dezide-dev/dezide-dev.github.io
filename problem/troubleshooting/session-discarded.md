---
layout: default
tags: error
service: troubleshooting
title: Session Discarded
---
# Session Discarded

The operation targeted a guide session that has been discarded. A discarded
session is terminal and accepts no further changes (for example re-discarding it,
or adding, updating, or removing a field after discard).

```yaml
{
    "type": "https://api.dezide.dev/problem/troubleshooting/session-discarded",
    "title": "Session Discarded",
    "status": 409,
    "detail": "Session is discarded"
}
```
