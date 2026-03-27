# Mission Control — Simplified Focus Dashboard

## Current Version: Simplified Dashboard (simplified.html)

**Streamlined focus dashboard** for the new 2-project strategy.

### What It Shows

- **2 Active Projects** — Revenue Sprint (primary) + KlaseCo.com (support)
- **Flat Team Structure** — 6 equal team members, no hierarchy
- **Archived Projects** — 5 projects paused for focus
- **Clear Metrics** — Revenue targets and completion status

### How to Open

```bash
# Recommended: Simplified version
open simplified.html
```

## Legacy Version: 3D Complex Dashboard (index.html)

The original complex 3D visualization with 6 projects and hierarchical C-Suite structure. 

**Features:** 3D visualization, complex agent hierarchy, 6 project tracking, animated connections.
**Status:** Archived — too complex for current focus strategy.

```bash
# Legacy version (complex)
open index.html
```

## Strategic Change

**Before:** 6 projects + 8-agent C-Suite hierarchy + complex 3D visualization
**After:** 2 projects + 6-agent flat team + simple focus dashboard

Focus wins. Ship Revenue Sprint first.

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
