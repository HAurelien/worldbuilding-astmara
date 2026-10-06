---
type: "organization"
aliases: []
planet:
  - "[[Aethernam]]"
  - "[[Zephyrion]]"
calendar: "aethernam"
org_type: "Secret, Military"
headquarters: "[[Zephyrion]]"
leaders:
  - "[[Angres Rimas]]"
founders:
  - "[[Angres Rimas]]"
capital: "[[Aethernam]]"
alternative_names:
  - "LP"
  - "Lost Protectors"
training_level: "Elite"
veterancy_level: "Veteran"
head_of_state: "[[Atios]]"
head_of_government: "[[Angres Rimas]]"
government_system: "Anarchy"
power_structure: "Transnational government"
deities:
  - "[[God of Death]]"
  - "[[God of Lycanthrope]]"
official_languages:
  - "[[Aethernam common]]"
controlled_territories:
  - "[[Aethernam]]"
related_species:
  - "[[Ether mirror]]"
  - "[[Human]]"
status: "draft"
tags: []
wa_id: "d7b6af98-8dcf-4b0e-8d0e-ff51f8181aa6"
---

This is the group of people knowing about both Aethernam and Zephyrion who sworn to keep Arrack from destroying anything anymore.

### History

This is an association created after the Great Cataclysm. They are used by Gods to protect them from [[Arrack]], the World Eater as the seal of Amagolon would probably break eventually. For this very reason, they have access to a part of the God's knowledge, harnessing power for the day the fight wouldn't be avoidable.

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
