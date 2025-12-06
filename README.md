# GTA5 Enhanced

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:00ff88&height=120&section=header&text=&fontSize=0" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=500&lines=GTA5+Enhanced;Fast+Weapon+Switching;v1.7" alt="Typing SVG" />

<br/>

![Version](https://img.shields.io/badge/Version-1.7-00FF88?style=for-the-badge&labelColor=1a1a2e)
![Platform](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white&labelColor=1a1a2e)
![AutoHotkey](https://img.shields.io/badge/AutoHotkey-v1.1-334455?style=for-the-badge&logo=autohotkey&logoColor=white&labelColor=1a1a2e)

<br/>

**Instant weapon switching for GTA5** 

[Features](#features) · [Install](#installation) · [Controls](#controls) · [Config](#configuration)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="500">

</div>

---

## Features

<table>
<tr>
<td width="50%">

### ⚡ Core Features
- **Instant Weapon Switch** - 0ms delay
- **R** → Rocket Launcher
- **N** → Sniper Rifle
- **Auto Ammo Purchase** - One key buy

</td>
<td width="50%">

### 🎮 Quality of Life
- **Session Stats** - Track your usage
- **Session Timer** - Time played
- **Auto GTA5 Detection**
- **Minimal GUI Overlay**

</td>
</tr>
</table>

---

## Controls

<div align="center">

| Key | Action | Key | Action |
|:---:|--------|:---:|--------|
| `F1` | Toggle ON/OFF | `R` | Rocket Switch |
| `F2` | Show/Hide GUI | `N` | Sniper Switch |
| `F3` | Buy All Ammo | `F5` | Reset Stats |
| `F4` | Toggle Sound | `F6` | Toggle Notify |
| `F12` | Exit Script | | |

</div>

---

## Installation

<table>
<tr>
<td>

```
 1  Install AutoHotkey v1.1
    └─ autohotkey.com/download
    
 2  Download GTA5-Enhanced.ahk
 
 3  Double-click to run
 
 4  Launch GTA5
 
 5  Press F1 to enable
```

</td>
<td>

> ⚠️ **Important**
> - Use AutoHotkey **v1.1** (not v2)
> - Run as **Administrator** if needed
> - Works with GTA5 Enhanced edition

</td>
</tr>
</table>

---

## Configuration

```autohotkey
; ══════════════════════════════════════
; CONFIGURATION - Edit to match your setup
; ══════════════════════════════════════

; Weapon slots (check your weapon wheel)
WEAPON_SLOT_C4 := "5"
WEAPON_SLOT_ROCKET := "4"
WEAPON_SLOT_SNIPER := "9"

; GUI settings
GUI_AUTO_HIDE_TIME := 8000   ; Auto-hide after 8 seconds (0 = never)
```

---

## GUI Preview

<div align="center">

```
╔══════════════════════════════════════╗
║  ⚡ GTA5 ENHANCED              v1.7  ║
╠══════════════════════════════════════╣
║  ✅ GTA5 Focused (PID: 12345)        ║
╠══════════════════════════════════════╣
║                                      ║
║  ● ACTIVE                            ║
║                                      ║
╠══════════════════════════════════════╣
║  🚀 Rockets: 42                      ║
║  🎯 Sniper: 28                       ║
║  💰 Ammo: 15                         ║
║  ⏱️  Session: 01:23:45               ║
╠══════════════════════════════════════╣
║  🔊 Sound: ON      🔔 Notify: ON     ║
╚══════════════════════════════════════╝
```

</div>

---

## Troubleshooting

<details>
<summary><b>🔴 Script won't start</b></summary>
<br/>

| Problem | Solution |
|---------|----------|
| Wrong AHK version | Install AutoHotkey v1.1 (not v2) |
| Permission denied | Run as Administrator |
| Antivirus blocking | Add exception for .ahk files |

</details>

<details>
<summary><b>🟡 GTA5 not detected</b></summary>
<br/>

| Problem | Solution |
|---------|----------|
| Script started first | Launch GTA5, then run script |
| Detection delay | Wait 2-3 seconds |
| Wrong window | Click on GTA5 window to focus |

</details>

<details>
<summary><b>🟡 Wrong weapons switching</b></summary>
<br/>

| Problem | Solution |
|---------|----------|
| Different weapon wheel | Edit slot numbers in config |
| Keys not working | Make sure F1 is pressed (enabled) |
| Focus issue | Click GTA5 window first |

</details>

<details>
<summary><b>🟡 Auto-buy not working</b></summary>
<br/>

| Problem | Solution |
|---------|----------|
| In a mission | Exit mission first |
| Menu timing | Increase Sleep values in F3 section |
| Wrong menu position | Start from default menu state |

</details>

---

## Technical

<div align="center">

| Setting | Value | Purpose |
|---------|-------|---------|
| `SendMode` | Input | Fastest key sending |
| `SetKeyDelay` | -1, -1 | No delay between keys |
| `Process Priority` | High | Better performance |
| `MaxHotkeysPerInterval` | 99000000 | Unlimited hotkeys |

</div>

---

## Disclaimer

> ⚠️ **Use at your own risk.** This script may violate Rockstar's Terms of Service. 
> Recommended for **private sessions only**. The author is not responsible for any consequences.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:00ff88&height=80&section=footer" width="100%"/>

**Made by [Lithap](https://github.com/Lithap)** · MIT License

<img src="https://img.shields.io/github/stars/Lithap/Gta5-enhanced-Macro?style=social" alt="Stars">

</div>
