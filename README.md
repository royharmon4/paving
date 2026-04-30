# Mach 2 Marketing Website (Pass 2)

Static, GitHub Pages-ready marketing site for **Mach 2 Marketing**.

## Project structure
- `index.html` - Homepage
- `commercial-paving-marketing.html` - Industry page
- `services.html` - Services
- `commercial-paving-visibility-audit.html` - Audit landing page
- `case-studies.html` - Case studies and teardown frameworks
- `pricing.html` - Pricing/engagement
- `about.html` - About
- `contact.html` - Contact
- `thank-you.html` - Thank-you page
- `404.html` - Not found page
- `privacy.html`, `terms.html` - intentional legal placeholders
- `assets/css/styles.css` - visual system, layout, component styles
- `assets/js/site.js` - mobile nav + FAQ interactions

## Pass 2 copy status
### Finalized launch copy
- Homepage positioning, hero, pain points, and FAQ
- Industry page messaging and niche fit narrative
- Services page (all former placeholder sections replaced)
- Commercial Paving Visibility Audit page (offer, fit, FAQ, and form guidance)
- Pricing, About, Contact, Thank-you, and 404 page messaging
- Metadata updates across primary pages

### Intentional placeholders kept for Pass 3
- Proof assets (client logos, testimonials, verified screenshots, before/after visuals)
- Contact details in footer (`[CONTACT PLACEHOLDER]` markers retained because no confirmed real details were provided in repo)
- Legal language in `privacy.html` and `terms.html` pending attorney-approved copy
- Hero/section imagery where placeholder blocks are still explicitly labeled

## Local preview
Open `index.html` directly in a browser, or run a local static server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to GitHub Pages
1. Push to the `main` branch.
2. In GitHub repo settings, enable **Pages** with **GitHub Actions** as source.
3. Existing GitHub Pages workflow publishes the static site.

## Pass 3 recommended follow-up
- Replace proof placeholders with approved real client evidence.
- Replace footer contact placeholders with confirmed business contact data.
- Add attorney-approved privacy and terms copy.
- Replace image placeholders with brand-approved photography/screenshots.
