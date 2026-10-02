---
type: synthesis
title: "Reading-Goal × Text-Style Matrix"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, matrix, comparison, style-effects, cross-hub]
created: 2026-07-26
updated: 2026-07-27
source_count: 30
---

# Reading-Goal × Text-Style Matrix

> **Abstraction:** [[syntheses/reading-goal-x-controlling-latent-factors]] rolls these observable variables up into the 12 latent factors and asks which *control* each goal. Read this page for the empirical variables; that one for the latent-factor verdict.
>
> **Visual reference:** `assets/text-style-specimens.html` (typographic variables) + `assets/layout-pattern-specimens.html` (page/screen layout patterns, incl. AI-generated layout) + `assets/genai-content-specimens.html` (the Gen-AI content layer this table's typographic scope excludes — see the gap note below) — paired before/after specimens tagged with these verdicts. Open in a browser or Obsidian.

Every style/layout variable in the corpus, cross-referenced against the four reading goals. The point of the matrix is the **interaction**: the same variable helps one goal and is neutral for another. The three sections below follow the [[concepts/text-style-vs-layout]] distinction — glyph-level (threshold), spatial/structural (control), and medium — with spacing/emphasis as bridge variables.

**Cell legend.** ↑ helps · ↓ hurts · = neutral/null · ~ mixed/contested · · not studied here. Parentheses = evidence strength: (s)=well-supported, (m)=moderate, (t)=thin/contested.

## Visual / typographic variables

| Variable | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **Font size** | = (s) legible-enough; aids speed not comp [[sources/ej1079769]] | ~ (t) display factor [[sources/chan-2011-optimum-interface-chinese-proofreading]] | · | ↑ (m) eases gaze [[sources/beymer-font-size-type-online-reading]] |
| **Typeface (serif/sans)** | = (s) weak [[sources/richardson-legibility-serif-sans-serif]], [[sources/ej1079769]] | ~ (t) [[sources/chan-2011-optimum-interface-chinese-proofreading]] | · | = (m) weak [[sources/beymer-font-size-type-online-reading]], [[sources/lund-1999-knowledge-construction-typography]] |
| **Disfluent fonts** | ~ (t) net null [[sources/ssrn-5678368]], [[sources/diemand-yauman-oppenheimer-fortune-favors-bold]] | · | · | ~↓ (t) slows, no retention gain [[sources/dykes-sans-forgetica-readability]], [[sources/font-disfluency-online-learning-highschool]] |
| **Line spacing (leading)** | = (m) null for comp [[sources/interletter-line-spacing-reading-speed-comprehension]] | ↑ (m) strong lever [[sources/chan-2014-line-length-spacing-proofreading]], [[sources/huang-2017-line-spacing-simplified-chinese]] | · | ↑ (m) legibility [[sources/tinker-1963-legibility-of-print]] |
| **Letter spacing** | = (m) comfort only [[sources/interletter-line-spacing-reading-speed-comprehension]] | · | ↓ (m) degraded boundary slows [[sources/fisher-1975-reading-visual-search]] | = (t) |
| **Line length / cpl** | ↑ (m) ~55 optimal [[sources/dyson-haselgrove-2001-speed-linelength-screen]], [[sources/layout-on-screen]] | ~ (m) drives scrolling [[sources/chan-2014-line-length-spacing-proofreading]] | · | ↑ (m) [[sources/dyson-haselgrove-2000-speed-patterns-screen]] |
| **Letter case (ALL-CAPS)** | ↓ (s) caps slower [[sources/tinker-1963-legibility-of-print]] | · | ↓ (m) word-shape loss [[sources/fisher-1975-reading-visual-search]] | ↓ (s) [[sources/tinker-1963-legibility-of-print]] |
| **Emphasis (bold/italic)** | ~ (t) predicts difficulty [[sources/martin-calpena-web-comprehension-2022]] | · | · | ↑ (t) salience/signaling |
| **Whitespace / margins** | ~ (t) | ~ (m) perf vs preference [[sources/2534-handheld-whitespace-reading]] | ↓dense↑ (m) sparse preferred, dense faster [[sources/tarling-2009-page-layout-visual-search]] | = (t) demarcation [[sources/functional-headings-selective-attention]] |
| **Information density** | · | · | ↑ (m) dense faster [[sources/tarling-2009-page-layout-visual-search]] | ~ (t) |

## Structural / layout variables

| Variable | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **Headings / signaling** | ↑ (m) macrostructure [[sources/lemarie-lorch-perywoodley-2012-headings]] | · | ↑ (t) navigation cue | ↑ (m) marks high-value regions [[sources/functional-headings-selective-attention]] |
| **Structure-aligned organizers** | ↑ (m) d=0.56 [[sources/ej1486502]], [[sources/18_63]] | · | ↑ (m) topology×task [[sources/liang-2013-infographics-layout-search-eyetracking]] | ↑ (t) |
| **Segmentation / indentation** | ↑ (m) [[sources/ssrn-5678368]] | · | · | ↑ (t) |
| **Text–graphic integration** | ↑ (m) manage split-attention [[sources/3320435-3320447]], [[sources/mayer-fiorella-intro-multimedia-learning]] | · | ~ (t) graphic type [[sources/zuo-2023-target-layout-graphic-search-eyetracking]] | ↑ (t) |
| **Layout topology (linear/radial)** | · | · | ↑ (m) radial>linear for comparison [[sources/liang-2013-infographics-layout-search-eyetracking]] | · |
| **Information structure / interaction style** | · | · | ↑ (m) task-dependent [[sources/capra-marchionini-structure-interaction-search]] | · |
| **Text direction / copy placement** | · | ~ (t) display factor [[sources/chan-2011-optimum-interface-chinese-proofreading]] | · | · |

## Medium / delivery variables

| Variable | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **Screen vs. paper** | ↓ (s) small paper advantage [[sources/clinton-2019-paper-vs-screens-meta]], [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]] | ↓ (m) medium costs [[sources/vitello-2022-screen-vs-paper]] | · | ↓ (m) shallowing [[sources/clinton-2019-paper-vs-screens-meta]] |
| **Scrolling vs. pagination** | · | ~ (m) line factors drive scrolling [[sources/chan-2014-line-length-spacing-proofreading]] | ~ (m) ×screen size [[sources/hemminger-marcial-2012-scrolling-pagination]] | ~ (m) reading patterns [[sources/dyson-haselgrove-2000-speed-patterns-screen]] |
| **Screen size** | · | ~ (m) small handheld [[sources/2534-handheld-whitespace-reading]] | ↑ (m) ×navigation [[sources/hemminger-marcial-2012-scrolling-pagination]] | · |
| **Time pressure** | ↓ (m) esp. on screen [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]] | · | · | →skim (s) triggers satisficing [[sources/duggan-payne-2009-text-skimming]] |

## Reading the matrix — three patterns
1. **Comprehension is moved by structure, not surface.** Its ↑ cells cluster in the structural block (headings, organizers, segmentation, integration, line length); its surface cells (size, typeface, spacing) are `=`. See [[syntheses/does-style-improve-comprehension]].
2. **Proofreading is moved by spacing/line geometry** — line spacing and line number are its strongest levers; but the evidence is almost entirely **Chinese-script** ([[entities/alan-chan-cityu-group]]).
3. **Search/skimming are moved by salience, density, and navigation** — target discriminability and getting to the right region, not deep-reading variables. See [[syntheses/skimming-vs-scanning-vs-search]].

## Big empty regions (sourcing gaps)
- **Search** has no comprehension-style typographic evidence (font/spacing cells are `·`) — it's studied via density, structure, and navigation instead.
- **Proofreading** rarely varies structural variables (headings/organizers) — it's a legibility/geometry literature.
- Linguistic axes (syntax, compression) are absent here; see [[concepts/latent-factor-matrix]] gap-list. *Gen-AI update:* LLM tools now manipulate the **content** side (compression via summaries, cohesion/level via rewriting) — a lever beyond this table's typographic scope; see [[syntheses/gen-ai-and-reading]] and `assets/genai-content-specimens.html` for worked before/after examples of that layer.
- Most cells rest on **single studies**; `~`/`(t)` cells are the priority targets for replication.

---
*Filed from a QUERY on 2026-07-26. Companion to [[syntheses/does-style-improve-comprehension]], [[syntheses/evidence-based-default-screen-layout]], [[syntheses/skimming-vs-scanning-vs-search]], [[syntheses/when-measures-disagree]]. Hubs: [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]]. Cross-check against [[concepts/latent-factor-matrix]].*
