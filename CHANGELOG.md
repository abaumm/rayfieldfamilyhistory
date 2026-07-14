# Rayfield Family History — Site Changelog

---

## 2026-07-14 — New Blog section added

### Added
- **`blog.html`** — new blog listing page, matching the site's card-grid design system (page-banner header + post cards). Currently lists one post, with a placeholder card for "more stories coming soon."
- **`blog-wagon-maker-of-des-arc.html`** — first blog post, the full text of "The Wagon Maker of Des Arc" (John Wesley Robinson), originally published in the Wayne County Journal Banner, June 29, 2026. Byline Andrea Harter; credit line to the original publication included. Cross-links to `profile-john-wesley-robinson.html`.
- **Nav + footer updated site-wide** — "Blog" link added to the main nav and footer on all 14 existing pages (between Ancestor Map and Contact), so the new section is reachable from anywhere on the site.
- **Homepage (`index.html`)** — new "Blog" card added to the "What's Here" site guide grid, linking to `blog.html`.
- **Profile page (`profile-john-wesley-robinson.html`)** — added a cross-link from the intro callout to the new blog post.

### Rationale
Andrea wants a place for shorter, focused narratives (by person or by place, e.g. Des Arc) separate from the full book chapters, plus a home for outside-published work like the Journal Banner piece. Rights to republish the full article text were confirmed clear (no written agreement existed with the paper; author retains copyright by default) before posting.

---

## 2026-07-04 (later same day) — Cut Family Members page; promoted the Family Tree from draft to live

Andrea decided to retire the Family Members / name index page and finish integrating the two family-tree visuals that had been sitting as unlinked drafts. All fixed locally; nothing pushed to origin yet.

### Removed
- **`name-index.html` deleted.** It was a static, unlinked-within-itself search table of 96 names with no connections out to profile pages or book chapters — effectively a dead end that duplicated the book's back-matter "Line" section. Andrea confirmed cutting it in favor of simpler upkeep.

### Promoted family-tree-draft.html → family-tree.html
- The old 4-generation `family-tree.html` (superseded) was replaced with the content of `family-tree-draft.html` — the current 8-generation, zoomable, cross-linked-to-profiles ancestor chart. The old draft file is gone; `family-tree.html` is now the one canonical URL.
- Added a footer (previously missing) matching the rest of the site.
- Added a cross-link near the header to the new convergence chart.

### Promoted family-tree-convergence-draft.html → family-tree-convergence.html
- Renamed to drop the "-draft" suffix now that it's live. Content unchanged (the six-family convergence diagram, already polished and profile-linked).
- Nav updated to the current 6-item standard (previous draft nav was missing "Pioneer Families," a page added after this draft was created).
- Added a footer (previously missing) and a link back to the ancestor chart, plus a link to Pioneer Families.

### Site-wide nav/footer update (13 files: index, the-rayfield-story, pioneer-families, contact, ancestor-map, all 8 profile pages)
- Replaced the "Family Members" nav/footer item with "Family Tree" (→ `family-tree.html`) everywhere, in the same list position.

### index.html
- "Family Members" homepage section retitled "Meet the Family"; its "Search All Members" button (→ name-index.html) replaced with "View the Family Tree" (→ family-tree.html). The profile-card grid itself is unchanged.
- "Family Members" card in the Site Guide grid replaced with a "Family Tree" card.

### the-rayfield-story.html
- "A Note on the Families" callout (back matter, mirrors the print book's "The Line" section) now also links to `family-tree.html` and `family-tree-convergence.html`, alongside the existing Pioneer Families link.

### pioneer-families.html
- Added a line under "Six pioneer families, one marriage" linking to the new convergence chart, since that page visualizes exactly what that section describes in prose.

---

## 2026-07-04 — Full site review + fixes: Jerusha/NC line sync, Wagon Factory restored, Eddy Pratt policy update, contradiction cleanup, stale chapter numbers, broken links

A full read-through of every page found several gaps against the print book and several site-only bugs. All fixed locally; nothing pushed to origin yet.

### the-rayfield-story.html
- **Chapter One synced to print v34:** Isaac Rayfield's "unnamed first wife" is now named Jerusha (1826 Cumberland Co., KY deed, ARN0000299), with the hedge that she isn't proven to be the mother of his oldest children. NC paternal line enriched: 1757 will citation supplemented with the original manuscript image (ARN0000297/297b); new sentence on Isaac likely being named for his maternal grandfather Isaac Meekins (1760 will, ARN0000298); new credit sentence for genealogist Eddy Pratt's *The Rayfield Record* (see Pratt policy below). New citations cite-137–140 added to the Sources list and back-matter prose.
- **Restored the missing "Wagon Factory" section in Chapter Seven** (~600 words on J.W. Robinson's wagon-making business, 1909–1928) — this was added to the print book June 28 but never made it to the web version. Inserted between "The Blacksmith's Shop" and "The Casket Maker," matching print placement exactly. New citations cite-141–151 (ARN0000257–267).
- **Eddy Pratt policy update:** per Andrea's July 4 clarification, Pratt's fuller work, *The Rayfield Record* (2008), is independently public via the FamilySearch Digital Library, so his name and that title may be cited. (Andrea's private excerpt copy, "Excerpts of Rayfield Report by Eddy Pratt.PDF"/ARN0000106–107, and any link to its ARN record, remain off-limits everywhere.) Restored his name in three places that had been softened to "an independent reconstruction," correcting the citation from the excerpt's internal title ("The Tidewater North Carolina Rayfields," 2014 — an incorrect date/title, since that's the private excerpt) to *The Rayfield Record* (2008).
- **Contradiction fixes:** Benjamin F. Seal's death date (footnote said November 1941; main narrative already said 1944 — footnote corrected to November 21, 1944). Franklin & Myrtle's children (footnote/census-card still listed Harmon and Glenn E. as their children, contradicting the "five children" narrative elsewhere in the same file — footnotes corrected; Harmon's presence in the 1920 census household is noted but flagged as not their child).

### profile-john-carter-rayfield.html
- Ancestral Line Records table: added rows for ARN0000297 (1757 will, image) and ARN0000298 (1760 Meekins will). Corrected the "Isaac Rayfield & Betsy Stop, 1816" marriage row — that marriage belongs to Isaac Jr. (son), not Isaac Sr., corrected here with a note; added a row for ARN0000299 (Jerusha, Isaac Sr.'s actual documented wife).

### name-index.html
- Eddy Pratt entry updated to cite *The Rayfield Record* (2008) instead of an unsourced "2014 reconstruction."
- Corrected the "Betsy Stop" entry (wife of Isaac Jr., not Sr.) and added a new "Jerusha Rayfield" entry (Isaac Sr.'s wife).
- Removed "Glenn E. Rayfield" and "Harmon Rayfield" entries — not children of Franklin & Myrtle.
- Fixed a duplicated "Pioneer Families" footer link and added the missing "Pioneer Families" link to the top nav (it was already in the footer).

### family-tree-draft.html
- Isaac Rayfield's wife updated from "Unknown / name not recorded" to Jerusha, with the hedge noted.

### profile-franklin-myrtle-rayfield.html
- Children table and 1920-census card corrected to five children (Jesse, Bessie/"Betty," Vernon, Elmo, Imogene Inez); Harmon and Glenn E. removed/flagged as not their children.
- Chapter reference corrected 2 → 4.

### profile-absalom-robinson.html, profile-john-carter-rayfield-jr.html, profile-john-wesley-robinson.html, profile-lucian-farris.html, profile-vernon-opal-rayfield.html, profile-william-lewis.html
- Chapter references corrected to match the June 29 8-chapter renumbering (Absalom 4→6, JCR Jr. 2→4, JW Robinson 5→7, Vernon & Opal 6→8, William Lewis 3→5; added a missing chapter reference to the Lucian Farris page, Chapter Three).
- Fixed broken links on profile-john-carter-rayfield-jr.html and profile-lucian-farris.html pointing to a nonexistent "The Rayfields - A Family History - cited.html" — corrected to the-rayfield-story.html (3 occurrences total).
- Fixed a structural bug on profile-absalom-robinson.html: a "Connections to Other Profiles" block had been left sitting after the closing `</html>` tag (outside the document) — moved inside, before `</body></html>`.

### index.html
- Fixed three "Founding Families" homepage cards linking to a nonexistent founding-families.html — repointed to the relevant chapter anchors on the-rayfield-story.html (Rayfield & Mann → Chapter One, Farris & Seal → Chapter Three, Lewis & Robinson → Chapter Five).

### pioneer-families.html
- Fixed a misplaced citation (cite-37, the Seal first-cousin tie) that had been sitting inside the site footer's navigation list instead of the citations list — moved to the correct place; removed the stray footer duplicate.

### Not done (flagged, not fixed)
- family-tree-convergence-draft.html is a polished, unpublished, unlinked draft with the chapter numbering already correct — a good candidate to finish and use to replace family-tree.html/family-tree-draft.html, but not touched this pass.

### profile-john-carter-rayfield-jr.html, profile-lucian-farris.html — migrated to the 2026-06-23 visual redesign (follow-up fix, later same day)
- Both pages were created June 23, 2026 (the same day as the visual redesign) but never switched over to it — flagged above, now fixed.
- Added the shared `style.css` link, the fixed navy nav bar (with mobile hamburger toggle) and shared footer used by the other 6 profile pages; swapped the old inline tan/brown palette for the shared navy/gold tokens; added the responsive-table rule for mobile.
- Removed the old standalone `<p class="back-link">` header (matching how the other 6 profiles handle navigation — via the shared nav only); preserved the cross-profile links (JCR Jr. ↔ JCR Sr., JCR Jr. ↔ Lucian Farris) inside each page's own footer paragraph instead.
- No body content changed — same facts, tables, and prose as before.

---

## 2026-07-02 — Web book synced to print manuscript v32

Brought the public web edition into line with the current print book (v32). Same content as print, with two deliberate differences: sensitive living-person details are scrubbed, and the web keeps its own inline ARN-linked citation style (not the print endnotes).

### the-rayfield-story.html
- **Two chapters added** and everything renumbered 6 → 8 chapters:
  - New **Chapter Two — The Farmer's Son: John Carter Rayfield Jr. & Nancy Ann Farris** (includes the documented 1880 Lamar County, Texas residence and the Samuel-born-in-Texas resolution)
  - New **Chapter Three — Before the County Had a Name: Lucian Nester Farris** (includes the Fold3/NARA M345 Union Provost Marshal record)
  - Franklin & Myrtle → Ch. 4; Uncle Billy → Ch. 5; Absalom → Ch. 6; JW & Katie → Ch. 7; Vernon & Opal → Ch. 8
  - Updated Contents list, sidebar nav, chapter anchors; added inline citations [125]–[136]
- **Factual corrections from v32:** Benjamin F. Seal death corrected to **Nov 21, 1944** (was 1941; "span of ten months" passage rewritten); **Seal cousins resolved** (John Polk & Benjamin were brothers → Everett and Myrtle first cousins); Clearwater land acquisition grounded in the **Flood Control Act of 1938**
- **Privacy scrub (public edition):** generalized "Andrea's office" and a Chicago street address; rewrote the "What the DNA Tells Us" back matter to remove living relatives' named autosomal-ethnicity figures and the private DNA-match name (kept the deep-ancestry haplogroup material)
- **Eddy Pratt:** removed his private report and correspondence from the public Sources; cited the primary colonial records directly; softened allusions so his name does not appear publicly (pending his permission to restore it)
- **Removed "A Note on This Book"** (print-only)

### index.html
- Homepage "chapter by chapter" list updated to the 8-chapter order; "The Blacksmith of Des Arc" title corrected to **"The Wagon Maker of Des Arc"**

### pioneer-families.html
- Benjamin F. Seal lineage date corrected 1941 → **1944**
- Seals section: added the resolved **first-cousin tie** (John Polk Seal, brother of Benjamin; Everett Seal ↔ Myrtle first cousins) with new citation [37]
- Clearwater passage grounded in the **Flood Control Act of 1938**

### profile-franklin-myrtle-rayfield.html
- Benjamin F. Seal death corrected `21 Nov 1941` → `21 Nov 1944`

> Restore note for the Pratt content lives in `../PRATT WEB CONTENT - removed (restore pending Eddy approval).md`.

---

## 2026-06-23 — Full Visual Redesign (v2)

### New design system
- Added `style.css` as a shared stylesheet across all pages
- Color palette: dark navy `#002C3D` + gold `#D6A15D` replacing tan/brown heritage aesthetic
- Typography: Cormorant Garamond (headings/display) + Inter (body), via Google Fonts
- All rem units for accessibility; WCAG AA contrast ratios verified throughout
- Fixed nav bar (dark navy, blur backdrop) with mobile hamburger toggle
- Shared footer with dark navy background

### Homepage (index.html) — rebuilt from scratch
- Old homepage (the book) moved to `the-rayfield-story.html`
- New landing page with full-width NPS hero image (Missouri Ozarks, Big Spring)
- Alternating cream/dark section rhythm: Intro → Quote → Book feature → Family Members → Timeline → Site Guide → Footer
- Compact 4-per-row family member cards with square-cropped portrait photos
- Quote band with Laura Ingalls Wilder or selected quote (TBD)
- "Site Guide / What's Here" section orienting new visitors
- NPS photo credit shown in hero (public domain, credit: National Park Service)

### The Rayfield Story (the-rayfield-story.html) — restyled
- Renamed from `index.html` (old homepage was the book)
- Updated color tokens to new palette; sidebar restyled to dark navy
- Fonts updated to Cormorant Garamond/Inter; removed parchment/texture backgrounds

### Profile pages — restyled (6 pages)
- `profile-absalom-robinson.html`
- `profile-franklin-myrtle-rayfield.html`
- `profile-john-carter-rayfield.html`
- `profile-john-wesley-robinson.html`
- `profile-vernon-opal-rayfield.html`
- `profile-william-lewis.html`
- All updated: color tokens, fonts, sidebar to navy, cream content backgrounds
- Fixed broken back-link: `The Rayfields - A Family History - cited.html` → `the-rayfield-story.html`

### Name Index (name-index.html) — restyled
- Color tokens updated, sidebar to navy, filter buttons updated to new palette
- Fixed broken link to cited.html
- Search/filter/table UI preserved

### Ancestor Map (ancestor-map.html) — restyled
- Page header banner updated from sepia brown to navy
- Color tokens updated to new palette
- Map itself unchanged (Leaflet.js + OpenStreetMap, no Google Maps dependency)

### Contact
- All mailto links updated to `abaumm+rayfieldfamilyhistory@gmail.com` for site-specific email tracking
- Contact shown as link only (email address not displayed on page)

### Bug fixes
- Resolved `.git/index.lock` file from sandbox operations (manual delete)
- Removed empty `media/nps-ozark-hills.jpg` artifact from failed download attempt (manual delete)
- Removed stray browser-saved files from repo (`Photo 1 Ozark Scenery...html`, `_files/`, screenshot jpg)

### 2026-06-23 (follow-up)
- Swapped Leaflet/OpenStreetMap map for Google My Maps iframe embed (map ID: `1EqCmzT8wwo7TUnCN6rG2Jc1lpeUg9TIH`)
  - Leaflet polygons (Clearwater Lake outline) were inaccurate; pins were approximate hardcoded coordinates
  - Google My Maps is now the source of truth — updates to the map appear automatically on site
  - Sidebar repurposed from JS-driven "Jump To" buttons to static location reference panel
- Updated all `mailto:` links site-wide to `abaumm+rayfieldfamilyhistory@gmail.com` for email tracking
- Updated quote to Alex Haley: "In every conceivable manner, the family is link to our past, bridge to our future."
- Created CHANGELOG.md

---

## Pre-2026 — Original site (v1)

- Static HTML site on GitHub Pages at custom domain
- Single-page book format: full narrative on homepage
- Tan/brown heritage aesthetic; Georgia serif throughout
- Profile pages, name index, Leaflet ancestor map
- No shared stylesheet; per-page inline CSS
