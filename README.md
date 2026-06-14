# EVE Abyss Companion — Web Edition

**v2.1.0** · Free single-file Abyssal Deadspace companion — 20-min timer, NPC detection, loot tracking. Open in Chrome/Edge/Opera GX. No install required.

> "Built by capsuleers, for capsuleers."

---

## What it does

- **20-minute filament timer** with a circular countdown ring and per-room split times
- **Automatic NPC detection** — watches your EVE combat log and identifies hostiles as they appear, colour-coded by EWAR type (scram, neut, web, damp, logi)
- **Always-on-top overlay** via Document Picture-in-Picture — floats over EVE in windowed-fullscreen
- **Loot delta tracking** — enter your cargo value before and after, it calculates the run's ISK
- **Run history and stats** — ISK/hour, best runs, breakdown by tier and weather
- **Performance recommendations** — ranks which tier + weather pays best from your own data
- **Session tracking** — name a block of runs, set a target count, get a summary when done
- **NPC Library** — searchable, filterable, with kill priority and EWAR tags for 126 Abyssal NPCs
- **All data stays local** — nothing leaves your machine. No accounts, no servers, no API calls.

---

## Requirements

| Requirement | Notes |
|---|---|
| **Chrome, Edge, or Opera GX** | Must be opened directly as a file, not served via a web server |
| **EVE Online** | Gamelogs folder must be accessible (usually `Documents\EVE\logs\Gamelogs`) |
| Firefox | ❌ Not supported — missing File System Access and Picture-in-Picture APIs |

---

## Quick start

1. Download `EveAbyssCompanion.html`
2. Open it directly in Chrome, Edge, or Opera GX
3. Complete the one-time setup wizard — point it at your EVE Gamelogs folder
4. Pick your tier and weather, enter your cargo's estimated value in **Before**, and hit **▶ Start** as you take the gate

---

## Full NPC dataset

The bundled starter set covers the most common NPCs. The full 126-entry dataset (`npc_dataset.json`) covers all seven Abyssal factions:

- Triglavian Collective (37)
- Rogue Drones (24)
- Drifters / Seekers (22)
- EDENCOM / CONCORD — Disparu Troop (14)
- Angels — Lucifer line (10)
- Sleepers — Lucid line (10)
- Sansha's Nation — Devoted line (9)

To load it: **Systems → Import dataset (.json)** — browse to `npc_dataset.json`.

---

## EULA compliance

EVE Abyss Companion reads log files from disk only. No memory reading, no game hooks, no injection, no EVE client interaction of any kind. It is fully compliant with the EVE Online EULA and Terms of Service.

---

## Support the project

If this saves your ship, consider buying the dev a coffee.

- **Ko-fi:** [ko-fi.com/jakkelsza](https://ko-fi.com/jakkelsza)
- **PayPal:** [paypal.me/JakkelsZA](https://paypal.me/JakkelsZA)
- **Bitcoin:** `35U3rbr7XWAsi55KqUJDpRKoKB8PistGZv`

---

## Also available

The original Windows desktop version (WPF/.NET 8) is at [github.com/Jakelsza/EveAbyssCompanion](https://github.com/Jakelsza/EveAbyssCompanion).

---

*EVE Online and the EVE logo are the registered trademarks of CCP hf. All rights reserved worldwide. This app is an unofficial fan-made tool and is not affiliated with, endorsed by, or sponsored by CCP hf.*
