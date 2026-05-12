# FyyFishITFluent.lua

> Fluent UI variant of the Fyy Fish IT hub, designed as an alternate interface for the same Fish IT automation ecosystem.

<p align="left">
  <img alt="script" src="https://img.shields.io/badge/script-Fish%20IT-0E9F6E">
  <img alt="ui" src="https://img.shields.io/badge/ui-Fluent-38BDF8">
  <img alt="status" src="https://img.shields.io/badge/status-Alternate%20UI-1177AA">
</p>

## Overview

`scripts/FyyFishITFluent.lua` provides a Fluent-based Fish IT experience. It uses Fluent's `SaveManager` and `InterfaceManager`, builds a wide tab layout, and covers player tools, Fish IT automation, shop, teleport, events, enchant, webhook, settings, and config sections.

## Feature Areas

| Area | Features |
|---|---|
| Info | welcome panel, support button, basic script information |
| Player | WalkSpeed, Infinite Jump, NoClip, Walk On Water, oxygen/radar helpers, respawn-position helper |
| Main / Auto | fishing automation and core Fish IT runtime controls |
| Shop | shop-related actions and purchase helpers |
| Teleport | map/location movement shortcuts |
| Totem / Quest / Event | progression and event helper panels |
| Trade / Enchants | trade/enchant oriented controls |
| Webhook | notification/reporting configuration |
| Config | Fluent save/load sections through SaveManager and InterfaceManager |

## Runtime Model

```text
load Fluent library
  -> create Fyy X Fish IT window
  -> build tabs
  -> attach SaveManager and InterfaceManager
  -> run feature callbacks through Roblox services/remotes
```

## Best Use Case

Use this script when Fluent UI is preferred over WindUI or when testing compatibility between UI frameworks.

## Privacy Notes

Do not expose raw library URLs, webhook endpoints, or private service details in public docs.

