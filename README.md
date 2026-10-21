# Hardware Blueprints Index

[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Start-Here)
[![Index Repo](https://img.shields.io/badge/Type-Index_Repo-purple?style=flat-square)](https://github.com/danielrosehill/Start-Here)
[![GitHub](https://img.shields.io/badge/GitHub-danielrosehill-blue?style=flat-square&logo=github)](https://github.com/danielrosehill)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

An index of repositories that document **physical builds** — the bill of materials, sourcing, wiring and enclosure decisions, and firmware plan for a piece of hardware. These are blueprints: enough to order the parts and assemble the thing, whether or not it has actually been built yet.

See [SCOPE.md](SCOPE.md) for what belongs here and how this index relates to the neighbouring ones.

## Sensors & Monitoring

| Project | Description | Links |
|---------|-------------|-------|
| **ESP32 Porch Construction-Impact Monitor** | Weatherproofed porch sensor logging noise (LAeq via INMP441 + ESPHome sound-level-meter), dust (SDS011) and optional vibration (MPU6050) from a nearby construction site, reporting to Home Assistant. Two costed variants, verified AliExpress sourcing | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/esp32-porch-decibel-monitor) |

## Input Devices & Peripherals

| Project | Description | Links |
|---------|-------------|-------|
| **Claude Macropad V2** | Dedicated macropad for driving Claude Code (approve, stop, new session, transcript navigation) with a host-driven status LED wired to Claude Code hooks. Off-the-shelf and custom ESP32 / RP2040 build paths | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Claude-Macropad-V2) |

## Infrastructure & Appliances

| Project | Description | Links |
|---------|-------------|-------|
| **Claude Rescue Pi** | Raspberry Pi out-of-band management node running Claude Code over Tailscale + Cloudflare Access, wired to a workstation via serial, direct-link ethernet and a smart plug as an emergency recovery surface. SBC comparison + full BOM | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Claude-Rescue-Pi) |

---

## Anatomy of a blueprint repo

The pattern these repos converge on, most fully realised in [esp32-porch-decibel-monitor](https://github.com/danielrosehill/esp32-porch-decibel-monitor):

| File | Contents |
|---|---|
| `spec.md` | What it is, variants, goals, the design decisions and what was ruled out |
| `research.md` | Dated component research — comparisons, prices, discarded options |
| `bom.md` / `bom.json` | Bill of materials, costed, ideally per variant |
| `sourcing.md` | Real listings with URLs and verified prices, dated, plus order-time checks |
| `software.md` | Firmware / integration plan (ESPHome YAML, HA entities, dashboards) |

Not every repo needs all five, but a repo with no BOM is a plan, not a blueprint — it belongs in [Architectural-Plans-Index](https://github.com/danielrosehill/Architectural-Plans-Index).

---

## Related Indexes

| Index | Covers |
|---|---|
| [Architectural Plans Index](https://github.com/danielrosehill/Architectural-Plans-Index) | Plans, specs and design documents where the artifact is the written plan |
| [Printables Index](https://github.com/danielrosehill/Printables-Index) | Print-ready reference posters built from HTML/CSS |
| [Docs And Notes Index](https://github.com/danielrosehill/Docs-And-Notes-Index) | Documentation and reference projects |

---

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
