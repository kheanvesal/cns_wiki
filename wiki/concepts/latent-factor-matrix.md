---
type: concept
title: "Readability Latent-Factor Matrix (V1–V6 / L1–L6)"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [framework, latent-factors, prior-analysis, coding-scheme, reconciliation]
created: 2026-07-26
updated: 2026-07-26
source_count: 63
---

# Readability Latent-Factor Matrix

Reconciliation page for the prior analysis in **`Readability Latent-Factor Matrix.xlsx`** (root; read-only source). It codes 63 unique papers on 12 latent dimensions at H/M/L/None, with a coverage summary, per-paper dimension notes, and a gap analysis.

## The 12 axes
**Visual (V):**
- **V1 Spatial density** — line length/cpl, interletter & line spacing, margins/whitespace → my [[concepts/line-length]], [[concepts/line-spacing]], [[concepts/whitespace-margins]].
- **V2 Glyph legibility** — typeface, font size, disfluency, case → [[concepts/font-type-typeface]], [[concepts/font-size]], [[concepts/serif-vs-sans]], [[concepts/disfluency]], [[concepts/legibility]].
- **V3 Salience distribution** — bold/italic emphasis, cueing, attention guidance → [[concepts/emphasis-bold-italic]], [[concepts/signaling]].
- **V4 Temporal presentation** — pacing, RSVP, scrolling vs pagination → [[concepts/scrolling-vs-paging]], [[concepts/reading-speed]].
- **V5 Layout-structure mapping** — headings/structure↔layout alignment, graphic organizers → [[concepts/headings-signaling]], [[concepts/text-structure]], [[concepts/graphic-organizers]].
- **V6 Navigation structure** — linear scroll ↔ paginated ↔ hyperlinked ↔ tiered/collapsible → [[concepts/scrolling-vs-paging]], [[concepts/interaction-style]].

**Linguistic (L):** L1 Lexical sophistication · L2 Syntactic complexity · L3 Cohesion · L4 Compression · L5 Rhetorical scaffolding · L6 Narrativity/genre.

Full definitions + examples for all 12: [[concepts/latent-factor-definitions]].

## Coverage (from the xlsx)
Most-engaged: **V5** (25 papers), **V2** (22), **V6** (22), **V1/V3** (20 each). Thinnest: **L2 & L4** (5 each), **L1 & L6** (9 each). The corpus is **visual-heavy, linguistics-light**.

## Documented gaps (xlsx "Missing Innovations") — feed these to LINT / new sourcing
- **L2 syntactic complexity** never experimentally manipulated with a readability outcome.
- **L4 compression** (full→summary→TL;DR→headline) only appears as an *outcome*, never an IV. *(Gen-AI update: LLM summaries make compression a manipulable input — [[sources/rolle-2025-gpt-tools-comprehension]], [[sources/kreijkes-2026-llm-notetaking-comprehension]]; see [[syntheses/gen-ai-and-reading]].)*
- **V4 true externally-paced (RSVP)** presentation absent.
- **Visual × reader-profile** moderators rarely crossed (e.g., fast readers slowed by wide spacing).
- **Adaptive/personalized** layout policy proposed but never empirically compared to fixed settings. *(Gen-AI update: LLMs now enable this — [[sources/mcnamara-2025-genai-text-personalization]] (linguistic adaptation), [[sources/chen-2024-textlap-layout-planning]] (layout generation) — but reader-outcome comparisons vs a fixed default are still open. See [[syntheses/gen-ai-and-reading]].)*
- **V6** under-samples the tiered/collapsible end.
- **L6 narrative↔expository recasting** has ~1 direct study ([[sources/ssrn-5678368]]).
- **Single-axis isolation dominates**; V×V and V×L interaction studies are rare.
- Reading goal **"pleasure/leisure"** essentially unstudied.
- **Mechanism-level (eye-tracking) evidence thin** relative to outcome-level.

> **Validity caveat.** This scheme is a rational taxonomy, **not a validated latent-factor structure** — several axes are non-orthogonal (V5↔L5 r=+0.66; the L-block collapses) and the H/M/L level conflates *manipulation* with *mention*. Treat coverage figures as *attention*, not manipulated coverage. Full review: [[concepts/latent-factor-matrix-critique]].

## Reconciliation notes / mismatches
- The matrix's V/L axes **map cleanly** onto this wiki's concept pages (above). No contradictions found; the matrix is more granular on **linguistic** axes (L1–L6), which the concept layer currently under-develops — a build-out opportunity.
- Matrix counts **63 unique papers**; this wiki's source pages match after folding `out.pdf` into [[sources/160800-snyder-1978-proofreading-typewriting]] (same dissertation) — see [[sources/out-scanned-preview]].
- Better citations the matrix supplied were propagated to: [[sources/2534-handheld-whitespace-reading]] (Huang & Li 2017), [[sources/kirby-style-strategy-skill-reading]] (Kirby 1988), [[sources/7085c1aa-book-review]] (review of Peggy Smith, *Letter Perfect*).

## Applied analysis
- [[syntheses/reading-goal-x-controlling-latent-factors]] — which of these 12 factors *control* each reading goal (vs. which are merely studied).
- [[syntheses/research-attention-over-time]] — how attention to these factors trended across eras (text style flat, layout dominant, linguistic bimodal). Key result: V2 glyph legibility is over-studied relative to its control; the controlling factors are structural/situational (V5, V3, V6, V4) plus linguistic L3/L5 for comprehension.

**See also.** all four hubs; [[concepts/method-type-divergence]] (the matrix's Layer B mechanism-vs-outcome point); [[syntheses/reading-goal-x-text-style-matrix]] (observable-variable version).
