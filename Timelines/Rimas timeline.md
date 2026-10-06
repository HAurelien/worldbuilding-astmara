---
type: "timeline"
aliases: []
world:
  - "[[Aethernam]]"
calendar: "aethernam"
status: "draft"
tags: []
wa_id: "4faa1b15-6fd7-4088-ab85-216d7a48f5ce"
---

This is the timeline of [[Angres Rimas]], one of the most important character of the two first developped worlds of [[Zephyrion]] and [[Aethernam]].

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
      - date
      - era
      - event_type
    sort:
      - property: year
        direction: ASC
```
