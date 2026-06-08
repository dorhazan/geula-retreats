# Geula Retreats

A bilingual (Hebrew/English) marketing site for **Geula Retreats** — a Tel Aviv-based surf retreat company running trips to Bali, Panama, El Salvador, and Siargao.

**Live:** [geula-retreats.com](https://geula-retreats.com)

## Highlights

- **Bilingual RTL/LTR** — full Hebrew & English content driven by an in-page i18n dictionary, with automatic `dir` switching.
- **Lightweight single-file build** — vanilla HTML/CSS/JS, no framework, no build step. Fast on mobile.
- **Mobile-first responsive design** — hamburger nav, click-to-fullscreen gallery, scroll-snap slider, lightbox grid.
- **Accessibility widget (IL Standard 5568, AA)** — font sizing, contrast, grayscale, motion-reduction, link emphasis.
- **PDF & "Coming Soon" modals** for destination brochures.
- **WhatsApp deep links** for booking CTAs.

## Stack

- HTML5 · CSS3 (custom properties, grid, flex) · Vanilla JS
- Google Fonts (Rubik)
- Deployed on **Vercel**

## Local development

```bash
# clone
git clone https://github.com/dorhazan/geula-retreats.git
cd geula-retreats

# open directly — no build step
start index.html        # Windows
open  index.html        # macOS
```

## Project structure

```
landing-page/
├── index.html      # entire site (CSS + JS inline)
├── images/         # photography & brand assets
└── docs/           # destination brochures (PDF)
```

## Deploy

Vercel-linked. Production deploys via:

```bash
vercel --prod
```

---

Built by [Dor Hazan](https://github.com/dorhazan) for Geula Retreats.
