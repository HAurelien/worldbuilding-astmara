---
type: "species"
aliases: []
world: []
related_organizations:
  - "[[Lone Protectors]]"
  - "[[Lower gods]]"
status: "draft"
tags: []
wa_id: "f1818472-1214-4376-9b3d-4361c3cb622e"
---

Every (or almost) of these entities are living in [[Ether|The Ether]].
They end up disappearing too, after a few month, once the living entity connected to them die. But, if enough persons are connected to them, if enough person praise the dead, the entity keeps on. It might end up capable of consuming a bit of the power of the others to keep itself together. This is the way the gods got created. Enough people trust their words when they were alive, and they ended up thanking or rewarding people who did so. And so their myth turned into a religion.

## Basic Information

### Genetics and Reproduction

These entities only appears when a new living being with enough intellectual capacities is born.

### Ecology and Habitats

[[Ether|The Ether]].

### Biological Cycle

They end up disappearing when, after a few month, once the living entity connected to them die. But, if enough persons are connected to them, if enough person praise the dead, the entity keeps on. It might end up capable of consuming a bit of the power of the others to keep itself together. This is the way the gods got created. Enough people trust their words when they were alive, and they ended up thanking or rewarding people who did so. And so their myth turned into a religion. Gaining power from more and more people, they keep their religion alive.

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
