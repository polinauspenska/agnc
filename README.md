# PROBLEMA website (landing page)

Single-page site: open `index.html` in a browser. No build step.

Live preview: https://claude.ai/artifact/GtqnvEJcN3FDYd4ioP8GS1

## Files
- `index.html`  all HTML, CSS and JS (CSS is in the <style> block, JS at the bottom)
- `assets/logo-wordmark.png`  wordmark only (header, footer)
- `assets/logo-full.png`  logo with "Marketing Agency" line
- `assets/hero.jpg`  recoloured banner photo (1800 px wide)
- `source/`  original logo, original hero photo, palette card

## Brand colours
- Burgundy  #65031E  (hero, loading screen)
- Rosewood  #6B0B0C  (closing section, menu)
- Coffee Bean  #2D120D  (text, dark sections)
- Botticelli  #CDE3E8  (light blue sections, accents)
- Cream  #F8F7D0  (light background, text on dark)

## Fonts (Google Fonts)
- Headings: Schibsted Grotesk (stand-in for Telegraf, which is a paid font; CSS asks for 'Telegraf' first)
- Body: Inter

## Page sections (in order)
Hero, Why Problema, What we do, What we solve (accordion), Method, Who we work with, Closing/contact, Footer.
Fullscreen menu opens from the "Menu" button.

## To do before launch
- Replace placeholder email `hello@problema.ae` (closing section) with the real one
- Add phone/WhatsApp and social links (footer has none yet)
- Add real case studies / results if wanted
- Swap hero photo for a higher-resolution original (current one is upscaled from a small image)
- Licence check for the hero photo
- Optional: real Telegraf font files, add via @font-face

## Notes
- Automatic dark mode was removed on purpose (fixed palette).
- Page title/description meta are in <head>.
