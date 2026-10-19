# Omegatech
A tech company that cares about your health
# OmegaTech website

Single static file (`index.html`), no build step. Works on GitHub Pages with relative paths.

## Edit
All content is in the `CONFIG` object at the top of the `<script>`: contact emails, founder bio, budget (totals, percentages and bars recalculate), roadmap, FAQ, enquiry types.

## Deploy (GitHub Pages)
1. Replace `index.html` in the `omega-foodtech-landing` repo (keep `FB_IMG_1741348426257.jpg` beside it).
2. Commit and push to the branch Pages serves (Settings > Pages).
3. Open https://mariahdi12.github.io/omega-foodtech-landing/

## Enable forms
Create a free form endpoint (e.g. Formspree), then set `CONFIG.formEndpoint` to its URL. Until then the form shows an honest "not configured" message with a mailto fallback.

## Pre-launch checklist
- Confirm contact emails; set the form endpoint and send a real test.
- Get lawyer review of the investor wording, privacy notice and fundraising approach.
- Add real investor documents only when they exist (none are linked now).
- Add `og:image`, `canonical` URL, `sitemap.xml` and `robots.txt` once the final domain is known.
- Run Lighthouse and test on real phones.
