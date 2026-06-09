---
layout: default
tags: error
title: Constraint Violation
---
# Constraint Violation

The request failed validation. The `violations` array lists each failure with the
`field` — the property path of the offending value — and a human-readable
`message`. Field paths use dotted/bracketed notation for nested objects and
collections (e.g. `address.street`, `items[2].name`).

This deliberately matches the shape produced by the Zalando `problem-spring-web`
library (`violations` of `{field, message}`), so a client written against that
shape works unchanged — only the `type` URI differs. An optional `detail` may
summarise the failure; clients that don't expect it can ignore it.

```yaml
{
    "type": "https://api.dezide.dev/problem/constraint-violation",
    "title": "Constraint Violation",
    "status": 400,
    "detail": "Request validation failed.",
    "violations": [
        { "field": "value", "message": "Field value too long" }
    ]
}
```
