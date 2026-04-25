# Arena Community Partner Hub — Spring 2026

Static landing page for Arena's Spring 2026 cohort community partners. Single-file HTML with no build step.

## Local preview

Open `index.html` directly in a browser, or run a quick local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Deployed via Netlify on push to `main`. Configuration is in `netlify.toml`.

## Structure

- `index.html` — the hub page (HTML/CSS/JS in one file)
- `assets/` — Arena logo (SVG + PNGs)
- `graphics-pack/` — full-size partnership graphics (PNG)
- `graphics-thumbs/` — preview thumbnails (JPG)
- `arena-spring-2026-graphics.zip` — bundle of ready-to-post invitation graphics
- `netlify.toml` — caching headers, no-index meta

## Editing copy

All content lives directly in `index.html`. The `[COMMUNITY NAME]` placeholders are replaced live in the browser when a partner types in the input — no template engine.

## Contact

adriene@arenatalent.com
