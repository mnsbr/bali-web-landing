# HariOps landing

Static product landing for **HariOps** (placeholder brand) — Indonesia tour/activity operator tool: WhatsApp → QRIS deposit → day roster.

Live: https://mnsbr.github.io/bali-web-landing/

## Stack

Plain HTML + CSS. See `DESIGN.md` (anti-slop rules + project tokens).

## CTA policy

Until self-serve signup exists, primary CTA is **Chat WhatsApp** (waitlist). No fake “Start free”. Email/mailto hidden until Kris provides a real address.

## Run

```bash
python3 -m http.server 8080
```

## Edit contacts

Search `6200000000000` in `index.html` when the real WhatsApp number lands.
