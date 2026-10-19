# Validation record

Validated on September 20, 2026.

- W3C Nu HTML Checker: 0 messages for `index.html`, `prep.html`, `starting.html`, and `campus-partners.html`.
- aXe WCAG A/AA audit: 0 violations for all four pages.
- Local structure check: every page has `header`, `nav`, `main`, `footer`, one `h1`, a `#main` target, working local links, and alternative text for every image.
- Browser smoke test: opened all four pages locally and clicked the shared navigation links successfully.
- Photo update: added six course-provided UMSI photographs with descriptive alternative text and captions, matched to the home, preparation, project-start, and campus-partner themes.

Visual review on October 18, 2026:

- Opened the home, preparation, project-start, and campus-partner pages in Chrome at a 1440px desktop viewport.
- Confirmed the home stage guidance cards have no images; short guidance and resource lists are plain sections; the long introductory and campus-partner explanations pair with supplied photos.
- Confirmed campus-partner photos alternate left and right across the three organization sections.
- Automated HTML, WAVE, and axe checks have not been rerun for this visual revision.

Photo sizing revision, October 18, 2026:

- Eight content photos are unique across all four pages; all local image files and alt text are present.
- Partner descriptions, usage lists, and links now share one text column with an alternating photo column.
- Desktop photos are capped at 24rem / 36% width and 17rem height, with compact mobile sizing.
- git diff --check passed. Current visual review could not run: sandbox blocked the local HTTP server; browser blocks file URLs.
- No production deployment performed; user review remains pending.

Photo and layout revision, October 19, 2026:

- Six user-supplied photos and two additional course-portal photos added; 16 unique content photos across four pages. The repeated navigation logo is excluded from this count.
- All image paths exist and all images have descriptive alt text. New photos resized to at most 1200 pixels.
- Desktop Chrome visual review covered all four pages. Paired introductory photos remain side by side; long content uses alternating image columns. Short resource lists remain cohesive text blocks.
- At 390px, all four pages have document width 390px and all content images load successfully. Mobile screenshots of starting and campus-partner pages inspected.
- No build step is needed for this static HTML/CSS website; latest files run on the local HTTP preview at port 4173.
- WAVE, axe, and external HTML validation have not been rerun for this revision.
- Production deployment is pending user acceptance of this preview, as requested.
