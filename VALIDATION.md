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

Rubric and layout revision, October 19, 2026 (second review):

- Read Canvas requirements and full 50-point rubric directly. Found and removed prohibited width media queries; only prefers-reduced-motion remains.
- Static HTML/CSS preview runs locally without a build tool. Grid uses available width to switch columns, with source text before images on mobile.
- All first photo groups now on the right on desktop. Single-image columns enlarged to half the content area; images capped at 25rem high.
- Partner choice uses separated topic/recommendation rows. Footer focus contrast improved. Image filenames normalized to lowercase.
- W3C Nu: all four HTML files returned an empty messages list.
- Chrome at 390px: all four document widths equal 390px and every content image loads; first text precedes its photos.
- WAVE and axe screenshots remain outstanding; no claim of full rubric compliance or guaranteed full marks.
- Production release remains pending user approval.

Partner links and submission preparation, October 19, 2026:

- Partner comparison now links to Ginsberg, C-SEED, and U-M Library instruction/support; destinations match the existing resource sections.
- Each main element is programmatically focusable via tabindex=-1 for the skip link. It does not create an extra Tab stop.
- Latest four HTML pages revalidated with W3C Nu: no messages. Referenced image paths match Git-tracked case-sensitive filenames.
- Updated only filled template answers in the original writeup; retained original prompts, styles, and cost table. Rendered all five pages and inspected them. Template table pagination retained to honor format preservation.
- WAVE/axe and personal time/cost entries intentionally left to the user.

Publication, October 19, 2026:

- User approved deployment. Published db77fff to main and verified four live HTML pages plus style.css match accepted local files exactly.
- Local submission document updated with supplied date, contact information, seven work-hour entries, 11-hour total, and $1,210 total. All five rendered pages visually inspected.
- No new WAVE/axe screenshots provided; Appendix A remains pending and accessibility prose accurately reflects that status.
