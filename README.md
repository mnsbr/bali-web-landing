# HariOps landing

Static product landing for **HariOps** — Indonesia-first SaaS for tour & activity operators (WhatsApp inquiry → QRIS deposit → roster).

Placeholder brand name until marketing locks the final one.

## Stack

Plain HTML + CSS. No build step, no backend.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page (hero, problem, offer, proof, CTA) |
| `styles.css` | Layout and theme |
| `README.md` | This file |

## Run locally

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Edit copy / brand

- Brand name, WhatsApp link (`wa.me/...`), and email: search `HariOps`, `6200000000000`, and `hariops.example` in `index.html`
- Section copy lives in `index.html` under each `<section>`
- Colors/spacing: `styles.css` (`:root` variables)

## Deploy

Any static host works (GitHub Pages, Netlify, Cloudflare Pages, S3, etc.). Point the host at the repo root.
