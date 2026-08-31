# Project Context — Modular UUV Capstone Showcase

A self-contained briefing you can paste into a Claude chat (or share with a
teammate) to pick up this work cold.

## The engineering project

- **Name:** Modular UUV — 3D-Printed Shell
- **Vehicle:** 8–10 ft class unmanned underwater vehicle (UUV)
- **Core design:** 3D-printed modular shell over an aluminum pressure hull
- **Mission profile:** autonomous missions with acoustic communication
- **Key specs (all preliminary / subject to change):**
  - Length ~9 ft (8–10 ft class)
  - 48 V battery, 24 V thruster
  - Comms: acoustic (subsea) + RF/Satcom (surface)
  - Control: autonomous with remote override
- **Team (Auburn):** Nathan Dechachutinan, Ryley Dubose, Kyle Hakel, Reid Humphrey, Ethan Zecher

## The website

- **Repo:** `reshuffle200-hub/Autonomous-Submarine`
- **Branch:** `claude/auburn-uuv-showcase-ryaj13` (pushed)
- **Stack:** plain static site — HTML + CSS + a little JS, no build step,
  GitHub Pages–hostable, dark naval theme
- **Files:**
  - `index.html` — sticky nav; hero; concept overview; key specs (marked
    subject to change); modular design breakdown; team
  - `styles.css` — dark naval theme, responsive
  - `script.js` — mobile nav toggle + reveal-on-scroll
  - `README.md` — overview, local-run, GitHub Pages steps
- **Not yet done:** no PR into `main`; Pages not yet enabled; specs detail
  lines and team roles are placeholders.

## Deploy (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → Branch:
`claude/auburn-uuv-showcase-ryaj13`, folder `/ (root)` → Save.
Expected URL: `https://reshuffle200-hub.github.io/Autonomous-Submarine/`

## Likely next steps

1. Swap placeholder specs for real numbers (weight, depth rating, endurance,
   battery capacity).
2. Add team roles (ME/EE/Software) and/or headshots.
3. Open a PR into `main`, and/or add a GitHub Actions Pages auto-deploy
   workflow.

> Note: a regular Claude chat can help draft and refine content, but it can't
> push to the repo — that requires a Claude Code session.
