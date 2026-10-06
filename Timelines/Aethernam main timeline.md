---
type: "timeline"
aliases: []
planet:
  - "[[Aethernam]]"
calendar: "aethernam"
status: "draft"
tags: []
wa_id: "a7ed06c5-3b7f-4076-b1b2-f5c2c1c1758c"
---

This is the global timeline of Aethernam. It only contains events directly related to major changes in the world.

## Eras

### The dark age

*... 1 PME*

This is an Era with lots of new technologies, but also a lot of destruction, war and suffering. No much have been found from this period as little could write and most of the knowledge have been burned through history.

### The true peace

*0 PME → 800*

This is an Era protected by the [[God of Humankind]]. During this Era, the world got reconstructed, war completely stopped all over the world, and technology begun to go forward..

### The breakthrough

*801 → 1500*

This is an era in which the technological knowledge increased a lot in all fields. From the mastering of iron to the windmill, the world got pushed forward by the new [[God of Progress]]. However, all those technologies and new ressources to exploit divided the world once again.

### The troubled age

*1501 → 2757*

Technologies had increasingly developed since the precedent age, and a new discovery was made : magic. This new power, mastered at first by a few newly discovered creatures, have been imbued into a very few objects. These objects were so powerful entire cities and countries were burned down for them.
A few volcanoes were active in the early days of this period.

### The end

*2758 and beyond*

This is an era of death, suffering and sacrifice, in which only a few manage to survive

[[Arrack]]

, the World Eater 's curse.

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
