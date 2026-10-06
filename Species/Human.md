---
type: "species"
aliases: []
planet: []
related_organizations:
  - "[[Lone Protectors]]"
  - "[[Lower gods]]"
status: "draft"
tags: []
wa_id: "9e0b8cd2-9669-4c58-9a4b-57b21a4ae72a"
---



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
