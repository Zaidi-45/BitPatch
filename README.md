# BitPatch for IGI-2: Covert Strike

[![Version](https://img.shields.io/badge/Release-v1.0%20Latest-brightgreen.svg)](https://github.com/Zaidi-45/BitPatch/releases/latest)
[![Website](https://img.shields.io/badge/Website-reviveigi2.com-blue.svg)](https://reviveigi2.com)
[![Discord](https://img.shields.io/badge/Discord-Bitmasters-7289da.svg)](https://discord.gg/dvwcbGVeyV)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary%20Freeware-red.svg)](EULA.md)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=40&pause=1800&color=6090EE&center=true&vCenter=true&width=600&height=60&lines=BITMASTERS%E2%84%A2;BACK+TO+NOSTALGIA" alt="Bitmasters Motto" />
</p>

**BitPatch** is the premier, GOG-compliant multiplayer patch and engine wrapper for *Project I.G.I.-2: Covert Strike*. Following the shutdown of GameSpy and Qtracker, BitPatch safely hooks into the game engine via a local `wsock32.dll` to restore in-game server browsing through the active **OpenSpy** master server, while providing essential stability fixes for modern 64-bit operating systems (Windows 10 & Windows 11).

Official Web Portal: [reviveigi2.com](https://reviveigi2.com)

---

## 📥 Download & Installation

[![Download BitPatch](https://img.shields.io/badge/Download-BitPatch%20v1.0%20(.zip)-007bff?style=for-the-badge&logo=github)](https://github.com/Zaidi-45/BitPatch/releases/latest)

1. Download **`BitPatch-v1.0.zip`** from the official [Releases Tab](https://github.com/Zaidi-45/BitPatch/releases/latest).
2. Extract all contents of the `.zip` archive directly into your main IGI-2 game folder (where `igi2.exe` is located).
3. Allow Windows to overwrite existing files when prompted.
4. Launch `igi2.exe` normally, navigate to **Multiplayer**, and servers will populate automatically via the OpenSpy master server.

---

## 🎮 Core Features

### 🛡️ Anti-Cheat & Security
- **Exploit Blocking:** Patches known trainer exploits including Invisible Mode, Fast Lockpick, Super Jump, Rapid Fire, Infinite Ammo, and Deviance.
- **Thermal Hack Prevention:** Completely eliminates modified thermal wallhacks.
- **Server Exploit Protection:** Mitigates Luigi Auriemma vulnerabilities (gshboom, format string attacks, fake player floods).

### ⚙️ Anti-Crash & Stability
- **Weapon Limit Fix:** Resolves weapon limits across all maps using an internal FIFO queue architecture.
- **Desynchronization Fixes:** Patches death animation desyncs, null pointer reads, and ghost entity cascading crashes.
- **Server Stability:** Fixes floating-point triggers and Z-coordinate limits that crash dedicated servers.

### 🎯 Gameplay & Client Enhancements
- **Modern OS Compatibility:** Pre-configured with dgVoodoo 2 wrappers to eliminate DirectDraw resolution crashes and visual artifacts on Windows 10/11.
- **Submerged Firing:** Unlocks the ability to fire weapons while submerged in water.
- **Free-Camera / Third-Person:** Toggleable in-game via `Left Alt + Right Alt`.
- **Beta Voice Lines:** Dedicated radio keybindings mapped to `Alt + T` and `Alt + I`.
- **UI Restoration:** Restores the original animated menu system from *Project I.G.I.*

---

<div align="center">
  <h3>✨ Classic IGI-1 Animated Menu Restoration</h3>
  <p><i>BitPatch natively restores the iconic Project I.G.I. animated interface inside IGI-2: Covert Strike.</i></p>
  <br/>
  <img src="https://github.com/user-attachments/assets/f56f50b4-6aae-49a3-81ed-2d643a7fe31b" alt="IGI-1 Animated Menu Restoration" width="580" style="max-width: 100%; border-radius: 8px;" />
</div>

---



## 🛒 Required Game Version
This patch is fully compatible and heavily optimized for the official [GOG.com release of I.G.I. 2: Covert Strike](https://www.gog.com/en/game/i_g_i_2_covert_strike) as well as original v1.2 retail installations. We recommend a clean, unmodified installation to avoid third-party script conflicts.

---

## 🌐 Community & Dedicated Servers

Looking to host a dedicated server, view live global player leaderboards, or download community map packs?

<p align="center">
  <a href="https://reviveigi2.com" target="_blank">
    <img src="https://img.shields.io/badge/Website-0078D6?style=for-the-badge&logo=internetcomputer&logoColor=white" alt="Website" />
  </a>&nbsp;
  <a href="https://www.moddb.com/mods/igi2-multiplayer-bitpatch" target="_blank">
    <img src="https://img.shields.io/badge/ModDB-B31010?style=for-the-badge&logo=modx&logoColor=white" alt="ModDB" />
  </a>&nbsp;
  <a href="https://www.facebook.com/BitmastersNetwork" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
  </a>&nbsp;
  <a href="https://www.youtube.com/@bitmastersofficial" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</p>

<!-- Followed by your centered Discord card -->

<br />

<div align="center">
  <table>
    <tr>
      <td align="center" width="370">
        <br />
        <a href="https://discord.gg/dvwcbGVeyV">
          <img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6a49cf127bf92de1e2_icon_clyde_blurple_RGB.png" width="68" alt="Discord" />
          <br /><br />
          <b><font size="4">Join the Official Bitmasters Community</font></b>
        </a>
        <br />
        <p>Discord · Matchmaking · Live Support</p>
      </td>
    </tr>
  </table>
</div>

---

## ⚖️ License & Legal

BitPatch binaries and configurations are proprietary freeware distributed under the terms of the [BitPatch End User License Agreement (EULA)](EULA.md).

> **Note on Source Code:** BitPatch is closed source to protect the integrity of the anti-cheat verification routines and maintain fair multiplayer server environments.

**Legal Disclaimer:** Project I.G.I.-2: Covert Strike is the registered trademark of its respective copyright holders. BitPatch is an independent community restoration project and is not affiliated with, sponsored by, or endorsed by Innerloop Studios, Codemasters, or GOG. This repository contains no base game executable binaries or proprietary level packages. See [DISCLAIMER.md](DISCLAIMER.md) for full terms.

**Attribution & Usage Policy:** You are free to utilize and reference this patch for community servers and modding initiatives. However, you **MUST** provide clear, visible credit to **Team Bitmasters** and include a direct link back to [reviveigi2.com](https://reviveigi2.com) or this GitHub repository. Decompiling, reverse engineering, bypassing anti-cheat modules, or re-uploading modified binaries under another name is strictly prohibited.


---
*Developed and maintained by Team Bitmasters (2012–2026).*

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:6090EE&height=160&section=footer&text=TEAM%20BITMASTERS&fontSize=38&fontColor=ffffff&fontAlignY=65" width="100%" alt="Team Bitmasters Footer" />
</p>
