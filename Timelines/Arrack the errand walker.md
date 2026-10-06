---
type: "timeline"
aliases: []
world:
  - "[[Aethernam]]"
calendar: "aethernam"
status: "draft"
tags: []
wa_id: "9c0d636b-c5e7-42e6-8149-3bf974bd00fa"
---

This is the timeline of Arrack, the main enemy of the worlds.

## Eras

### The power seek

*... 2757*

This is an era pretty unknown during which Arrack finally arrived withing the reach of these words in the [[Ether]] as a [[Ether mirror]]

### The harness

*2757 → 2757*

During this period, Arrack slowly gained knowledge on this world, and harnessed the power of people then some minor gods until she got kicked out through a [[Pillar]] by the [[Lower gods|lower gods]].

### The containment

*2758 and beyond*

During this period, Arrack was under control in an amulet, prevented by the [[Lone Protectors]] from getting out.

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
