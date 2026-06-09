---
layout: default
tags: error
service: troubleshooting
title: Session Already Started
---
# Session Already Started

A guide session was started, but it is not in the `DRAFT` state (it has already
been started, or has been discarded).

```yaml
{
    "type": "https://api.dezide.dev/problem/troubleshooting/session-already-started",
    "title": "Session Already Started",
    "status": 409,
    "detail": "Already started"
}
```
