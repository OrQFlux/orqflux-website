# OrqFlux — Product Website

Static HTML/CSS/JS website for OrqFlux. No build step required.

## Pages

| File | URL |
|------|-----|
| `index.html` | `/` — Main landing page |
| `about.html` | `/about` — Company, team, values |
| `blog.html` | `/blog` — Article listing |
| `careers.html` | `/careers` — Careers page |
| `contact.html` | `/contact` — Contact / message form |

## Structure

```
orqflux/
├── index.html       # Landing page (hero, features, journeys, analytics, integrations, FAQ)
├── about.html       # About page (story, mission, values, team)
├── blog.html        # Blog listing page
├── careers.html     # Careers page (no open roles)
├── contact.html     # Contact / message form
├── CNAME            # Custom domain (edit before deploying)
├── .nojekyll        # Disables Jekyll on GitHub Pages
└── README.md        # This file
```

## No dependencies

Pure HTML, CSS, and vanilla JavaScript. No npm, no bundler, no framework.
Google Fonts loaded from CDN (`fonts.googleapis.com`).
