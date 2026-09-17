# HariOps landing — design rules

Anti-slop baseline: https://github.com/febbhav/signs-of-ai-design

## Tokens (Arky Week 1)

| Token | Value | Use |
|-------|-------|-----|
| `--bg` | `#F7F4EF` | Light paper marketing background (aligned with Rails) |
| `--accent` | `#F59E0B` | Amber — links, emphasis, secondary UI (not paid) |
| `--wa` | `#25D366` | WhatsApp CTA **only** |
| `--success` / `--color-success` | `#22C55E` | Lunas / paid chips |
| `--warn` / `--color-warn` | `#EAB308` | Menunggu / unpaid |
| `--danger` | `#EF4444` | Errors |
| Spacing | 8pt grid | 8 / 16 / 24 / 32 / 40 / 48 |

## Type

- **Sora** — H1 / H2
- **IBM Plex Sans** — body / UI
- **IBM Plex Mono** — IDR amounts

Do not default to Inter, Geist, or Space Grotesk.

## CTA honesty

- Until self-serve signup exists: **no** “Coba gratis” / “Start free”.
- Primary: Chat WhatsApp with a **real** number, or a disabled “WhatsApp segera” state — never a fake `wa.me` that looks live.
- Secondary: jump to `#offer` (“Lihat alurnya”).
- Hide mailto until a real email exists.

## NEVER-DO

- Mint/teal `#2DD4A8` glow aesthetic on this brand pass
- Painting paid chips with accent amber
- Fake logos, testimonials, or user counts
- Centered gradient-orb “Get Started” hero template
- Broken mailto forms

## Motion

One easing curve, 150–240ms. Prefer CTA hover + light hero fade. Honor `prefers-reduced-motion: reduce`.


## Marketing vs app

Landing Pages and Rails app both use light paper chrome. Amber accent + WA green CTA only.
