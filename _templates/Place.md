---
type: place
aliases: []
world: []
place_type: 
parent: 
owner: 
from: 
until: 
calendar: aethernam
status: draft
tags: []
---

## Summary

## Geography

## History

## Notable places

## Events

```base
filters:
  and:
    - '!file.inFolder("_templates")'
    - type == "event"
    - file.hasLink(this.file)
views:
  - type: table
    name: Events
    order:
      - file.name
      - year
      - event_type
      - timelines
    sort:
      - property: year
        direction: ASC
```
