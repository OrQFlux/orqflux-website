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

## Deploy

### GitHub Pages (recommended, free)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch → main → / (root)**
4. Your site is live at `https://<username>.github.io/<repo-name>/`

For a custom domain (e.g. `orqflux.io`):
- Add a `CNAME` file containing your domain (already included)
- Point your DNS: `A` records to GitHub Pages IPs, or a `CNAME` record to `<username>.github.io`

### Netlify (alternative)

1. Drag-and-drop this folder at [netlify.com/drop](https://netlify.com/drop)
2. Or connect the GitHub repo at netlify.com → "Add new site"
3. Build command: *(leave empty)*  
4. Publish directory: `/` (root)

### Vercel (alternative)

```bash
npx vercel --prod
```
No config needed — Vercel auto-detects static HTML.

## Customisation

### Book a demo link
Search for `calendar.google.com/calendar/u/0/r?pli=1` across all files and replace with your actual Google Calendar appointment scheduling link.

### Contact email
Search for `hello@orqflux.io` and `support@orqflux.io` and replace with your real addresses.

### Company details
- `about.html` — team names, bios, and founding story
- `contact.html` — HQ location and contact details
- All footers — © year and legal links

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
