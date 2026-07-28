# LZWORTH — Premium Rebuild (v2)

Single-file, dependency-free landing site for LZWORTH (AI automation agency).

## Files
- `index.html` — the whole site (HTML + CSS + JS inline)
- `logo.png` — your company logo (used in nav + footer, transparent background)
- `favicon.png` — browser tab icon
- `vercel.json` — hosting config + security headers
- `robots.txt`, `sitemap.xml` — SEO
- `.gitignore`

## What's new in v2
- **Your real logo** now appears in the nav and footer (with a subtle hover tilt).
- **Real social links wired in** — pulled from your site:
  - Instagram → instagram.com/lzworth.in
  - LinkedIn → linkedin.com/company/lzworth
  - YouTube → youtube.com/@lzworth
  - WhatsApp → wa.me/918826124463
  - Email → lzworth@gmail.com
  - Domain/canonical/schema updated to lzworth.in
- **Fake reviews removed.** Replaced with an honest "Our Promise" section (14-day guarantee, full ownership, transparent pricing) + a "See our work on Instagram" link. No invented testimonials.
- **New effects added:**
  - Custom cursor (dot + trailing ring, grows on hover, shrinks on click) — desktop only
  - Scroll-progress bar at the top of the page
  - Back-to-top button (appears after scrolling)
  - Parallax on the hero grid + aurora as you scroll
  - 3D tilt on the hero terminal when you move the mouse over it
  - Mouse-follow glow on agent + promise cards
  - (kept) scroll-reveal, number counters, magnetic buttons, sticky glass nav, marquee
- All effects respect `prefers-reduced-motion` and disable the custom cursor on touch devices.

## Deploy
Drop the whole folder on Vercel (or any static host). Keep all files together so the logo/favicon load.

## Optional next steps
- Add a real 1200×630 `og.png` share image (referenced in the head).
- When you have genuine client permission, real testimonials can go back in the Promise section's place.
