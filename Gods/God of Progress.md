---
type: "god"
aliases:
  - "Anzaar"
planet:
  - "[[Aethernam]]"
  - "[[Zephyrion]]"
species: "[[Ether mirror]]"
calendar: "aethernam"
affiliations:
  - "[[Lower gods]]"
divine_classification: "God"
current_location: "[[Ether]]"
conditions:
  - "[[Aura]]"
realm: "[[Ether]]"
status: "draft"
tags: []
wa_id: "e778a943-af95-4601-9471-1bca8e98b04c"
---

**Anzaar**

The god of Progress. Praised by most of the scientific, this god is actively helping his subordinates, as long as they work hard and smart. Appeared around 790.
It's power varied a lot during the major events.
Like the other gods, he got very damaged after The Great Cataclysm.

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
