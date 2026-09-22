# Alex Morgan — Portfolio

A modern, single-page portfolio website with a dark, developer-focused aesthetic.

## Sections
- **Hero** — name, role, tagline, CTAs, animated code card
- **Skills** — grouped by category (Frontend, Backend, Cloud, Tools)
- **Experience** — vertical timeline of roles
- **Projects** — card grid with gradient thumbnails
- **Contact** — client-side form (wire to Formspree/EmailJS for real submissions)

## Tech
- Pure HTML, CSS, and vanilla JavaScript — no build step, no dependencies
- Google Fonts (Inter + JetBrains Mono)
- Fully responsive (mobile, tablet, desktop)
- Accessible (semantic HTML, ARIA labels, keyboard-friendly)

## Customize
All content is placeholder. Replace:
- Name, role, tagline in `index.html` (hero section)
- Skills in the `#skills` section
- Experience entries in the `#experience` timeline
- Project cards in the `#projects` grid
- Social links and email in the hero + contact sections

## Deploy
Static site — deployable to Vercel, Netlify, GitHub Pages, or any static host.

## Local preview
Open `index.html` in a browser, or run:
```
python -m http.server 8000
```
