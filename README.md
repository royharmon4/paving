# Mach 2 Marketing Website (Pass 1)

Static, GitHub Pages-ready marketing site scaffold for **Mach 2 Marketing**.

## Project structure
- `index.html` - Homepage
- `commercial-paving-marketing.html` - Industry page
- `services.html` - Services
- `commercial-paving-visibility-audit.html` - Audit landing page
- `case-studies.html` - Case studies architecture
- `pricing.html` - Pricing/engagement
- `about.html` - About
- `contact.html` - Contact
- `thank-you.html` - Thank-you page
- `404.html` - Not found page
- `privacy.html`, `terms.html` - legal placeholders
- `assets/css/styles.css` - visual system, layout, component styles
- `assets/js/site.js` - mobile nav + FAQ interactions
- `.github/workflows/pages.yml` - GitHub Pages deployment workflow

## Editing copy in Pass 2
Primary editable content is directly in each HTML page. Search for `[PLACEHOLDER]` to find high-priority copy and media replacements.

### Replace first
1. Homepage proof section and hero image placeholder
2. Audit page proof block and FAQ copy
3. Case studies placeholders with verified outcomes
4. Contact details and legal pages

## Local preview
Open `index.html` directly in browser, or run a local static server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to GitHub Pages
1. Push to the `main` branch.
2. In GitHub repo settings, enable **Pages** with **GitHub Actions** as source.
3. Workflow `.github/workflows/pages.yml` publishes the full static site.

## Pass 2 focus
- Final conversion copy and CTA tuning
- Real imagery and proof assets
- Legal/privacy terms
- Analytics + event tracking
- Final SEO polish and schema expansion
