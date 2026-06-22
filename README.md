# KP Concrete & Design — Website

A modern, responsive marketing site for [KP Concrete & Design](https://www.kp-concrete.com/), Colorado's concrete experts (Denver metro area).

## What's here

- **`index.html`** — the full single-page site (semantic, accessible markup)
- **`styles.css`** — all styling (CSS custom properties, fully responsive)
- **`images/`** — project photos

## Features

- Sticky navigation with click-to-call and a persistent "Free Quote" CTA
- Hero with trust badges
- Services overview
- **Filterable project gallery** (Concrete / Decorative & Stamped / Pavers & Stonework)
- **Financing section with a live monthly-payment calculator**
- Service-area grid
- Real 5-star Google reviews with links to the Google profile
- Quote request form (front-end; wire up to a backend or form service)

## Local preview

It's a static site — no build step. Serve the folder with any static server:

```bash
npx serve .
```

Then open the printed `localhost` URL.

## Deploy

Hosted on Vercel. Pushes to `main` auto-deploy once the repo is connected in the Vercel dashboard.

## To finish before going fully live

- Swap in full-resolution photos (current images are ~400px from the old site)
- Wire the quote form to a real backend (e.g. Formspree) or KP's existing quote system
- Confirm financing terms (APR/term options in the calculator are placeholders)
- Replace the Google Maps search link with KP's exact Google Business Profile URL
