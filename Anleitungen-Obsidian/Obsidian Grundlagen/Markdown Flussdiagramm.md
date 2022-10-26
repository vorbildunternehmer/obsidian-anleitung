---
tags: tutorial, markdown, diagramm
---

Flussdiagramm
===

```mermaid
flowchart TD

f[Familie]
a[Anne]
j[Jens]
i[Ina]
n[Nora]

f --> Eltern
f --> Kinder

Eltern -.- a
Eltern -.- j

Kinder -.1. Tochter.- i
Kinder -.2. Tochter.- n

n --> Kindergarten
i --> Schule

i ---> e[Isst gerne Süßes]
n ===> e
```