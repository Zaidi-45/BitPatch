# BitPatch for IGI-2: Covert Strike

[![Version](https://img.shields.io/badge/Release-v1.0%20Latest-brightgreen.svg)](https://github.com/Zaidi-45/BitPatch/releases/latest)
[![Website](https://img.shields.io/badge/Website-reviveigi2.com-blue.svg)](https://reviveigi2.com)
[![Discord](https://img.shields.io/badge/Discord-Bitmasters-7289da.svg)](https://discord.gg/dvwcbGVeyV)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**BitPatch** is the premier, GOG-compliant multiplayer patch and engine wrapper for *Project I.G.I.-2: Covert Strike*. Following the shutdown of GameSpy and Qtracker, BitPatch safely hooks into the game engine via a local `wsock32.dll` to restore in-game server browsing through the active **OpenSpy** master server, while providing essential stability fixes for modern 64-bit operating systems (Windows 10 & Windows 11).

Official Web Portal: [reviveigi2.com](https://reviveigi2.com)

---

## 📥 Download & Installation

[![Download BitPatch](https://img.shields.io/badge/Download-BitPatch%20v1.0%20(.zip)-007bff?style=for-the-badge&logo=github)](https://github.com/Zaidi-45/BitPatch/releases/latest)

1. Download **`BitPatch-v1.0.zip`** from the official [Releases Tab](https://github.com/Zaidi-45/BitPatch/releases/latest).
2. Extract all contents of the `.zip` archive directly into your main IGI-2 game folder (where `igi2.exe` is located).
3. Allow Windows to overwrite existing files when prompted.
4. Launch `igi2.exe` normally and navigate to **Multiplayer** — servers will populate automatically via OpenSpy.

---

## 🎮 Core Features

### 🛡️ Anti-Cheat & Security
- **Exploit Blocking:** Patches known trainer exploits including Invisible Mode, Fast Lockpick, Super Jump, Rapid Fire, Infinite Ammo, and Deviance.
- **Thermal Hack Prevention:** Completely eliminates modified thermal rifle wallhacks.
- **Server Exploit Protection:** Mitigates Luigi Auriemma vulnerabilities (gshboom, format string attacks, fake player floods).

### ⚙️ Anti-Crash & Stability
- **Weapon Limit Fix:** Resolves weapon limits across all maps using an internal FIFO queue architecture.
- **Authentication Fixes:** Resolves persistent CD authentication loops.
- **Desynchronization Fixes:** Patches death animation desyncs, null pointer reads, and ghost entity cascading crashes.
- **Server Stability:** Fixes floating-point triggers and Z-coordinate limits that crash dedicated servers.

### 🎯 Gameplay & Client Enhancements
- **Modern OS Compatibility:** Pre-configured with dgVoodoo 2 wrappers to eliminate DirectDraw resolution crashes and visual artifacts on Windows 10/11.
- **Submerged Firing:** Unlocks the ability to fire weapons while submerged in water.
- **Free-Camera / Third-Person:** Toggleable in-game via `Left Alt + Right Alt`.
- **Beta Voice Lines:** Dedicated radio keybindings mapped to `Alt + T` and `Alt + I`.
- **UI Restoration:** Restores the original animated menu system from *Project I.G.I.*

---

## 🛒 Required Game Version
This patch is fully compatible and heavily optimized for the official [GOG.com release of I.G.I. 2: Covert Strike](https://www.gog.com/en/game/i_g_i_2_covert_strike) as well as original v1.2 retail installations. We recommend a clean, unmodified installation to avoid third-party script conflicts.

---

## 🌐 Community & Dedicated Servers

Looking to host a dedicated server, view live global player leaderboards, or download community map packs?

* **Web Portal:** [reviveigi2.com](https://reviveigi2.com)
* **Forum:** [reviveigi2.com/forum.html](https://reviveigi2.com/forum.html)
* **Discord Server:** [Bitmasters Official Discord](https://discord.gg/dvwcbGVeyV)

---

## ⚖️ License & Legal

This repository configuration is licensed under the **MIT License**.

**Legal Disclaimer:** Project I.G.I.-2: Covert Strike is the registered trademark of its respective copyright holders. BitPatch is an independent community restoration project and is not affiliated with, sponsored by, or endorsed by Innerloop Studios, Codemasters, or GOG. This repository contains no base game executable binaries or proprietary level packages.

**Attribution Requirement:** You are free to utilize and reference this patch for community servers and modding initiatives. However, you **MUST** provide clear, visible credit to **Team Bitmasters** and include a direct link back to [reviveigi2.com](https://reviveigi2.com) or this GitHub repository. Claiming this work as your own is strictly prohibited.

---
*Developed and maintained by Team Bitmasters (2012–2026).*
