## [2025-10-23] — Stable Portal Link & URL Resolution Fix

**Summary**
- Fixed encoded Liquid tag issue in `shift.html` portal link (`%257B%257B…%257D%257D`) by replacing it with a clean absolute URL.
- Restored functional navigation between *shift.html* and *byDesign* pages.
- Verified correct site title render (no longer triggers 404 fallback).
- Maintained portal glow and animation styling without regressions.

**Files Updated**
- `shift.html`
- `shift.css`

**Outcome**
- Portal behavior now clean, stable, and independent of Jekyll processing.
- Direct cross-domain navigation between *shift* and *byDesign* confirmed.
- Base milestone complete for next phase: cross-environment build consistency.

_Tag: `v1.1-portal-link-stable`_



## [2025-10-22] — Baseline Milestone: Hover-Isolated Portal + Stable Layout

**Summary**
- Implemented hover-isolated “exit the Singularity” portal dot on *shift.html*.
- Fully separated hover behavior from `.section.origin` kicker using absolute wrapping (`.portal-wrap`).
- Restored proper section spacing and visual hierarchy across all content blocks.
- Finalized glow and hover animations for “iamshift.dev” within the Continuum section.
- Established visual and motion parity with byDesign’s portal entry dot.

**Files Updated**
- `shift.html`
- `shift.css`

**Outcome**
- Baseline stable version confirmed visually and behaviorally.  
- All interactive elements behave independently (no hover bleed).  
- Responsive layout intact.

_Tag: `v1.0-shift-portal-stable`_