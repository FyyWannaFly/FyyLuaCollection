# ClientAbyss.lua

> Alternate Abyss client variant with a Lexs-style UI and selected-fish automation workflow.

<p align="left">
  <img alt="script" src="https://img.shields.io/badge/script-Abyss%20IT-0E9F6E">
  <img alt="ui" src="https://img.shields.io/badge/ui-Lexs--style-06B6D4">
  <img alt="status" src="https://img.shields.io/badge/status-Client%20Variant-1177AA">
</p>

## Overview

`scripts/ClientAbyss.lua` is a smaller Abyss client variant. It creates a premium-style window, builds an Abyss config folder, scans replicated fish assets, and exposes selected-fish automation plus supporting utility controls.

## Feature Areas

| Area | Features |
|---|---|
| UI | premium-style Abyss window and tab layout |
| Config | local `LexsHub/Abyss` config folder setup |
| Fish Selection | replicated fish asset scanning and selectable fish list creation |
| Automation | selected-fish automation state, catch/tween controls, auto-sell state |
| Utility | oxygen and teleport-oriented helper state |

## Runtime Model

```text
load Lexs-style UI
  -> create Abyss window
  -> scan replicated fish assets
  -> build selection controls
  -> run Abyss automation callbacks
```

## Best Use Case

Use this for a focused Abyss client implementation with a smaller footprint than the full Fish IT client.

## Privacy Notes

Keep UI source URLs and community invite details private unless they are intentionally public.

