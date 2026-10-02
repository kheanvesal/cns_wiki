---
type: synthesis
title: "An Evidence-Based Default Screen Layout"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, recommendations, layout, design]
created: 2026-07-26
updated: 2026-07-26
source_count: 15
---

# An Evidence-Based Default Screen Layout

A practical "safe default" for on-screen text, synthesized across the corpus. It optimizes for **comprehension and legibility without a strong task assumption**, then lists how to shift the default when the dominant reading task is known. Confidence tags: **[well-supported]**, **[moderate]**, **[thin/contested]**.

## Default recommendations

| Element | Default | Confidence | Basis |
|---|---|---|---|
| **Line length** | ~55 characters per line (≈45–75) | Moderate | [[sources/dyson-haselgrove-2001-speed-linelength-screen]], [[sources/layout-on-screen]], [[sources/bringhurst-elements-of-typographic-style]] |
| **Font size** | Comfortably large (≥ ~12pt equiv.); larger for small screens | Well-supported | [[sources/ej1079769]], [[sources/beymer-font-size-type-online-reading]], [[sources/tinker-1963-legibility-of-print]] |
| **Typeface** | Any mainstream, legible face; serif vs sans is **not** decisive | Well-supported | [[sources/richardson-legibility-serif-sans-serif]], [[sources/lund-1999-knowledge-construction-typography]] |
| **Avoid disfluent fonts** | Don't use hard-to-read fonts to "aid memory" | Moderate (contested) | [[sources/dykes-sans-forgetica-readability]], [[sources/font-disfluency-online-learning-highschool]], [[sources/ssrn-5678368]] |
| **Line spacing** | Adequate leading, proportional to size/measure | Moderate | [[sources/chan-2014-line-length-spacing-proofreading]], [[sources/tinker-1963-legibility-of-print]] |
| **Case** | Sentence/mixed case; **avoid ALL-CAPS** for body text | Well-supported | [[sources/tinker-1963-legibility-of-print]], [[sources/fisher-1975-reading-visual-search]] |
| **Headings/signaling** | Clear headings aligned to text structure | Moderate | [[sources/lemarie-lorch-perywoodley-2012-headings]], [[sources/functional-headings-selective-attention]], [[sources/ej1486502]] |
| **Whitespace/margins** | Adequate margins; balance density vs. comfort | Thin | [[sources/2534-handheld-whitespace-reading]] |
| **Text + graphics** | Keep references contiguous & cued (avoid split attention) | Moderate | [[sources/mayer-fiorella-intro-multimedia-learning]], [[sources/3320435-3320447]] |
| **Navigation** | Scrolling by default; consider pagination on small screens | Moderate | [[sources/hemminger-marcial-2012-scrolling-pagination]], [[sources/chan-2014-line-length-spacing-proofreading]] |
| **Attention (long/timed reads)** | Add pacing/attention support on screen | Moderate | [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]], [[sources/clinton-2019-paper-vs-screens-meta]] |

## Shift the default by dominant task
- **Comprehension (deep read):** prioritize structure — headings, structure-aligned layout, moderate cpl; manage screen "shallowing" (attention support, or paper for high-stakes). See [[syntheses/does-style-improve-comprehension]].
- **Skimming (gist):** strong signaling/headings so satisficing readers find high-value regions fast; expect a gist-preserving speed–accuracy tradeoff. [[concepts/headings-signaling]], [[concepts/skim-comprehension-tradeoff]].
- **Search/scan (find a target):** denser layouts locate targets faster (even if users *prefer* sparse); consistent, predictable target placement. [[sources/tarling-2009-page-layout-visual-search]], [[concepts/information-density]].
- **Proofreading (error detection):** generous line spacing and fewer lines per screen aid detection; minimize scrolling; note most evidence is Chinese-script. [[sources/chan-2014-line-length-spacing-proofreading]], [[entities/alan-chan-cityu-group]].

## Gen-AI note — adaptive layout is now buildable, but unproven
LLMs can now *generate* layout from text [[sources/chen-2024-textlap-layout-planning]] and *adapt* linguistic level/cohesion to a reader profile [[sources/mcnamara-2025-genai-text-personalization]], so the "adaptive vs. fixed default" comparison the matrix flagged as untested is finally feasible. But it is still **unproven against this default**: personalization is validated by NLP metrics, not reader outcomes. And AI **summaries** — the most common LLM reading aid — can *harm* strong readers [[sources/rolle-2025-gpt-tools-comprehension]], so "let AI simplify it" is not a safe default. See [[syntheses/gen-ai-and-reading]].

## What this default deliberately does **not** claim
- That a specific typeface, exact point size, or micro-spacing materially boosts **comprehension** — those mostly buy speed/comfort ([[syntheses/does-style-improve-comprehension]]).
- That one layout serves all tasks — the same variable (e.g., density) helps search but is dis-preferred, and spacing that aids proofreading is neutral for comprehension. The **task is the moderator** ([[concepts/reading-purpose-and-goal]]).

## Confidence & caveats
- **Well-supported:** avoid ALL-CAPS; adequate size; typeface class is not decisive.
- **Moderate:** ~55 cpl optimum; headings help; screen attention penalty.
- **Thin/contested:** exact whitespace/margins; disfluency (leaning "no benefit").
- **Generalization risks:** proofreading layout evidence is mostly **Chinese** ([[entities/alan-chan-cityu-group]]); several screen studies predate modern high-DPI displays; the corpus rarely tests **interactions** or **personalized/adaptive** layout ([[concepts/latent-factor-matrix]] gaps). Treat as a *default*, not a law.

---
*Filed from a QUERY on 2026-07-26. Related: [[syntheses/does-style-improve-comprehension]], [[concepts/method-type-divergence]]; hubs [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]].*
