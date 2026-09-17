# HariOps landing

Static product landing for **HariOps** — Indonesia-first SaaS for tour & activity operators (WhatsApp → QRIS deposit → day roster).

Placeholder brand until marketing locks the final name.

## Stack

Plain HTML + CSS. No build step. UX oriented to [UXDT guidelines](https://www.uxdt.nic.in/guidelines/) (mobile-first, task-oriented CTAs, a11y basics).

## Design tokens

CSS variables in `styles.css` (`:root`) — colors, type, spacing, `--tap-min` (48px). Reuse the same names in the Rails app later.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing (hero CTA above fold, problem, offer, proof, CTA) |
| `styles.css` | Tokens + layout |
| `README.md` | This file |

## Run locally

```bash
python3 -m http.server 8080
```

Visit http://localhost:8080

Live: https://mnsbr.github.io/bali-web-landing/

## Edit copy / brand

Search `HariOps`, `6200000000000`, and `hariops.example` in `index.html`.
