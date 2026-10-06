---
type: "god"
aliases: []
world:
  - "[[Aethernam]]"
  - "[[Zephyrion]]"
species: "[[Ether mirror]]"
calendar: "aethernam"
place_of_death: "[[Ether|The Ether]]"
status: "draft"
tags: []
wa_id: "728ce512-7953-4146-b5fa-59ff4cf47347"
---

He is Absalom the First, the first [[Human]] to ascend to be a God. He had troubles to use magic in the begining, as he was the first of them all. After the events of The Great Transition, he succeded to stabilise the world for a time, until the [[God of Progress]] ascended too. His obsessions ended up breaking the world apart, and from there, other Gods begun to rise. A few century later, he gradually felt in disbelief about humanity's evilness, and disappeared from the scenery. He was the first to be absorbed by [[Arrack]] shortly before the Great Cataclysm.

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
