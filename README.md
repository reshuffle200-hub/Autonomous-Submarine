# Modular UUV — 3D-Printed Shell

Project-showcase website for our **Auburn University Senior Design** capstone.

An **8–10 ft class unmanned underwater vehicle (UUV)** built around a
**3D-printed modular shell** and an **aluminum pressure hull**, designed for
autonomous missions with acoustic communication.

> ⚠️ All specifications on the site are preliminary concept-phase targets and are **subject to change**.

## Site

A plain static site — no build step, no dependencies.

| File | Purpose |
|------|---------|
| `index.html` | Page markup and content (nav, hero, concept, specs, modular design, team) |
| `styles.css` | Dark naval theme and responsive layout |
| `script.js`  | Mobile nav toggle and reveal-on-scroll effects |
| `README.md`  | This file |

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy — GitHub Pages

1. Push this branch to GitHub (already done).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set **Branch** to the branch containing these files and folder **/ (root)**, then **Save**.
5. Wait ~1 minute; the published URL appears at the top of the Pages settings.

For a permanent URL, merge this branch into `main` and point Pages at `main` / root.

## Key specs (subject to change)

- **Length:** ~9 ft (8–10 ft class)
- **Propulsion:** 48 V electric
- **Comms:** Acoustic (subsea) + RF/Satcom (surface)
- **Control:** Autonomous with remote override

## Team — Auburn University

- Nathan Dechachutinan
- Ryley Dubose
- Kyle Hakel
- Reid Humphrey
- Ethan Zecher
