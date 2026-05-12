# FyyAbyss.lua

> Fyy Community Abyss IT script using the shared WindUI style and config workflow.

<p align="left">
  <img alt="script" src="https://img.shields.io/badge/script-Abyss%20IT-0E9F6E">
  <img alt="ui" src="https://img.shields.io/badge/ui-WindUI-6D4CFF">
  <img alt="status" src="https://img.shields.io/badge/status-Focused%20Release-1177AA">
</p>

## Overview

`scripts/FyyAbyss.lua` is the Fyy-branded Abyss script. It follows the same structure as the other WindUI releases: load UI, create a themed window, register config objects, and expose Abyss-specific helper controls.

## Feature Areas

| Area | Features |
|---|---|
| UI | `Fyy X Abyss IT` window, AMOLED theme, mobile-friendly open button |
| Config | save/load/autoload config helpers under Fyy config folders |
| Player | utility controls and game-specific helpers |
| Abyss Automation | Abyss-focused automation panels and selected workflow controls |
| Notifications | WindUI notifications for config and runtime feedback |

## Runtime Model

```text
WindUI bootstrap
  -> create Abyss window
  -> initialize config folder
  -> register feature controls
  -> run Abyss callbacks
```

## Best Use Case

Use this as the focused Abyss release script when the full Fish IT hub is unnecessary.

## Privacy Notes

Remote UI library details are private and intentionally documented only as a runtime dependency.

