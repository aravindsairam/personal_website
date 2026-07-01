# personal_website

Personal portfolio site — a single-page static website (robotics / aerial drone work).

## Structure

- `index.html` — the site
- `DD.mp4` — background video (H.264, web fast-start)
- `images/` — aerial photos used in the gallery
- `uploads/` — resume PDF

## Local preview

It's a plain static site — no build step. Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Static host (e.g. Cloudflare Pages). Point the host at this repo root; there's no build command and no output directory to configure.
