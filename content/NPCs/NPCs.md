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
        - file.inFolder("quartz/content/NPCs")
    order:
      - file.name
      - Last seen?
      - First Met
      - Race
      - Dead?
      - First Mentioned
      - Lives
      - Met in
    sort: []
    columnSize:
      note.Race: 148
      note.First Mentioned: 136
      note.Lives: 231

```
