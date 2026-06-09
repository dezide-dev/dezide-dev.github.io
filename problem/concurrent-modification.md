---
layout: default
tags: error
title: Concurrent Modification
---
# Concurrent Modification

A concurrent change won an update race, so the request was not applied. This is
**retryable**: reload the resource and try again.

```yaml
{
    "type": "https://api.dezide.dev/problem/concurrent-modification",
    "title": "Concurrent Modification",
    "status": 409,
    "detail": "A concurrent change won the update race; reload and retry."
}
```
