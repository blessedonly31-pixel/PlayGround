# Mythfall: Frontline

A small, browser-based, offline-first 3D FPS prototype built with Three.js and Vite. It is a local single-player simulation—not an online game, a finished commercial shooter, or a published mobile app.

## Run locally

Requirements: Node.js 20.19+ or 22.12+ (required by the installed Vite 8 release).

```sh
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`). To create and serve a production build:

```sh
npm run build
npm run preview
```

The PWA service worker caches the production app shell and same-origin assets after the first successful online load. For offline installation, open the deployed site once while online, then use the browser's **Install app** / **Add to Home Screen** option. Service workers require HTTPS on a deployed site (localhost is also treated as secure). Optional Google Fonts are fetched from the network and fall back to system fonts offline.

## In the prototype

- 10 selectable, procedurally assembled locations
- Four modes: team elimination, battle royale-style survival, zombie waves, and assassin survival
- Three weapon/loadout presets, health and armor, ammunition/reload, pickups, and a match HUD
- Local AI-controlled enemies and (in team mode) friendly bots
- Desktop mouse/keyboard and touch movement, aiming, firing, and loot controls

## Controls

**Desktop:** Click the game to capture the mouse; `W A S D` move, mouse aims, left-click fires, `R` reloads, `E` collects nearby loot, `Shift` sprints, and `Esc` pauses/releases the mouse. Click to recapture the mouse after returning to play.

**Touch:** Use the left on-screen pad to move, swipe the open game area to aim, and use **FIRE** / **LOOT** on the right. Rotate the device to landscape for more room.

## Scope and limitations

This is a locally simulated prototype with lightweight procedural geometry and simple bot behavior. There is no network matchmaking, multiplayer service, account system, cloud save, production anti-cheat, or extensive content pipeline. The combat modes are playable approximations rather than a balanced or fully featured release. Performance varies by device; lower-end phones may struggle with WebGL.

The repository does **not** contain an Android application package or Play Store release. A PWA can be installed from a compatible browser, but Play Store distribution would require a separately configured Android wrapper/build, store assets, policy and permission review, testing, and a Play Console release. No publishing or store approval is implied.

<!-- omgithub:readme:start -->
## 🚀 Build, play, and remix with OMGithub

**Created using [OMGithub.com](https://omgithub.com).**

[![OMGithub](https://img.shields.io/badge/OMGithub-Open%20project-orange?style=for-the-badge)](https://omgithub.com/blessedonly31-pixel/PlayGround)
[![GitHub](https://img.shields.io/badge/GitHub-Source-181717?logo=github&style=for-the-badge)](https://github.com/blessedonly31-pixel/PlayGround)

- 🎮 [Open the project](https://omgithub.com/blessedonly31-pixel/PlayGround).
- ✨ [Remix this project](https://omgithub.com/?remix=blessedonly31-pixel%2FPlayGround).
- 💻 [Explore the source](https://github.com/blessedonly31-pixel/PlayGround).
- 🛠️ [Check build runs](https://github.com/blessedonly31-pixel/PlayGround/actions).
- 🐛 [Report an issue](https://github.com/blessedonly31-pixel/PlayGround/issues).
- 👤 [Explore the creator's projects](https://omgithub.com/blessedonly31-pixel).
- 🌍 [Create with OMGithub](https://omgithub.com).
<!-- omgithub:readme:end -->
