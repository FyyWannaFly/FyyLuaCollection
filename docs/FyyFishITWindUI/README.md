# FyyFishITWindUI.lua

> Main WindUI release script for Fish IT, built around Fyy Community styling, config persistence, and broad automation panels.

<p align="left">
  <img alt="script" src="https://img.shields.io/badge/script-Fish%20IT-0E9F6E">
  <img alt="ui" src="https://img.shields.io/badge/ui-WindUI-6D4CFF">
  <img alt="status" src="https://img.shields.io/badge/status-Main%20Release-1177AA">
</p>

## Overview

`scripts/FyyFishITWindUI.lua` is the largest Fyy-branded Fish IT script in this repo. It creates the `Fyy X Fish IT` WindUI window, applies an AMOLED-style theme, manages local config files, and exposes Fish IT automation through a multi-tab interface.

## Feature Areas

| Area | Features |
|---|---|
| Player | WalkSpeed, Infinite Jump, NoClip, utility movement helpers, quality-of-life toggles |
| Fishing | instant fishing modes, automation flows, radar/oxygen helpers, selected workflow toggles |
| Inventory | auto-sell, auto-favorite, item/rod-oriented helpers |
| Shop | purchase helpers and shop-related automation |
| Teleport | location navigation and shortcut controls |
| Event / Quest | event-specific helpers, quest/totem/enchant related panels |
| Webhook | user-configurable notification/reporting controls |
| Config | save/load/autoload user settings through local config files |

## Runtime Model

```text
load UI library
  -> create WindUI window
  -> apply theme
  -> register config objects
  -> create tabs
  -> attach callbacks to Roblox services/remotes
```

## Local Data

The script uses a local config folder pattern for saved settings:

```text
FyyCommunityConfig/
FyyConfig/
```

Do not commit generated config files unless intentionally publishing presets.

## Privacy Notes

Private library URLs, webhook URLs, and service endpoints are intentionally omitted from this documentation. Use placeholders in public examples.

