---
layout: slide
title: "Docker Images"
---

### Images are built in layers

```
┌─────────────────────────┐
│     Your Application    │  ← Your code
├─────────────────────────┤
│     Dependencies        │  ← npm, pip packages
├─────────────────────────┤
│     Runtime             │  ← Node, Python, Java
├─────────────────────────┤
│     Base OS             │  ← Ubuntu, Alpine
└─────────────────────────┘
```

Each layer is cached and reusable!
