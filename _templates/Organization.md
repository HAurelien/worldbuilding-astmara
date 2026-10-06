---
type: organization
aliases: []
world: []
org_type: 
founded: 
dissolved: 
calendar: aethernam
headquarters: 
leaders: []
founders: []
parent_org: 
status: draft
tags: []
---

## Summary

## Purpose

## Structure

## History

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
