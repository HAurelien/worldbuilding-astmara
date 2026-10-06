---
type: "god"
aliases: []
world:
  - "[[Aethernam]]"
  - "[[Zephyrion]]"
species: "[[Ether mirror]]"
calendar: "aethernam"
affiliations:
  - "[[Lower gods]]"
realm: "[[Ether]]"
status: "draft"
tags: []
wa_id: "9616c5d0-835c-4de1-87d5-ae5ac74e72a1"
---

He is the God protecting and creating most of the unique and uncanny creatures of the world. He is very eccentric in his creation, even if he is a former well-known biologist, trying to imbue magic within living creatures to make the most unstable and unpredictable things appear. Even if he is not that powerful, his knowledge about the magical proprieties of the world makes of him a very powerful and dangerous enemy. As such, he is feared as much as the most capable Lower Gods. This is why [[Arrack]] , during the Great Cataclysm, made sure not to hurt any of his creations. He is neutral to her, as he doesn't fiddle with the fate of Humankind, nor the one of the other Gods.

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
