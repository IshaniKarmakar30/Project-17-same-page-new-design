# Project-17-same-page-new-design
## Project Overview
This project demonstrates how applying core UI/UX design principles completely transforms a basic web page without modifying any textual content or copy.

- **Source File**: `before.html` (Standard unstyled baseline)
- **Redesigned File**: `after.html` (Polished layout using modern UI principles)

## 3 Core Design Changes & Why They Help

1. **Visual Hierarchy & Typography Scaling:**
   - *Change:* Replaced system default Arial with the modern geometric font `Plus Jakarta Sans`, using clamp-based fluid font sizing (`clamp(2.5rem, 6vw, 4.25rem)`) and subtle gradient fills on headings.
   - *Why it helps:* Draws immediate attention to the main event title and gives the page an authoritative, premium feel, preventing cognitive fatigue.

2. **Spacing, Depth & Modern Dark Surface System:**
   - *Change:* Transitioned from a flat grey background to a dark canvas (`#090d16`) with translucent glass cards (`rgba(255, 255, 255, 0.04)`), soft radial glow, and refined padding.
   - *Why it helps:* Enhances content legibility, provides breathing room between blocks, and reduces harsh contrast for users in low-light environments.

3. **Responsive Grid & Micro-Interactions:**
   - *Change:* Replaced static linear block cards with a CSS Grid layout (`repeat(auto-fit, minmax(300px, 1fr))`) coupled with subtle translateY hover lifts and interactive CTA glow.
   - *Why it helps:* The cards automatically adapt smoothly across mobile and desktop screens while tactile hover states clearly communicate clickability and affordance.

## Done Checklist
- [x] Both `before.html` and `after.html` exist
- [x] Text and wording in both files are 100% identical
- [x] Fully responsive across mobile, tablet, and desktop
- [x] 3 clear design rationales documented
