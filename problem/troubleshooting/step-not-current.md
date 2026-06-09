---
layout: default
tags: error
service: troubleshooting
title: Step Not Current
---
# Step Not Current

The response was submitted for a step that is not the session's current step.
Answer the current recommendation step, or use reset-and-respond to revisit an
earlier one.

```yaml
{
    "type": "https://api.dezide.dev/problem/troubleshooting/step-not-current",
    "title": "Step Not Current",
    "status": 422,
    "detail": "Step (step-42) is not current step"
}
```
