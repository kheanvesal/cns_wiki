---
type: concept
title: "Readability (corpus definition)"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [definition, readability, scope, core]
created: 2026-07-26
updated: 2026-07-26
source_count: 70
---

# Readability — a corpus-grounded definition

The synthesized definition of "readability" that this whole wiki supports. It reconciles how the sources use the term and states the study's scope (target documents).

## Definition
> **Readability is the degree to which a *given reader*, pursuing a *given goal*, in a *given medium*, can efficiently extract the information they need from a document.** It is a joint function of four things — the **content** (linguistic properties), the **presentation** (typography + layout), the **reader** (skill, knowledge, goal), and the **task/medium** — measured at the level appropriate to the goal.

Three properties fall out of the corpus and matter most:

1. **Relational, not intrinsic.** Readability is not a fixed property of a document. The same document is readable *differently* for comprehension vs. skim vs. search vs. proofread ([[syntheses/reading-goal-x-controlling-latent-factors]]), and for a novice vs. an expert ([[sources/rolle-2025-gpt-tools-comprehension]], [[sources/binkley-identifier-style-effort-comprehension-2012]]). A definition that omits reader and goal is incomplete. This is the wiki's central claim ([[concepts/reading-purpose-and-goal]]).
2. **Multi-level.** It spans Kintsch's levels — surface **legibility** → **textbase** → **situation model** ([[sources/kintsch-1998-comprehension]]). "Readable" can mean *legible* (fast to decode) or *comprehensible* (easy to understand) — different levels, often confused ([[concepts/legibility]]).
3. **Measure-dependent.** Operationalized via speed, accuracy/comprehension, eye movements, and comfort/preference — which routinely **disagree** ([[concepts/method-type-divergence]], [[syntheses/when-measures-disagree]]). Any readability claim must name its measure.

## What readability is NOT (common narrowings)
- **Not legibility.** Legibility is glyph-level decoding ease; it's a *threshold* input to readability, not readability itself ([[concepts/legibility]], [[concepts/text-style-vs-layout]]).
- **Not a formula.** Flesch-Kincaid and kin capture only surface **lexical + syntactic** features (matrix L1/L2). They miss cohesion (L3), rhetorical scaffolding (L5), layout, medium, reader, and goal — most of what actually controls the outcome ([[concepts/latent-factor-matrix]], [[sources/mcnamara-2025-genai-text-personalization]]).
- **Not comprehension alone.** Comprehension is one *outcome* of readability (the deep-reading one); readability also governs speed, error-detection, and findability.

## What determines it (the 12 factors, ranked by control)
The [[concepts/latent-factor-definitions]] decompose readability's determinants. Ranked by how much they *control* outcomes ([[syntheses/reading-goal-x-controlling-latent-factors]]):
1. **Content / linguistic** — cohesion (L3), rhetorical scaffolding (L5), and increasingly **compression** (L4, now LLM-manipulable). Move the ceiling most.
2. **Layout** — layout-structure mapping (V5), salience (V3), navigation (V6), spatial density (V1). Move the ceiling.
3. **Text style / glyph** — typeface, size, case, disfluency (V2). A **threshold**: sets the floor, rarely the ceiling.
Plus the moderators that make it relational: **reader** (skill, knowledge), **goal/task**, **medium** (screen vs paper).

## Full stack (floor → ceiling)
**text style → layout → content** ([[concepts/text-style-vs-layout]]): text style sets the floor, layout moves the ceiling, content moves it most. Gen-AI now makes the content layer directly manipulable ([[syntheses/gen-ai-and-reading]]).

---

## Target documents (scope of this study)
What kinds of documents the corpus's readability findings actually cover — and therefore where they generalize.

**Genre / text type (what's studied):** predominantly **expository / instructional** prose — textbooks, science texts, educational passages ([[sources/ej1486502]], [[sources/fpsyg-12-712901]]); plus web pages ([[sources/martin-calpena-web-comprehension-2022]]), narrative vs expository contrasts ([[sources/journal-of-educational-psychology-1999]], [[sources/ssrn-5678368]]), scientific writing ([[sources/hyatt-et-al-2017-proofreading-writing-science]]), clinical text ([[sources/soltan-2026-skimming-clinical-info-eyetracking]]), source code ([[sources/binkley-identifier-style-effort-comprehension-2012]]), infographics and digital-library records for search ([[sources/liang-2013-infographics-layout-search-eyetracking]], [[sources/capra-marchionini-structure-interaction-search]]).

**Medium:** print, desktop screen, **mobile/handheld** ([[sources/2534-handheld-whitespace-reading]], [[sources/interletter-line-spacing-reading-speed-comprehension]]), multi-slate/e-reading ([[sources/chen-multislate-active-reading]]) — with a strong screen-vs-paper thread ([[concepts/screen-vs-paper]]).

**Language / script:** mostly **English / alphabetic**, with a substantial **Chinese** cluster (on-screen proofreading, [[entities/alan-chan-cityu-group]]) and several **EFL/L2** samples (Iran, Indonesia, Iceland).

**Reader populations:** **university students** dominate; also secondary students ([[sources/kreijkes-2026-llm-notetaking-comprehension]]), EFL learners, medical students, developers, older struggling readers ([[sources/edmonds-2009-reading-interventions-synthesis]]).

**Format/length:** short-to-medium passages and articles; some textbook-length; short items for search/scanning.

### Where the findings do NOT clearly generalize (out of scope)
- **Pleasure / literary / long-form immersive** reading — essentially unstudied ([[syntheses/reading-goals-purpose-depth-map]] "enjoy" gap).
- **Children's** early-reading materials (population is mostly adults/students).
- **Non-Latin scripts beyond Chinese** (Arabic, Devanagari, etc. — thin/absent).
- **Professional/legal/financial** documents and forms.
- **Audio / multimodal / accessibility-tech** reading beyond a few accessibility-framed studies.

**Net scope statement.** *This study's readability findings apply most safely to educated adults (especially students) reading digital or print **expository/instructional** text for **comprehension, skimming, search, or proofreading** — and should be generalized cautiously to pleasure reading, children, non-Latin scripts, and professional document genres.*

## Sources & links
Anchored across the corpus; core: [[sources/kintsch-1998-comprehension]] · [[sources/tinker-1963-legibility-of-print]] · [[sources/richardson-legibility-serif-sans-serif]] · [[sources/mcnamara-2025-genai-text-personalization]]. See also [[concepts/legibility]] · [[concepts/latent-factor-matrix]] · [[concepts/text-style-vs-layout]] · [[syntheses/reading-goal-x-controlling-latent-factors]] · all four hubs.
