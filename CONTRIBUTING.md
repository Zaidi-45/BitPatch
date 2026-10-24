# Contributing to BitPatch

Thank you for helping improve the BitPatch multiplayer restoration initiative. 

Because BitPatch binaries and engine hooks are maintained directly by Team Bitmasters to protect anti-cheat integrity, we do not accept direct pull requests for engine binaries. However, community contributions through **bug discovery, crash telemetry, map compatibility testing, and dedicated server stress testing** are essential.

---

## How to Report Bugs & Crashes

If you experience an engine freeze, startup crash, or server desync:

### 1. Check Existing Issues
Before opening a new ticket, search the [Issues tab](https://github.com/Zaidi-45/BitPatch/issues) to verify if the bug has already been documented or resolved in a development build.

### 2. Submit a Quality Bug Report
When opening a ticket, include:
* **Operating System:** Windows 10, 11 (build version), or Linux/Wine environment.
* **Failure Context:** Did the crash occur on startup, in the multiplayer server browser, upon spawning, or during map transition?
* **Multiplayer Host:** Dedicated server name, player count, and current map.
* **Renderer / Wrapper:** dgVoodoo 2 (and resolution settings) or native DirectX.

---

## Dedicated Server & Map Testing

We actively seek community operators to:
* Stress test high-concurrency dedicated servers (16–32 player slots).
* Test custom community maps for missing texture files, spawn point loops, or memory leaks.
* Document unhandled network packet anomalies.

Join our [Discord Community](https://discord.gg/dvwcbGVeyV) to coordinate live server testing sessions with the developers.
