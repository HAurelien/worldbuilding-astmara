---
type: "organization"
aliases: []
world:
  - "[[Aethernam]]"
  - "[[Zephyrion]]"
calendar: "aethernam"
org_type: "Religious, Pantheon"
founded: 947
headquarters: "[[Ether]]"
leaders:
  - "[[God of Progress]]"
founders:
  - "[[God of Humankind]]"
  - "[[God of Progress]]"
parent_org: "[[Higher gods]]"
ruling_organization: "[[Higher gods]]"
government_system: "Anarchy"
controlled_territories:
  - "[[Ether]]"
related_species:
  - "[[Ether mirror]]"
  - "[[Human]]"
status: "canon"
tags: []
wa_id: "32d926a1-db40-43e2-8de2-f26a3c0345cd"
---

This is not really an organization, it is just a way to group all the lower gods. They rule only over a few worlds, whereas the [[Higher gods]] rule over the whole universe.

### History

### Apparition

 
All dates are given following the [[Aethernam]] timeline
 
[[God of Humankind]] -> First to appear from Absalom the First around 0
[[God of Progress]] -> Second to appear around 783
[[God of Eldritch creatures]] -> Third to appear around 1612
[[God of Lycanthrope]] -> Appeared around 1834
[[God of Justice]] -> Appeared around 2485
[[God of Death]] -> Appeared around 2793
[[God of War]] -> Appeared around 2954
[[Goddess of Hope]] -> Appeared around 1738

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
