# Mach 2 Marketing Website (Pass 3)

Static GitHub Pages marketing site for **Mach 2 Marketing** — **Marketing for Commercial Paving & Pavement Maintenance Contractors**.

## What's complete
- Core page set is in place with niche-specific copy and consistent navigation/footer structure.
- Primary CTA is standardized across the site: **Book Your Commercial Paving Visibility Audit**.
- Metadata has been improved across major pages (title, description, Open Graph basics).
- Footer contact placeholders are now clean, explicit launch placeholders (no raw token text).
- Proof and case study placeholders are intentionally phrased and non-fabricated.
- Contact and audit forms are structured and currently routed to `thank-you.html` for static-site flow.
- Legal pages are now presentable launch placeholders with clear legal-review notes.

## Repository structure
- `index.html` - Homepage
- `commercial-paving-marketing.html` - Industry page
- `services.html` - Services
- `commercial-paving-visibility-audit.html` - Audit page + intake form
- `case-studies.html` - Case-study/proof framework
- `pricing.html` - Engagement model
- `about.html` - Brand rationale and approach
- `contact.html` - Contact form
- `thank-you.html` - Submission confirmation page
- `404.html` - Not found page
- `privacy.html`, `terms.html` - Launch placeholder legal pages
- `assets/css/styles.css` - Styles
- `assets/js/site.js` - Mobile nav + FAQ behavior
- `assets/img/favicon-placeholder.png` - Temporary favicon asset

## Still required before public launch
1. **Contact details**
   - Replace footer placeholders with approved business email/phone on all pages.
2. **Proof assets**
   - Add approved testimonials, logos, screenshots, and before/after examples.
3. **Form backend**
   - Connect audit/contact forms to a real form processor or CRM endpoint.
4. **Domain and schema**
   - Replace placeholder domain/schema values (e.g., `https://example.com`) with final production domain.
5. **Brand assets**
   - Replace favicon placeholder with final brand favicon.
6. **Legal review**
   - Replace placeholder `privacy.html` and `terms.html` with attorney-approved legal text.

## Local preview
```bash
python -m http.server 8080
```
Then open: `http://localhost:8080`

## GitHub Pages deployment
1. Push to the publishing branch.
2. Ensure GitHub Pages is configured to deploy from GitHub Actions.
3. Confirm custom domain settings only after final production domain is available.

## Final launch checklist
- [ ] Approved contact details inserted sitewide
- [ ] Approved proof assets inserted sitewide
- [ ] Forms connected to live backend/CRM
- [ ] Final production domain updated in metadata/schema
- [ ] Favicon and any placeholder imagery replaced
- [ ] Legal pages replaced with attorney-approved copy
- [ ] End-to-end QA pass on mobile and desktop
