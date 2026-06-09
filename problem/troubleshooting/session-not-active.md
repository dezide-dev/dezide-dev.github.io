---
layout: default
tags: error
service: troubleshooting
title: Session Not Active
---
# Session Not Active

The operation requires an `ACTIVE` guide session, but the session is not active
(for example it has not been started yet, or has been discarded). Responding,
evaluating, and reset-and-respond all require an active session.

```yaml
{
    "type": "https://api.dezide.dev/problem/troubleshooting/session-not-active",
    "title": "Session Not Active",
    "status": 422,
    "detail": "Session not active"
}
```
