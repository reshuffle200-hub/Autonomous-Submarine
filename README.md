# Modular UUV — 3D-Printed Shell · Team 14

Project-showcase website for our **Auburn University Senior Design** capstone (**Team 14**).

An **8–10 ft class unmanned underwater vehicle (UUV)** built around a
**3D-printed modular shell** and an **aluminum pressure hull**, designed for
autonomous missions with acoustic communication.

> All specifications on the site are preliminary and are **subject to change**.

## Site

A plain static site — no build step, no dependencies.

| File | Purpose |
|------|---------|
| `index.html` | Page markup and content (nav, hero, concept, specs, modular design, team) |
| `styles.css` | Dark naval theme and responsive layout |
| `script.js`  | Mobile nav toggle and reveal-on-scroll effects |
| `images/`    | Team headshots (see `images/README.md` for filenames) |
| `README.md`  | This file |

## Team headshots

Add each member's photo to `images/` using the exact filenames listed in
`images/README.md` (`nathan.jpg`, `ryley.jpg`, `kyle.jpg`, `reid.jpg`,
`ethan.jpg`). Until a photo is present, that card shows the member's initials,
so the launch page always renders cleanly.

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
- **Propulsion:** 48 V battery, 24 V thruster
- **Comms:** Acoustic (subsea) + RF/Satcom (surface)
- **Control:** Autonomous with remote override

## Team — Auburn University

- Nathan Dechachutinan
- Ryley Dubose
- Kyle Hakel
- Reid Humphrey
- Ethan Zecher
