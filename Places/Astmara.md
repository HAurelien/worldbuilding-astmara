---
type: "place"
aliases: []
planet: []
place_type: "World"
status: "draft"
tags: []
---

Astmara is the world. Its planets include [[Aethernam]] and [[Zephyrion]].

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
