---
type: synthesis
title: "Research Attention Over Time — Text Style vs Layout vs Linguistic"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, trend, temporal, bibliometric, latent-factors]
created: 2026-07-26
updated: 2026-07-26
source_count: 60
---

# Research Attention Over Time

How the corpus's focus has shifted across eras, using publication year (available for **60 of 63** papers, 1963–2025) crossed with the [[concepts/latent-factor-definitions]] grouped into three buckets ([[concepts/text-style-vs-layout]]): **text style** (V2 glyph), **layout** (V1, V3–V6), **linguistic** (L1–L6). Values are weighted engagement (H=3/M=2/L=1), shown per paper to remove era volume.

## The data

| Era | papers | Text style | Layout | Linguistic | — per paper (TS / LAY / LING) |
|---|---|---|---|---|---|
| pre-1990 | 4 | 6 | 9 | 1 | 1.5 / 2.2 / 0.2 |
| 1990–2004 | 13 | 7 | 34 | 37 | 0.5 / 2.6 / 2.8 |
| 2005–2014 | 20 | 19 | 82 | 15 | 0.9 / 4.1 / 0.8 |
| 2015–2026 | 23 | 19 | 59 | 37 | 0.8 / 2.6 / 1.6 |

Share of attention per era: text style 38→9→16→17%; layout 56→44→71→51%; linguistic 6→47→13→32%.

## The trend, in three parts
1. **Text style (glyph) is flat and low throughout.** Only the earliest print-legibility era (Tinker, [[sources/tinker-1963-legibility-of-print]]) gave it real weight; since ~1990 it's the least-studied factor per paper. The field effectively **settled** typeface/size/case early and moved on — consistent with the control finding that glyph legibility is a **threshold, not a lever** ([[syntheses/reading-goal-x-controlling-latent-factors]]).
2. **Layout dominates and peaks in 2005–2014** — the screen-reading / HCI / eye-tracking wave: line length ([[sources/layout-on-screen]]), search UIs ([[sources/capra-marchionini-structure-interaction-search]]), scrolling ([[sources/hemminger-marcial-2012-scrolling-pagination]]). It eases after but still leads every era.
3. **Linguistic is bimodal** — peaks 1990–2004 (comprehension-theory era: [[sources/kintsch-1998-comprehension]], [[sources/journal-of-educational-psychology-1999]]), collapses during the HCI decade, then recovers after 2015 as structure/genre work returns ([[sources/ssrn-5678368]], [[sources/ej1486502]]).

## Interpretation
Research attention has **cycled** between "how the text reads" (linguistic) and "how it's arranged on screen" (layout), while "how the letters look" (text style) was decided early and largely abandoned. Crucially, the swings track **technology waves** (the arrival of screens drove the 2005–2014 layout peak) more than they track **what controls outcomes** — the linguistic collapse in the 2000s wasn't because cohesion stopped mattering, and the enduring low investment in text style is (for once) aligned with the evidence.

## Gen-AI addendum (2024–2026)
A **new wave** has arrived that the factor-coded corpus doesn't capture: LLM/Gen-AI reading research ([[syntheses/gen-ai-and-reading]]). It reopens the previously-dormant **linguistic** axes — but via *tools* (AI summaries, personalized rewriting) rather than hand-authored text — and it finally activates **L4 compression**. So the "linguistic recovery" after 2015 is likely to accelerate sharply post-2023, now driven by AI rather than discourse theory. This wave is a candidate for a fifth era once enough Gen-AI papers are ingested and factor-coded.

## Caveats
- **Weighted-engagement coding** = *attention* (includes review/mention papers), which is the right measure for an attention trend but carries the mention-vs-manipulation inflation flagged in [[concepts/latent-factor-matrix-critique]]. A manipulated-IV-only trend would be sparser, especially for linguistic (L2/L4 ≈ 0 manipulations in any era).
- **Coarse buckets** — 60 papers, uneven era counts (4/13/20/23); the pre-1990 cell rests on 4 papers.
- 3 papers lack a parseable year and are excluded.

## See also
[[concepts/latent-factor-matrix]] · [[concepts/text-style-vs-layout]] · [[syntheses/reading-goal-x-controlling-latent-factors]] · [[concepts/latent-factor-matrix-critique]].
