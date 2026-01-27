# Bouldern mit Kindern 🧗

SEO-optimized static website about bouldering with kids. Built with Astro and Tailwind CSS, deployed on GitHub Pages.

**Live:** [https://berndbot.github.io/boulder-mit-kindern/](https://berndbot.github.io/boulder-mit-kindern/)

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Homepage | `/` | Overview, hero section, teasers, FAQ |
| Ab welchem Alter? | `/ab-welchem-alter/` | Age guide for kids bouldering (2-13+) |
| Vorteile | `/vorteile/` | Benefits: motor skills, confidence, focus |
| Ausrüstung | `/ausruestung/` | Equipment guide: shoes, chalk, clothing |
| Tipps für Eltern | `/tipps-fuer-eltern/` | Parent tips: motivation, safety, mistakes |
| Boulderhallen finden | `/boulderhallen-finden/` | Finding kid-friendly bouldering gyms |
| Impressum | `/impressum/` | Legal notice |
| Datenschutz | `/datenschutz/` | Privacy policy |

## Tech Stack

- **Astro** – Static site generator
- **Tailwind CSS v4** – Utility-first CSS
- **@astrojs/sitemap** – Auto-generated sitemap
- **GitHub Pages** – Hosting via GitHub Actions

## Development

```bash
npm install
npm run dev     # Start dev server
npm run build   # Build static site
npm run preview # Preview build
```

## Deployment

Automatic deployment via GitHub Actions on push to `main`. The workflow builds the Astro site and deploys to GitHub Pages.

## SEO Features

- Semantic HTML with proper heading hierarchy (H1, H2, H3)
- Meta titles and descriptions for every page
- Open Graph and Twitter Card meta tags
- Schema.org JSON-LD markup (WebSite + Article)
- XML Sitemap (`/sitemap-index.xml`)
- robots.txt
- Internal linking between all content pages
- Breadcrumb navigation
- Responsive design (mobile-first)
- Canonical URLs
