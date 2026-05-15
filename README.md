# Perseid Echo Demos

Index of static demo sites built by Perseid Echo Creations. Each demo lives in its own subfolder and ships under the same `main`-branch GitHub Pages deployment.

Live index: https://slybry2000.github.io/perseid-echo-demos/

## Demos

| Demo | Path | Live URL |
|------|------|----------|
| Perseid Echo (demos index) | `/` | https://slybry2000.github.io/perseid-echo-demos/ |
| Dream Travel | `/dream-travel/` | https://slybry2000.github.io/perseid-echo-demos/dream-travel/ |
| Riley Lawns | `/riley-lawns/` | https://slybry2000.github.io/perseid-echo-demos/riley-lawns/ |

## Dream Travel

Single-page site for community leaders who host custom group trips with Dream Travel. Image-first hero with the host as subject; the partnership (host fills the seats, Dream Travel carries the trip) is the visible center of the page.

- `dream-travel/index.html` — landing page
- `dream-travel/styles.css` — site stylesheet
- `dream-travel/ART-BIBLE.md` — binding design spec for future sections
- `dream-travel/images/` — hero photos (art-directed desktop + mobile crops) and logos
- Legacy URLs (`about.html`, `adult-travel.html`, `ambassador.html`, `contact.html`, `experiences.html`, `journeys.html`, `private-custom-group-tours.html`) redirect to the matching anchor on `index.html`
- `dream-travel/backup/2026-04-14-pre-ambassador-pivot/` — frozen copy of the previous multi-page site

## Notes

- No build step. Each demo is hand-authored HTML/CSS.
- GitHub Pages publishes from the `main` branch root.
- Contact flows use direct `mailto:` and `tel:` — no fake form submission.

## Local preview

Serve the repo root with any static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/` for the demos index, or `http://localhost:8000/dream-travel/` for the Dream Travel site directly.
