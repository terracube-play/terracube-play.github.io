# Terracube

Terracube is a free, block-style sandbox game that runs in your browser. Explore a procedurally generated world, mine and place blocks, craft tools, and build without downloading anything or signing up.

**Play:** [terracube-play.github.io](https://terracube-play.github.io/)

## Features

- Procedurally generated terrain with hills, forests, beaches, oceans, caves, and ores
- Mining, block placement, and a hotbar
- Survival and creative modes
- Crafting, tools, beds, and a day-and-night cycle
- Hostile mobs that appear at night
- WebGL rendering in a single browser page

## How to play

Click **Play now** on the website, then click the game to begin. The game is best played on a desktop or laptop with a keyboard and mouse.

| Action | Control |
|---|---|
| Move | `W` `A` `S` `D` |
| Look | Mouse or arrow keys |
| Jump / swim up | `Space` |
| Sprint | `Shift` |
| Mine blocks / attack | Hold left click |
| Place a block | Right click |
| Use a crafting table or bed | Right-click it |
| Pick a block | Middle click |
| Select a hotbar slot | `1`–`9` or mouse wheel |
| Open inventory and crafting | `E` |
| Switch Survival / Creative | `G` |
| Fly in Creative mode | `F` or double-tap `Space` |
| Pause | `Esc` |

In Survival mode, collect materials and use the inventory to craft. A crafting table unlocks additional recipes. A bed can set your spawn point and let you sleep through the night.

## Run locally

This is a static site: the game and its styling are included in `index.html`. Serve the repository root with any static web server, then open the local address in a WebGL-capable browser.

For example, with Python:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project files

- `index.html` — website, game interface, and game implementation
- `manifest.json` — installable web app metadata
- `icon-192.png`, `icon-512.png` — app icons

## Notes

- The game currently does not save world changes; a new visit starts with a newly generated world.
- A keyboard and mouse are recommended. Mobile play is not well supported.
- Terracube is an independent browser game and is not affiliated with Mojang Studios or Microsoft.
