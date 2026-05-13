---
dg-publish: true
title: NPCs
draft: false
tags:
  -
---
 
```base
views:
  - type: table
    name: NPC Overview
    filters:
      and:
        - file.inFolder("NPCs")
    order:
      - file.name
      - First Met
      - Race
      - Last seen?
      - Dead?
      - First Mentioned
      - Lives
      - Met in
    columnSize:
      note.Race: 148

```
