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

| Game | Description |
|---|---|
| [Our World](../OurWorldSite) | Flagship AR/VR metaverse |
| [One World](../OneWorldSite) | Full 3D MMORPG sequel (Unreal Engine 5) |
| [ODOOM](../ODOOMSite) | OASIS-powered classic Doom |
| [OQUAKE](../OQuakeSite) | OASIS-powered Quake |
| [Shadow Fighter](../ShadowFighterSite) | Fighting game trilogy |
| [Snake 3000](../Snake3000Site) | The original OASIS game |

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
