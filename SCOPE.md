# Scope — Hardware Blueprints Index

## What belongs here

Repositories whose primary content is the **build documentation for a physical object** — enough to order the parts and assemble it.

Include a repo if it has most of:

- A **bill of materials** — the parts, costed
- **Sourcing** — real listings, suppliers, prices, dated
- A **hardware spec** — component choice and why, wiring, power, enclosure, mounting
- A **firmware or integration plan** where the thing is electronic (ESPHome/Arduino, Home Assistant entities)

The defining test: **could someone else buy the parts and build it from this repo?** If yes, it belongs here — built or not.

Applies equally to:

- Sensor and IoT builds (ESP32/ESP8266, Zigbee, Thread)
- Single-board-computer appliances (Raspberry Pi and similar)
- Input devices and peripherals (macropads, keyboards)
- Upgrades and rebuilds of existing hardware, where the repo carries a parts list and sourcing

## What does NOT belong here

- **Plans with no BOM** — a spec for something to be built, but no parts list → [Architectural-Plans-Index](https://github.com/danielrosehill/Architectural-Plans-Index)
- **Documentation of an off-the-shelf device** — reverse-engineered APIs, setup notes, troubleshooting for something bought whole → topical index or [Docs-And-Notes-Index](https://github.com/danielrosehill/Docs-And-Notes-Index)
- **3D models and printables on their own** — geometry without a build → [Printables-Index](https://github.com/danielrosehill/Printables-Index), unless the model is one line of a larger build
- **Software projects that merely run on hardware** → the appropriate topical index
- **Purchase research for a finished product** — comparing things to buy rather than parts to combine

## Overlap rules

- A repo may appear in both this index and `Architectural-Plans-Index` when it holds a substantial written design *and* a costed BOM
- A repo may appear in both this index and a topical index (e.g. a Home Assistant or Claude Code index) when the build serves that domain
- Prefer this index whenever the repo answers *"what do I buy and how does it go together?"*

## Privacy

This index is public. Private repositories are not listed here — build documentation that is private (household-specific, purchase-in-progress, or containing addresses or account details) stays out until the repo is made public.
