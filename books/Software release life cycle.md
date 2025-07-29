# Software release life cycle

```mermaid
---
title: Stages of development
---
stateDiagram
    pa : Pre-alpha
    rc : Release candidate
    eol : End-of-life
    [*] --> pa
    pa --> Alpha
    Alpha --> Beta
    Beta --> rc
    rc --> Release
    Release --> eol
```