# ClientFishIT.lua

> Alternate Fish IT client variant using a Lexs-style UI layout and a broad multi-tab feature set.

<p align="left">
  <img alt="script" src="https://img.shields.io/badge/script-Fish%20IT-0E9F6E">
  <img alt="ui" src="https://img.shields.io/badge/ui-Lexs--style-06B6D4">
  <img alt="status" src="https://img.shields.io/badge/status-Client%20Variant-1177AA">
</p>

## Overview

`scripts/ClientFishIT.lua` is a Fish IT client implementation separate from the Fyy WindUI/Fluent releases. It builds a premium-style window and organizes a large feature set across player, fishing, shop, teleport, event, trade, enchant, totem, quest, settings, and webhook tabs.

## Feature Areas

| Area | Features |
|---|---|
| Info | support/community panel and basic window metadata |
| Player | Infinite Jump, NoClip, freeze/position utilities, movement helpers |
| Main / Auto | Fish IT automation and fishing workflow controls |
| Shop | shop helpers and purchase-related controls |
| Teleport | location and movement shortcuts |
| Event / Trade / Enchant | game-specific helper panels |
| Totem / Quest | progression-oriented helper controls |
| Settings / Webhook | runtime settings and notification/reporting controls |

## Runtime Model

```text
load Lexs-style UI
  -> create client window
  -> build feature tabs
  -> attach callbacks to Roblox services/remotes
```

## Best Use Case

Use this as an alternate client path when the Lexs-style UI is preferred or when comparing feature parity against the Fyy-branded Fish IT scripts.

## Privacy Notes

Webhook and external source URLs should stay out of public docs.

