<div align="center">

# 🎣 FyyLuaCollection 🎣

### **Curated Roblox Luau Script Hub by Fyy Community**

*Per-script documentation · Encrypted release builds · WindUI & Fluent interfaces*

<br />

<p>
  <img src="https://img.shields.io/badge/Language-Luau-00A2FF?style=for-the-badge&logo=lua&logoColor=white" alt="Luau" />
  <img src="https://img.shields.io/badge/Platform-Roblox-000000?style=for-the-badge&logo=roblox&logoColor=white" alt="Roblox" />
  <img src="https://img.shields.io/badge/UI-WindUI_%2B_Fluent-6D4CFF?style=for-the-badge" alt="UI" />
</p>

<p>
  <img src="https://img.shields.io/badge/Docs-Per_Script-0E9F6E?style=flat-square" alt="Docs" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/By-FyyWannaFly-5865F2?style=flat-square" alt="Owner" />
  <img src="https://img.shields.io/badge/License-ISC-green?style=flat-square" alt="License" />
</p>

<br />

**[Fyy Community Discord](https://discord.gg/77nEeYeFRp)** · **[Report Issue](../../issues)** · **[Request Feature](../../issues)**

</div>

---

## Overview

`FyyLuaCollection` is a curated script hub for the **Fyy Community** — a collection of encrypted, production-ready Roblox Luau scripts with dedicated documentation per tool. Every script ships with its own feature page under `docs/`, so users know exactly what they are running before they load it.

Built for anglers, climbers, and gardeners across Roblox's biggest fishing and survival games.

---

## Script Catalog

| Script | Target Game | UI | Docs |
| :--- | :--- | :--- | :--- |
| **Fyy Fish IT — Fluent** | Fish IT | Fluent | [docs/FyyFishITFluent](docs/FyyFishITFluent/README.md) |
| **Fyy Fish IT — WindUI** | Fish IT | WindUI | [docs/FyyFishITWindUI](docs/FyyFishITWindUI/README.md) |
| **Client Fish IT** | Fish IT | WindUI | [docs/ClientFishIT](docs/ClientFishIT/README.md) |
| **Fyy Abyss** | Abyss | WindUI | [docs/FyyAbyss](docs/FyyAbyss/README.md) |
| **Client Abyss** | Abyss | WindUI | [docs/ClientAbyss](docs/ClientAbyss/README.md) |
| **Fyy Garden Horizon** | Garden Horizon | WindUI | [docs/FyyGardenHorizon](docs/FyyGardenHorizon/README.md) |
| **Hook HTTPS** | Utility | — | [docs/Hook_Https](docs/Hook_Https/README.md) |
| **WindUI Library** | All scripts | — | [docs/WindUI](docs/WindUI/README.md) |

---

## Repository Layout

```
FyyLuaCollection/
│
├── scripts/                    # Production-ready encrypted scripts (.ENC.lua)
│   ├── FyyFishITFluentENC.lua
│   ├── FyyFishITWindUIENC.lua
│   ├── ClientFishITENC.lua
│   ├── FyyAbyssENC.lua
│   ├── ClientAbyssENC.lua
│   ├── FyyGardenHorizonENC.lua
│   └── Hook_HttpsENC.lua
│
├── lib/                        # Vendored UI libraries
│   └── WindUI.lua
│
├── docs/                       # Per-script feature documentation
│   ├── FyyFishITFluent/
│   ├── FyyFishITWindUI/
│   ├── ClientFishIT/
│   ├── FyyAbyss/
│   ├── ClientAbyss/
│   ├── FyyGardenHorizon/
│   ├── Hook_Https/
│   └── WindUI/
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## Usage

Each script has its own loadstring documented in its respective `docs/*/README.md`. Example pattern:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/FyyWannaFly/FyyLuaCollection/main/scripts/FyyFishITFluentENC.lua"))()
```

Refer to the per-script documentation for:

- Full feature list
- UI screenshots
- Configuration options
- Known limitations
- Compatibility notes

---

## Security & Privacy

> [!NOTE]
> This repository intentionally **excludes** sensitive runtime values:
> - Private domain names and API backends
> - Webhooks, tokens, and database credentials
> - Raw unencrypted source code
>
> All scripts in `scripts/` are **`.ENC.lua`** — encrypted release builds. The raw sources remain private.

---

## What Ships Here

- **`scripts/*.ENC.lua`** — Production encrypted builds ready to loadstring
- **`lib/WindUI.lua`** — Vendored UI library used across multiple scripts
- **`docs/*/README.md`** — One feature page per script, updated per release

## What Does Not Ship

- Raw unencrypted Luau sources
- Backend API URLs, domains, webhooks
- Authentication keys or tokens
- Development/testing-only scripts

---

## Community

| Resource | Link |
| :--- | :--- |
| Discord Server | [discord.gg/77nEeYeFRp](https://discord.gg/77nEeYeFRp) |
| Issue Tracker | [GitHub Issues](../../issues) |
| Creator | [@FyyWannaFly](https://github.com/FyyWannaFly) |

---

## License

Distributed under the **ISC License**. See [LICENSE](LICENSE) for details.

Scripts in this repository are provided as-is for community use. The authors are not responsible for any consequences resulting from their use.

---

<div align="center">

**Fyy Community** — *Lets Fly High!*

Made with 💜 for the Roblox scripting community

</div>
