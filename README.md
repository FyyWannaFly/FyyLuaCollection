# FyyCommunity Scripts

> Fyy Community Roblox Luau script collection with polished per-script documentation, privacy-safe release notes, and dedicated docs for Fish IT, Abyss, Garden Horizon, HTTP tooling, and WindUI.

<p align="left">
  <img alt="language" src="https://img.shields.io/badge/language-Luau-00A2FF?logo=lua&logoColor=white">
  <img alt="platform" src="https://img.shields.io/badge/platform-Roblox-000000?logo=roblox&logoColor=white">
  <img alt="ui" src="https://img.shields.io/badge/ui-WindUI%20%2B%20Fluent-6D4CFF">
  <img alt="docs" src="https://img.shields.io/badge/docs-Per%20Script-0E9F6E">
  <img alt="status" src="https://img.shields.io/badge/status-Private%20Toolkit-1177AA">
  <img alt="owner" src="https://img.shields.io/badge/by-FyyWannaFly-5865F2">
</p>

This repository is a curated script hub workspace for Fyy Community. Active Luau scripts live in `scripts/`, the vendored UI library under `lib/` lives in `lib/`, and `docs/` contains one dedicated `README.md` per in-scope file so every script has its own clean feature page.

Sensitive runtime values are intentionally not documented here. Private domains, raw source URLs, webhooks, tokens, database credentials, and backend details should stay out of public README content.

---

## Repo Name Suggestions

Recommended repo name: **`FyyCommunity-Scripts`**

Other good options:

| Name | Why it fits |
|---|---|
| `FyyScriptHub` | Short, clean, and easy to remember. |
| `FyyRobloxTools` | Good if this grows beyond game-specific scripts. |
| `FyyX-Scripts` | Matches the `Fyy X` branding inside the UI windows. |
| `FyyCommunity-Luau` | More technical and language-focused. |

---

## Repository Layout

```text
.
├─ scripts/
│  ├─ FyyAbyss.lua
│  ├─ FyyFishITFluent.lua
│  ├─ FyyFishITWindUI.lua
│  ├─ FyyGardenHorizon.lua
│  ├─ ClientAbyss.lua
│  ├─ ClientFishIT.lua
│  └─ Hook_Https.lua
├─ lib/
│  └─ WindUI.lua
├─ docs/
│  ├─ FyyAbyss/README.md
│  ├─ FyyFishITFluent/README.md
│  ├─ FyyFishITWindUI/README.md
│  ├─ FyyGardenHorizon/README.md
│  ├─ ClientAbyss/README.md
│  ├─ ClientFishIT/README.md
│  ├─ Hook_Https/README.md
│  └─ WindUI/README.md
└─ README.md
```

---

## Script Index

| Script | Target / Role | UI | Dedicated Docs |
|---|---|---|---|
| `scripts/FyyFishITWindUI.lua` | Main Fish IT release | WindUI | [`docs/FyyFishITWindUI`](docs/FyyFishITWindUI/README.md) |
| `scripts/FyyFishITFluent.lua` | Alternate Fish IT release | Fluent | [`docs/FyyFishITFluent`](docs/FyyFishITFluent/README.md) |
| `scripts/FyyAbyss.lua` | Abyss IT release | WindUI | [`docs/FyyAbyss`](docs/FyyAbyss/README.md) |
| `scripts/FyyGardenHorizon.lua` | Garden Horizon release | WindUI | [`docs/FyyGardenHorizon`](docs/FyyGardenHorizon/README.md) |
| `scripts/ClientFishIT.lua` | Alternate Fish IT client | Lexs-style UI | [`docs/ClientFishIT`](docs/ClientFishIT/README.md) |
| `scripts/ClientAbyss.lua` | Alternate Abyss client | Lexs-style UI | [`docs/ClientAbyss`](docs/ClientAbyss/README.md) |
| `scripts/Hook_Https.lua` | HTTP debugging utility | Custom GUI | [`docs/Hook_Https`](docs/Hook_Https/README.md) |
| `lib/WindUI.lua` | Vendored UI library | Library | [`docs/WindUI`](docs/WindUI/README.md) |

---

## Feature Highlights

### Fish IT Scripts

- multiple UI variants for the same Fish IT ecosystem
- player helpers such as WalkSpeed, Infinite Jump, NoClip, and movement utilities
- fishing automation workflows
- shop, teleport, event, quest, totem, enchant, and settings panels
- config persistence and local save/load behavior
- webhook-style notification configuration without exposing private endpoints in docs

### Abyss Scripts

- Abyss-focused client and Fyy-branded implementations
- selected-fish / automation-oriented controls
- local config folder setup
- lighter footprint than the full Fish IT hubs

### Garden Horizon Script

- Garden/farming workflow support
- Fyy WindUI styling
- local config persistence
- player quality-of-life helpers

### Developer Utility

- HTTP monitor for request/response inspection
- compact debugging GUI
- optional local file output for captured logs

### UI Library

- vendored WindUI build
- windows, tabs, themes, controls, notifications, and styling primitives
- used by the WindUI-based Fyy scripts

---

## In Scope vs Out of Scope

In scope:

- active release scripts under `scripts/`
- client variants
- debugging utility
- vendored UI library
- `docs/` documentation pages

Out of scope for public docs:

- `test.lua`
- `oldfishit.lua`
- backend folders
- generated logs/config files
- `.env` files
- private endpoints and credentials

---

## Runtime Requirements

These scripts are designed for Roblox Luau environments that expose common APIs such as:

- `loadstring`
- `game:HttpGet`
- `writefile`
- `readfile`
- `isfile`
- `isfolder`
- `makefolder`
- `delfile`
- `listfiles`
- `setclipboard`

Common Roblox services used across the scripts include:

- `Players`
- `RunService`
- `HttpService`
- `UserInputService`
- `ReplicatedStorage`
- `TeleportService`
- `Lighting`
- `Workspace`

---

## Privacy Rules

Do not publish private runtime values in README files.

Avoid exposing:

- backend domains
- raw script-hosting URLs
- webhook URLs
- bot tokens
- database connection strings
- owner/admin IDs
- `.env` values
- private key/license service details

Use placeholders instead:

```lua
loadstring(game:HttpGet("<your-release-url>"))()
```

```text
<private-backend-endpoint>
<private-webhook-url>
<private-discord-bot-token>
```

---

## Maintenance Notes

- Keep one dedicated docs folder per active script.
- Keep the root README as an index, not a giant feature dump.
- Document new scripts under `docs/<ScriptName>/README.md`.
- Keep legacy/test/backend files ignored unless they are sanitized.
- Review all docs for private URLs before committing or pushing.

