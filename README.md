# Valence Fusion Calculator

A lightweight, offline-capable browser tool for [Warframe](https://www.warframe.com) players to calculate Valence Fusion bonus results and track 60% weapon progress.

---

Live Demo: https://tower4me.github.io/Valence-Fusion-Calculator/

---

## Features

- **Fusion Calculator** — Enter two weapon bonus values, get the result instantly using the official formula: `min(1.1 × max(Bonus 1, Bonus 2), 60)`. Includes the ≥58% → 60% rounding rule.
- **Reverse Calculator** — Enter a target bonus value and get the minimum bonus you need on one of the two weapons to reach it.
- **60% Weapon Tracker** — Check off every Kuva, Tenet, and Coda weapon you've maxed. Progress is saved automatically.
- **Light & Dark Theme** — Toggle between themes; preference is remembered.
- **Multilingual** — Available in German, English, Spanish, and French.

---

## How Storage Works

This tool uses your browser's **localStorage** — no account, no server, no cookies.

| What gets saved | Where |
|---|---|
| Checked weapons (your progress) | localStorage key `vf-checked` |
| Theme preference (light/dark) | localStorage key `vf-theme` |
| Language preference | localStorage key `vf-lang` |

**What this means for you:**
- Nothing leaves your device. Zero data is transmitted anywhere.
- Your progress persists across browser restarts and system reboots.
- Data is tied to the browser and domain you open the file from. If you open the file from a different path or browser, it starts fresh.
- Clearing your browser's site data or cache will erase saved progress. Export or note your progress before doing so.
- Incognito/private mode does not persist data between sessions.

---

## Disclaimer

This is an unofficial fan tool and is not affiliated with or endorsed by Digital Extremes. Warframe and all related assets are property of Digital Extremes Ltd.
