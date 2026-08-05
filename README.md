# OGEngine — The OASIS Omniverse Game Engine

**One Engine, Infinite Worlds**

OGEngine is the shared game runtime powering all OASIS-connected worlds. It provides a common foundation for avatar SSO, shared quests, NFT items, real-world GPS discovery and AR combat — so any game built on OGEngine is automatically part of the OASIS Omniverse.

## What OGEngine Provides

| Feature | Description |
|---|---|
| **Avatar SSO** | Single sign-on with OASIS universal avatars across all OGEngine games |
| **Shared Quests** | Quests and missions that span multiple games simultaneously |
| **NFT Items** | Weapons, armour, skins and collectibles owned on-chain, usable in every OGEngine game |
| **GeoHotSpots** | Real-world GPS locations in parks that hide in-game items and unlock AR events |
| **AR Combat** | Augmented reality enemy encounters overlaid on real-world environments |
| **Karma Integration** | OASIS Web4 karma awarded for in-game achievements |
| **STARNET Registry** | All assets, quests and hotspots registered in the STARNET decentralized store |

## Games Built on OGEngine

### Live

| Game | Base engine | Description |
|---|---|---|
| Our World | Our World engine | Flagship AR/VR metaverse — the real world is the level |
| ODOOM | UZDoom (GZDoom fork) | OASIS-powered classic Doom |
| OQUAKE | vkQuake | OASIS-powered Quake |

### Generation 1 — In Development (FPS)

| Game | Base engine | Status |
|---|---|---|
| ODOOM3 | dhewm3 (idTech4) | In development |
| ODOOM3-BFG | RBDOOM-3-BFG | In development |
| ODuke3D | EDuke32 | In development |
| ODuke3D-RT | Duke-RT (Raze fork, Vulkan RT) | In development |
| OWolf3D | ECWolf | In development |
| OQuake2 | Yamagi Quake II | In development |
| OQuake2-RTX | Q2 RTX | In development |
| OQuake3 | Quake3e | In development |
| OHeretic | UZDoom (GZDoom fork) | In development |
| OHexen | UZDoom (GZDoom fork) | In development |
| OShadowWarrior | Raze | In development |
| OShadowWarriorRT | Duke-RT (Raze fork, Vulkan RT) | In development |

### Generation 2 — Planned

| Game | Base engine | Status |
|---|---|---|
| OMorrowind | OpenMW | Integration files complete |
| OMineCraft | Minetest / Fabric mod | Planned |

## Tech Stack

| Layer | Detail |
|---|---|
| Site | Single-file `index.html` — inline CSS + vanilla JS |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |

## Running the Site Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Powering every OASIS world*
