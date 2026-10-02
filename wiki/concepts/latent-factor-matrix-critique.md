---
type: concept
title: "Critique of the Latent-Factor Scheme (V1–V6 / L1–L6)"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [critique, methodology, latent-factors, validity, coding]
created: 2026-07-26
updated: 2026-07-26
source_count: 0
---

# Critique of the Latent-Factor Scheme (V1–V6 / L1–L6)

A validity review of the coding scheme in `Readability Latent-Factor Matrix.xlsx` (see [[concepts/latent-factor-matrix]]). Grounded in the xlsx's own operational definitions (Dimension Notes) and a pairwise correlation analysis of the 12 dimensions across the 63 coded papers.

## Verdict
A **sensible and useful rational taxonomy** — it enabled the coverage and control analyses — but **not a validated latent-factor structure**. The label overclaims; several axes are non-orthogonal; the H/M/L level conflates *manipulation* with *mention*; and there is construct drift in several codings.

## What holds up
- **The visual axes are genuinely distinct.** Splitting **V1 spatial density** (spacing/margins/cpl) from **V2 glyph legibility** (letterform/size) is defensible — they are uncorrelated in the data (V2–V6 = −0.25, V1 separate from L-axes). **V5 layout-structure** and **V6 navigation** are also crisp.
- These four visual axes map cleanly onto the reading-goal control signatures ([[syntheses/reading-goal-x-controlling-latent-factors]]).
- Having an explicit scheme at all is what surfaced the **controlling-but-untested** gaps (L2, L4).

## Problems

### 1. "Latent factors" is a misnomer
The dimensions are defined top-down (rational taxonomy), not extracted from any covariance/factor analysis. Nothing is "latent." **Rename to *coding dimensions*** or validate empirically before claiming factor status.

### 2. Non-orthogonality (empirical)
Pairwise correlations (H=3/M=2/L=1) across the 63 papers — highest positive pairs signal redundancy:

| Pair | r | Reading |
|---|---|---|
| **V5 ↔ L5** | **+0.66** | Same construct (text structure) coded twice — visual + linguistic — often from one feature. Double-counts. |
| L1 ↔ L2 | +0.64 | Linguistic axes collapse together… |
| V3 ↔ V5 | +0.63 | Salience overlaps layout-structure. |
| L2 ↔ L3 | +0.60 | …the six L-axes behave like ~1–2 underlying factors, not six. |
| L3 ↔ L5 | +0.53 | |
| V4 ↔ V6 | +0.34 | Temporal overlaps navigation (scroll/paginate). |

Well-separated (good): V2–V6 −0.25, V1–L3 −0.29 (visual vs linguistic correctly distinct). **The 6-visual / 6-linguistic symmetry is forced** — the L-block is not six independent factors.

### 3. Construct drift in the coding (from Dimension Notes)
- **V4 "Temporal presentation" coded High for "screen vs. paper"** — medium ≠ temporality. There is no Medium axis, so it leaked into V4.
- **V3 "Salience"** coded Medium where the note itself says "IV is reader ability, not visual salience."
- **L1 "Lexical sophistication"** coded from camelCase identifier segmentation — that is orthographic/word-boundary (visual), not vocabulary difficulty.
- **L4 "Compression"** credited to skimming-as-*behavior*, though the axis is defined as text *transformation* (full→summary→headline).

### 4. The H/M/L scale conflates two things
It mixes *centrality of manipulation* ("manipulated as core IV") with *mere mention* ("reviewed/contextual"). So engagement counts **overstate real coverage**. Evidence: **20 of 63 papers have no dimension coded High at all**; only 13 have ≥2 High. Much of the scale's signal is M/L "mentions."

### 5. Completeness gaps
No dedicated **Medium/Device** axis (leaked into V4); no **Color/Contrast** axis; no **Interactivity / hyperlink-density** distinct from V6; graphics/multimodality folded into V5 rather than standalone. Reader-side variables are (reasonably) excluded — but ability/learning-style papers then get mis-coded onto V3.

## Recommended revisions
1. Rename to **coding dimensions** (or run an actual factor analysis to earn "latent").
2. **Split the level code** into two orthogonal fields: *manipulated-IV vs. mentioned* × *centrality*; recompute coverage on manipulated-only.
3. **Collapse or redefine V5/L5** — either one text-structure construct, or define independently (structure *present* vs. structure *signalled by layout*).
4. **Add a Medium axis**; reserve V4 for true pacing (RSVP); move screen/paper there.
5. **Re-assign mis-coded cells:** camelCase → word-segmentation (V-side); reader-ability → moderator (not V3); skimming-behavior → outcome (not L4).
6. Consider adding **Color/Contrast** and **Interactivity**.

## Impact on this wiki's analyses
The "engagement/coverage" figures in [[concepts/latent-factor-matrix]] and [[syntheses/reading-goal-x-controlling-latent-factors]] inherit the **mention-vs-manipulation inflation** — treat the ▓▒░ engagement shades as *attention*, not *manipulated coverage*. The **control** ratings (●◐○) are unaffected (they derive from source-page effect directions, not the xlsx level codes). Caveat notes added to both pages.

## Net assessment
The **visual side is close to a real factor structure**; the **linguistic side is aspirational scaffolding** the current corpus cannot populate or discriminate. Keep the scheme for organizing and gap-finding; stop treating its 12 axes as 12 independent factors.

**See also.** [[concepts/latent-factor-matrix]] · [[syntheses/reading-goal-x-controlling-latent-factors]] · [[syntheses/reading-goal-x-text-style-matrix]] · [[concepts/method-type-divergence]].
