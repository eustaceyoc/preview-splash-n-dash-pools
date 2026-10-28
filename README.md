# Splash n Dash Pools (sample site)

A sample website I designed for Splash n Dash Pools, a pool cleaning and repair company in Sacramento, CA. I put together sites like this to show local businesses what a modern, mobile-friendly web presence could look like for them before they commit to anything.

**Live preview:** https://preview-splash-n-dash-pools.vercel.app

## Design

A refined, editorial take on a local pool-service site. It sits on warm stone with deep teal and lagoon accents, uses Instrument Serif for headlines and Figtree for text, and has an arch-masked hero photo, a services accordion, a dark section for the business's Nextdoor record, a photo band, a review slider and a validated contact form. I dropped the retro look from my first version because it felt too playful for a service people trust with their home.

## Stack

- Plain HTML and CSS in a single `index.html`, with no framework and no build step
- Vanilla JavaScript (no libraries) for the sticky shrinking header, mobile menu, scroll reveals, subtle parallax, services accordion, review slider, an animated counter for a number sourced from Nextdoor, and client-side form validation. It respects `prefers-reduced-motion`
- Responsive layout, checked at 375, 768 and 1280 px
- Fonts and images: Instrument Serif and Figtree, plus two stock photos from Unsplash (by Zhen Yao and Luis Redondo, credited on the page)
- Hosted on Vercel

## Running it locally

Open `index.html` in a browser, or serve the folder with something like `npx serve .`

## Notes

- This is a sample site, not the business's official website, and it isn't affiliated with or published by Splash n Dash Pools.
- The contact form is for demo purposes only and doesn't send anything.
- Search engines are blocked for now (`robots.txt` and a `noindex` header in `vercel.json`) until the business decides whether it wants the site live.

Built by Eustace Crentsil
