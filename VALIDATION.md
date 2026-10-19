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

Accessibility evidence supplied, October 19, 2026:

- Added eight user-supplied screenshots to Appendix A, paired by page. The nine-page submission document was rendered and every page visually inspected.
- Axe screenshots identify all four live GitHub Pages URLs: 0 automatic issues, WCAG 2.1 AA, Best Practices off.
- WAVE screenshots show 0 errors and 0 contrast errors on all four pages. Home, Preparing, and Starting each have 1 redundant-link alert; Campus Partners has 3.
- The Starting WAVE screenshot visibly references 127.0.0.1:4173. Other WAVE screenshots lack visible page URLs. These are local or unconfirmed-address evidence, not confirmed live-site scans. Four live WAVE screenshots with visible URLs remain needed.
- Automated results do not establish manual accessibility compliance. Redundant-link alerts require review.
- Updated existing writeup answers using simple English. The repository document omits personal contact details; the local submission copy includes the supplied contacts, date, 11 hours, and $1,210 total.
- No website source changed in this evidence update; no new site deployment required.

Updated WAVE evidence, October 19, 2026, 00:30:

- Replaced all four previous WAVE screenshots with the user's new screenshots (00:30:17, 00:30:35, 00:30:42, 00:30:50). Counts are unchanged: 0 errors, 0 contrast errors, and 1/1/1/3 redundant-link alerts.
- Preparing screenshot shows a GitHub Pages hover link. Browser address bars are not included, so the exact current page URLs are not independently visible in these WAVE images. Removed the obsolete local-address statement about the replaced Starting screenshot.
- Appendix A retains the four live axe screenshots. Manual accessibility results have not been supplied.
- Updated submission and sanitized repository copies; website source unchanged.

Manual keyboard acceptance, October 19, 2026:

- User confirmed that all four pages passed the keyboard checklist provided in chat: skip link, logical Tab order, visible focus, Enter activation, reverse navigation with Shift+Tab, no keyboard traps, and accessible footer links.
- This is user-performed verification, not an additional agent-run test. It does not claim screen-reader testing or complete WCAG conformance.
- Updated both writeup copies to record the completed keyboard checks. Website source unchanged.

## October 19, 2026 — Writeup language revision
- Reviewed the student's actual previous Canvas submission and instructor feedback.
- Revised the five written answers and Appendix introduction with varied sentence lengths, common vocabulary, and clearer explanations of design choices.
- Preserved template wording and formatting, project facts, cost figures, and all eight accessibility screenshots. Public copy continues to omit personal contact details.
- Rendered the submission document and inspected all 10 pages. Restored the Appendix introduction's existing font formatting and inspected the changed page; the remaining nine rendered pages were identical.
- Documentation only; website source and deployment unchanged. No new accessibility scan is claimed.

## October 19, 2026 — Explicit response to first-deliverable feedback
- Added a paragraph at the end of the final written answer identifying the instructor's two concerns and the corresponding revisions: clearer links to client goals and explanations of accessibility features and their users.
- Preserved existing text, run formatting, template, costs, and screenshots.
- Rendered the updated 10-page document. Inspected changed pages 5 and 6; the other eight pages are pixel-identical to the previously inspected version. The original table retains its automatic page-break behavior.
- Documentation-only update; no deployment changes.

## October 19, 2026 — Small first-person wording adjustment
- Rephrased two sentences in the feedback paragraph to describe what I learned and how I explained my choices.
- Retained all other content and formatting. Rendered 10 pages; inspected changed pages 5 and 6, with the remaining eight identical to the reviewed version.

## October 19, 2026 — Light first-person revision
- Added a small amount of first-person wording across the five responses and Appendix introduction, using varied openings rather than consecutive sentences beginning with I.
- Preserved the template, contact handling, costs, and eight embedded screenshots.
- Rendered the 10-page submission and reviewed changed pages 2–6; the remaining pages match the prior reviewed render. No website changes.
