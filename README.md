# Ultimate Pi IVI Hat — The Modular Car Computer Revolution

![Valkyrie Ecosystem](https://via.placeholder.com/800x400?text=Valkyrie+Modular+IVI)  
*(Coming: Rendered 3D renders from KiCad)*

## What is this?
The **first brick** in the Valkyrie modular automotive computing platform.  
Starts as a Raspberry Pi 5 HAT with **everything** (DAB+, GPS, CAN-FD, 4×75W amp, 5G, Wi-Fi 6E).  
Evolves into plug-and-play modules for Pi, CM5, or our custom i.MX93 board in 2027.

### v1.0 Features (Pi HAT, shipping Q1 2026)
- **DAB+/FM**: SI4684 + CM108 USB audio (zero-lag radio)
- **GPS + RTC**: u-blox MAX-M10S (dead reckoning, Fakra antenna)
- **CAN-FD + Ignition**: MCP2518FD + STM32G0 (wake on key, graceful shutdown)
- **Audio Amp**: TPA3255 4×75W Class-D (bypass factory radio, full DSP/EQ from Qt)
- **USB Hub**: 5-port GL3523 (PD fast-charge, one dedicated to GPS)
- **Power**: 12→5/3.3V automotive DCDC (MP9943, -40..+105°C)
- **Connectivity**: Wi-Fi 6E/BT 5.4 (CYW55573), optional 5G (Quectel RG255C)
- **Future-Proof**: 60-pin "V-Bus" expansion for modular unbundling

BOM: ~$160 (100 pcs) | Size: 85×56 mm (Pi HAT standard) | 4-layer PCB

## Build Status
| Milestone | Status | ETA |
|-----------|--------|-----|
| Schematic v0.1 (Power + USB) | ✅ Done | Now |
| Full Schematic (All Blocks) | 🔄 In Progress | Dec 1 |
| PCB Layout + DRC | 🟡 Planned | Dec 7 |
| Prototypes (5× JLCPCB) | 🟡 Planned | Dec 15 |

## Getting Started
1. Clone: `git clone https://github.com/sjdean/ultimate-pi-ivi-hat.git`
2. Open `pcb/ultimate-hat-v0.1.kicad_pro` in KiCad 8
3. Tweak → Commit → PR

## License
MIT — Open-source forever. Sell kits, fork, build on it. Credit appreciated.

## Roadmap
- **2026 Q1**: Pi HAT v1.0 ships
- **2026 Q4**: Modular unbundle (separate GPS/CAN/amp boards)
- **2027 Q2**: Valkyrie i.MX93 SOM + carrier (Pi-killer)

Built with ❤️ by @sjdean + Grok (xAI). Questions? Open an issue.

---
*Powered by Raspberry Pi Foundation & NXP i.MX93*
