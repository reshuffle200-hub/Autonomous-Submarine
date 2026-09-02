# Team headshots

Drop each member's headshot in this folder using these **exact** filenames
(the site references them directly):

| Filename | Team member | Hometown |
|----------|-------------|----------|
| `nathan.jpg` | Nathan Dechachutinan | Birmingham, AL |
| `ryley.jpg`  | Ryley Dubose | Prattville, AL |
| `kyle.jpg`   | Kyle Hakel | Enterprise, AL |
| `reid.jpg`   | Reid Humphrey | Dothan, AL |
| `ethan.jpg`  | Ethan Zecher | Madison, AL |

## Gantt chart screenshot

Add a screenshot of the full Gantt chart to this folder as **`gantt.png`**
(a wide PNG works best). It appears in the site's **Schedule** section. Until
it is added, that section shows a labeled placeholder. The "View the full Gantt
chart" button links to the public Google Sheet (set that URL in `index.html`,
replacing `REPLACE_WITH_GANTT_LINK`).

Notes:
- Square-ish crops look best (the avatar is a circle). Anything works —
  the image is center-cropped by CSS.
- Keep filenames lowercase with the `.jpg` extension. If you must use PNG,
  update the matching `src` in `index.html`.
- Until a photo is added, the card automatically shows the member's
  initials, so the site never looks broken.
