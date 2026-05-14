<div align="center">
  <img src="https://img.shields.io/badge/Android-4.4+-00C853?style=flat-square&logo=android" />
  <img src="https://img.shields.io/badge/Arch-ARMv7%20%7C%20ARM64-1976D2?style=flat-square" />
  <img src="https://img.shields.io/badge/Unity-IL2CPP-FF6F00?style=flat-square" />
  <br/><br/>
  <h1>Magic Offset Tester</h1>
  <p><b>A powerful on-device runtime offset testing & memory manipulation tool for Android game reversing</b></p>
</div>

---

## 📱 Overview

**Magic Offset Tester** is an all-in-one runtime toolkit built for game reverse engineers and modders. It lets you test offsets, hook methods, patch memory, and inspect IL2CPP data — all from a floating overlay menu while your target app is running.

No PC needed. Everything works on-device via an interactive floating menu.

---

## ✨ Features

| Category | Capabilities |
|----------|-------------|
| **Hex Patching** | Write offsets, replace hex directly, or use the Easy Patcher for common value patterns (bool, int, float, NOP). Patch & restore on the fly. |
| **Method Hooking** | Hook game methods and override return values — supports bool, int, float, Vector2, and Vector3 types. |
| **Void/Field Hooking** | Hook update-style void methods with parameter-aware patterns. Modify fields in memory directly — bool, int, float, Vector2, Vector3. |
| **Static Void Hooking** | Hook static methods and override their parameters or skip execution entirely. |
| **Call Void** | Hook void functions to prevent them from executing (disable functionality). |
| **Link Classes** | Chain pointer offsets to navigate complex class hierarchies and access nested instance fields. |
| **IL2CPP Dumper** | Experimental built-in IL2CPP assembly dumper with real-time progress tracking. |
| **Live Value Display** | Floating overlay box that shows real-time values from hooked methods and fields with auto-refresh. |
| **Resizable Menu** | Drag the resize handle to adjust menu width and height to your preference. |
| **Library Monitor** | Check target library load status and device info at a glance. |
| **Theme Support** | Toggle between Dark and Light themes. |
| **Menu Customization** | Adjust icon size, icon alpha, hide icon, enable shimmer animation, toggle floating box. |
---

## 📸 Menu Sections

1. **Hex Patcher** — Patch raw hex at any offset with instant apply/restore.
2. **Hook Getter** — Hook methods and set custom return values.
3. **Set Void / Field** — Hook void update methods and modify instance fields.
4. **Display Values** — Real-time monitoring of method returns and field values.
5. **Donation & Support** — Support the project.
6. **Tools & Settings** — Library config, unhook, menu settings, theme, and IL2CPP dumper.

---

## 🛠 Integration

The app comes with a built-in guide showing exactly how to integrate the floating menu into any Android app:
- Required manifest permissions
- Service declaration
- Launch code snippets (with & without overlay permission)

---

## 🤝 Support & Community

- **Telegram Channel:** [@retiredgamermods](https://t.me/retiredgamermods)
- **Telegram Group:** [@magicmodschat](https://t.me/magicmodschat)
- **YouTube:** [Magic Mods](https://youtube.com/@magicmods-u5k)

---

## ☕ Donations

If this tool helps you, consider supporting the project:

| Method | Details |
|--------|---------|
| 💚 **Opay** | `6555602697` |
| 💙 **USDT (ERC20)** | `0xfc2deb7ad7217b6cb004011ffe366f4dc585f86e` |
| 💜 **USDT (TRC20)** | `TFEUopXJVC1EUapKBX7etkYjaAZNeyCaQi` |
| 💎 **USDT (TON)** | `UQDyjlHy5-n3XoKmJ9OUSkmFJCtBWpNYk2eR1DVeN8nHlIek` |
| 🟧 **Bitcoin** | `1DUP4T7GzaD3b1PA2U1Az8zx5PcsTZHZkP` |
| ⚡ **XRP** | `r4rjtVAtG3gmcDHU3nmXdYKcVSbvGPF7Fa` (Memo: `503234574`) |

Every bit helps keep development going. Thank you! ❤️

---

## ⚠️ Disclaimer

This tool is intended for **educational purposes and lawful security research only**. Modifying apps may violate their terms of service. Use responsibly and only on apps you own or have permission to test.

---

<div align="center">
  <b>Made with ❤️ by Magic Mods</b>
</div>
