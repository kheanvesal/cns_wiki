---
type: synthesis
title: "Reading-Goal × Text-Style Matrix"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, matrix, comparison, style-effects, cross-hub]
created: 2026-07-26
updated: 2026-10-02
source_count: 41
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
| **Disfluent fonts** | ↓ accuracy / = benefit (s) [[sources/ssrn-5678368]], [[sources/diemand-yauman-oppenheimer-fortune-favors-bold]], [[sources/janouskova-2022-font-readability-moses-illusion]] | · | · | ~↓ (t) slows, no retention gain [[sources/dykes-sans-forgetica-readability]], [[sources/font-disfluency-online-learning-highschool]] |
| **Line spacing (leading)** | = (m) null for comp [[sources/interletter-line-spacing-reading-speed-comprehension]] | ↑ (m) strong lever [[sources/chan-2014-line-length-spacing-proofreading]], [[sources/huang-2017-line-spacing-simplified-chinese]] | · | ↑ (m) legibility [[sources/tinker-1963-legibility-of-print]] |
| **Letter spacing** | = (m) comfort only [[sources/interletter-line-spacing-reading-speed-comprehension]] · ↑ dyslexianet subgroup (t) [[sources/arya-2023-assessment-methods-readability-legibility]] | · | ↓ (m) degraded boundary slows [[sources/fisher-1975-reading-visual-search]] | = (t) |
| **Line length / cpl** | ↑ (m) ~55 optimal [[sources/dyson-haselgrove-2001-speed-linelength-screen]], [[sources/layout-on-screen]] | **↑ (s)** **inverted U, peak ≈45 cpl, ω²=.42** [[sources/porte-2001-typographical-error-salience-l2]] | · | ↑ (m) [[sources/dyson-haselgrove-2000-speed-patterns-screen]] |
| **Letter case (ALL-CAPS)** | ↓ (s) caps slower [[sources/tinker-1963-legibility-of-print]] | · | ↓ (m) word-shape loss [[sources/fisher-1975-reading-visual-search]] | ↓ (s) [[sources/tinker-1963-legibility-of-print]] |
| **Emphasis (bold/italic)** | ~ (t) predicts difficulty [[sources/martin-calpena-web-comprehension-2022]] | · | · | ↑ (t) salience/signaling |
| **Typeface familiarity** | = (m) [[sources/accelerating-adult-readers-typeface]], [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] | · | ~ pref not perf [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] | = (m) no speed or recall benefit [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] |
| **Whitespace / margins** | ~ (t) | ~ (m) perf vs preference [[sources/2534-handheld-whitespace-reading]] | ↓dense↑ (m) sparse preferred, dense faster [[sources/tarling-2009-page-layout-visual-search]] | = (t) demarcation [[sources/functional-headings-selective-attention]] |
| **Information density / #elements** | · | · | **↑ (m) → ↓ (s)** volume cost, non-monotonic; individual clusters > layouts [[sources/li-2009-web-layout-information-forms-locations]], [[sources/lu-et-al-2011-visual-search-information-overload]] | ~ (t) |

## Structural / layout variables

| Variable | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **Headings / signaling** | **↑ (m)** p<.001 recall, but **21 cues bundled** [[sources/lege-2019-typography-efl-eye-tracking]] | · | ↑ (m) fewer fixations b=−0.92 [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]] | ↑ (m) marks high-value regions [[sources/functional-headings-selective-attention]] |
| **Structure-aligned organizers** | ↑ (m) d=0.56 [[sources/ej1486502]], [[sources/18_63]] | · | ↑ (m) topology×task [[sources/liang-2013-infographics-layout-search-eyetracking]] | ↑ (t) |
| **Segmentation / indentation** | ↑ (m) [[sources/ssrn-5678368]] | · | · | ↑ (t) |
| **Text–graphic integration** | ↑ (m) manage split-attention [[sources/3320435-3320447]], [[sources/mayer-fiorella-intro-multimedia-learning]] | · | **↑ (m)** congruity ↑search p<.001, ↓distraction p<.001 [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] | ↑ (t) |
| **Layout topology (linear/radial) / order** | = (t) order no direct effect [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] | · | ↑ (m) radial>linear for comparison [[sources/liang-2013-infographics-layout-search-eyetracking]]; order→fixation duration only (p=.002) [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] | · |
| **Information structure / interaction style** | · | · | ↑ (m) task-dependent [[sources/capra-marchionini-structure-interaction-search]] | · |
| **Text direction / copy placement** | ~ (t) vertical>horizontal recall t=3.569, p=.001 [[sources/chinese-typography-eye-tracking-vertical-horizontal]] | ~ (t) display factor [[sources/chan-2011-optimum-interface-chinese-proofreading]] | ~ script familiarity > direction [[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] | · |

## Medium / delivery variables

| Variable | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **Screen vs. paper** | **↓ (s)** g=−.21, p=.02 [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]], [[sources/clinton-2019-paper-vs-screens-meta]]; **= (m) in first graders** [[sources/florit-2025-first-grade-comprehension-monitoring]]; **shallow-only** [[sources/chen-et-al-2014-paper-screen-tablet-familiarity]] | ↓ (m) medium costs [[sources/vitello-2022-screen-vs-paper]] | · | ↓ (m) shallowing [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]]; **= (m) speed** pooled null [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]] |
| **Scrolling vs. pagination** | · | ~ (m) line factors drive scrolling [[sources/chan-2014-line-length-spacing-proofreading]] | ~ (m) ×screen size [[sources/hemminger-marcial-2012-scrolling-pagination]] | ~ (m) reading patterns [[sources/dyson-haselgrove-2000-speed-patterns-screen]] |
| **Screen size** | · | ~ (m) small handheld [[sources/2534-handheld-whitespace-reading]] | ↑ (m) ×navigation [[sources/hemminger-marcial-2012-scrolling-pagination]] | · |
| **Time pressure** | ↓ (m) esp. on screen [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]] | · | · | →skim (s) triggers satisficing [[sources/duggan-payne-2009-text-skimming]] |

## Reading the matrix — three patterns
1. **Comprehension is moved by structure, not surface.** Its ↑ cells cluster in the structural block (headings, organizers, segmentation, integration, line length); its surface cells (size, typeface, spacing) are `=`. See [[syntheses/does-style-improve-comprehension]]. **Updated 2026-10:** the strongest new structural cell (Lege, cueing, p < .001) is also the one with a **21-cue bundle confound**, and the strongest new surface entry is a **negative** (disfluency lowering accuracy) — so this pattern held but its evidentiary base weakened on both sides.
2. **Proofreading is moved by spacing/line geometry** — line spacing and line number are its strongest levers; but the evidence is almost entirely **Chinese-script** ([[entities/alan-chan-cityu-group]]). **Updated 2026-10:** this claim is now anchored by a non-Chinese, isolated-variable study with the corpus's largest effect in proofreading — **line length, ω² = .42, inverted U peaking at ≈45 cpl** [[sources/porte-2001-typographical-error-salience-l2]]. It upgrades that cell from `~ (m)` to `↑ (s)` and adds a **non-monotonicity** no other cell in the matrix has.
3. **Search/skimming are moved by salience, density, and navigation** — target discriminability and getting to the right region, not deep-reading variables. See [[syntheses/skimming-vs-scanning-vs-search]]. **Updated 2026-10:** the density cell split in two — *density as arrangement* (preference≠performance) versus *volume as quantity* (monotonic cost, non-monotonic at the top), and the second is confounded with the first in every study.

## ★ Cells changed by the 2026-10 ingest
| Cell | Before | After | Reason |
|---|---|---|---|
| Line length × Proofreading | ~ (m) | **↑ (s), non-monotonic** | Porte ω² = .42, peak ≈45 cpl, decline at 35 [[sources/porte-2001-typographical-error-salience-l2]] |
| Disfluent fonts × Comprehension | ~ (t) net null | **↓ accuracy / = benefit** | Janoušková dissociation, equivalence-tested null on the reflective outcome [[sources/janouskova-2022-font-readability-moses-illusion]] |
| Screen vs. paper × Comprehension | ↓ (s) | **↓ (s) but depth- and age-qualified** | Kong pooled g = −.21; shallow-only effect; null in first graders; tablet ≈ paper [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]] · [[sources/chen-et-al-2014-paper-screen-tablet-familiarity]] · [[sources/florit-2025-first-grade-comprehension-monitoring]] |
| Headings × Comprehension | ↑ (m) | **↑ (m), confounded** | Lege p < .001 but 21 simultaneous cues; redirection not recruitment [[sources/lege-2019-typography-efl-eye-tracking]] |
| Typeface familiarity | (absent) | **new row, = (m)** | Ho Sang & Petrarca: preferred, not faster, no recall gain [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] |
| Information density × Search | ↑ (m) | **↑ (m) → ↓ (s) non-monotonic** | Li (subtractive) vs Lu (multiplicative) vs Lu's mid-range reversals; clusters > layouts |
| Text–graphic integration × Search | ~ (t) | **↑ (m)** | Zhang congruity: search p < .001, distraction p < .001 |

## Big empty regions (sourcing gaps)
- **Search** has no comprehension-style typographic evidence (font/spacing cells are `·`) — it's studied via density, structure, and navigation instead. **Still true after 2026-10.**
- **Proofreading** rarely varies structural variables (headings/organizers) — it's a legibility/geometry literature. **Still true:** Lege is the only structural manipulation in the new batch, and it was run on L2 *readers*, not proof-readers.
- **★ Quantity is never separated from arrangement.** Every density/volume cell in this matrix is confounded with the number of elements. This is now the matrix's single most-cited methodological gap. See [[concepts/visual-search]].
- **★ No cell is populated for comprehension of long text.** The 2026-10 comprehension studies run 140 words to a few pages. See [[concepts/screen-size]].
- Linguistic axes (syntax, compression) are absent here; see [[concepts/latent-factor-matrix]] gap-list. *Gen-AI update:* LLM tools now manipulate the **content** side (compression via summaries, cohesion/level via rewriting) — a lever beyond this table's typographic scope; see [[syntheses/gen-ai-and-reading]] and `assets/genai-content-specimens.html` for worked before/after examples of that layer.
- Most cells rest on **single studies**; `~`/`(t)` cells are the priority targets for replication. **★ The 2026-10 batch made this worse, not better:** it added strong single-study cells (Porte, Lege, Li, Lu) with n = 15–65 each and no independent replications.

---
*Filed from a QUERY on 2026-07-26. Companion to [[syntheses/does-style-improve-comprehension]], [[syntheses/evidence-based-default-screen-layout]], [[syntheses/skimming-vs-scanning-vs-search]], [[syntheses/when-measures-disagree]]. Hubs: [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]]. Cross-check against [[concepts/latent-factor-matrix]].*
