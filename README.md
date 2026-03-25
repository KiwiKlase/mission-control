# KlaseCo Mission Control — 3D Visualization

Interactive 3D command center dashboard for KlaseCo operations.

## What It Shows

- **Command Center Hub** — Alex (Founder) and Kiwi (Chief of Staff) at the center
- **6 Project Nodes** — orbiting the hub with status color coding (green/yellow/blue)
- **5 Sub-Agent Stations** — Bolt, Lens, Relay, Echo, Spark with connections to their projects
- **Systems Layer** — Memory, Approval Queue, GitHub, Discord
- **Animated Connections** — particle-based data flow lines between all elements

## How to Open

Just open `index.html` in any modern browser:

```bash
open index.html
```

Or:
```bash
# macOS
open /Users/kiwi/.openclaw/workspace/projects/mission-control/index.html

# Or just double-click the file in Finder
```

No build step, no dependencies to install. Three.js loads from CDN.

## Controls

- **Click + Drag** — Orbit/rotate the view
- **Scroll** — Zoom in/out
- **Hover** — Tooltip with node info
- **Click** — Detail panel with full description and connections

## Status Colors

- 🟢 **Green** — Active / Building
- 🟡 **Yellow** — In Progress
- 🔵 **Blue** — Planned / Long Term
- ⚪ **White** — Systems

## Tech

Single HTML file, Three.js r128 from CDN, OrbitControls. No frameworks, no build tools.
