---
layout: default
tags: error
service: troubleshooting
title: Step Not In History
---
# Step Not In History

A reset-and-respond targeted a step that is not present in the session's history,
so there is nothing to rewind to.

```yaml
{
    "type": "https://api.dezide.dev/problem/troubleshooting/step-not-in-history",
    "title": "Step Not In History",
    "status": 422,
    "detail": "Step (step-42) is not in history"
}
```
