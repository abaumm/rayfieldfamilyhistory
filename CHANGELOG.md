# Rayfield Family History — Site Changelog

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
