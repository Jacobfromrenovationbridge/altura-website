# Altura Design & Build

Static marketing site for Altura Design & Build.

## Structure

- `index.html` — the entire site (single-page, self-contained HTML/CSS).
- `vercel.json` — Vercel static hosting config.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on [Vercel](https://vercel.com). Every push to `main` triggers an
automatic production deploy once the repo is connected to a Vercel project.
