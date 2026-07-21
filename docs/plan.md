# Project Plan

This plan covers how I'm managing risk and sequencing the work for the Elsner App Development Services website prototype, per PMUPM Chapter 4.

---

## Risk Analysis (TAME)

For each risk, I identified it, rated its likelihood and impact, and picked a response using the TAME framework — **T**ransfer, **A**ccept, **M**itigate, or **E**liminate.

| # | Risk | Likelihood | Impact | Response | Plan |
|---|------|------------|--------|----------|------|
| 1 | I run out of time before the July 23 deadline because I underestimate how long the design/build takes | Medium | High | **Mitigate** | Keep the site to exactly two pages as scoped, build the docs first while the requirements are freshest, and treat the scope statement's exclusions as a hard boundary against adding "just one more thing" |
| 2 | CSS styling breaks or looks inconsistent between index.html and about.html | Medium | Medium | **Mitigate** | Build shared layout components (nav, footer, type scale) first in style.css before writing page-specific content, and test both pages side by side after every CSS change |
| 3 | The site doesn't display correctly across devices | Medium | Medium | **Mitigate** | Design mobile-first and check the layout at a few breakpoints before calling any page done, rather than treating responsiveness as a final pass |
| 4 | GitHub Pages deployment fails or the live link doesn't work | Low | High | **Mitigate** | Deploy early with placeholder content to confirm Pages is configured correctly, then iterate on real content — don't wait until the end to test deployment |
| 5 | The site overstates what Elsner App Development Services actually is (implying a real, operating business with clients) | Low | High | **Eliminate** | The scope statement's Exclusions section already rules this out; I'll review copy on both pages against that list before finalizing content and deploying |
| 6 | I lose work due to a bad save, accidental overwrite, or local file issue | Low | Medium | **Transfer** | Commit to GitHub regularly throughout the build instead of only at the end, so GitHub's version history absorbs this risk |
| 7 | I run low on time for the retrospective and rush through it | Medium | Low | **Accept** | This is a real but low-impact risk — if time gets tight near the deadline, I'll accept a more concise (but still honest) retrospective rather than let it compromise the site or docs |

---

## Work Breakdown Structure (WBS)

Deliverables broken into the tasks needed to complete each one.

### 1. Planning Documents
* 1.1 Finalize `scope.md` (incorporate Assignment 04 peer feedback)
* 1.2 Draft `plan.md`: TAME risk analysis
* 1.3 Draft `plan.md`: WBS task schedule
* 1.4 Write `retrospective.md` (after the build is complete)

### 2. Repository Setup
* 2.1 Create public GitHub repository
* 2.2 Set up folder structure
* 2.3 Enable GitHub Pages on the repository
* 2.4 Confirm the live Pages link works with placeholder content

### 3. Homepage (index.html)
* 3.1 Structure the page (header/nav, hero, key sections, footer)
* 3.2 Write homepage content introducing Elsner App Development Services
* 3.3 Link to about.html from the homepage navigation
* 3.4 Apply and test styling from style.css

### 4. About Page (about.html)
* 4.1 Structure the page
* 4.2 Write background content and the HomeProof example
* 4.3 Link back to index.html
* 4.4 Apply and test styling from style.css

### 5. Website Design
* 5.1 Define visual direction: palette, typography, layout concept
* 5.2 Build shared styles in `style.css` (nav, footer, spacing, etc.)
* 5.3 Confirm shared styles work across both page templates before adding content

### 6. Cross-Page Quality Pass
* 6.1 Check both pages at desktop and mobile widths
* 6.2 Check navigation works correctly in both directions
* 6.3 Proofread all copy against the scope statement's Exclusions (no overstated claims)

### 7. README.md
* 7.1 Write a clear project description
* 7.2 Add link to the live GitHub Pages site
* 7.3 Add link to the docs/ folder

### 8. Final Wrap-Up
* 8.1 Final commit and push to GitHub
* 8.2 Confirm live site and all links work end-to-end
* 8.3 Write `retrospective.md`
* 8.4 Review entire repo against the scope statement's Desired Results and Acceptance Criteria
