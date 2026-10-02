---
type: concept
title: "Critique of the Four Reading Goals"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [critique, methodology, reading-goals, taxonomy, validity]
created: 2026-07-26
updated: 2026-07-26
source_count: 0
---

# Critique of the Four Reading Goals

A validity review of the wiki's organizing spine — **comprehension, proofreading, search, skimming** (the `raw/` folders and the four hub pages). Parallel to [[concepts/latent-factor-matrix-critique]]. Grounded in an overlap analysis of the 64 source pages' `reading_tasks`.

## Verdict
A **useful, evidence-discriminating pragmatic organization** — the control signatures genuinely differ by goal ([[syntheses/reading-goal-x-controlling-latent-factors]]) — but as a *taxonomy* it mixes levels, overlaps heavily, and is incomplete relative to the corpus's own cited scheme. Keep it as the working spine; don't treat the four as a flat, exhaustive, orthogonal set.

## What holds up
- **Organizing by task, not by variable, is the right call** (the CLAUDE.md principle) and it pays off: comprehension←structure/cohesion, proofreading←spatial density, search←navigation/salience, skimming←signaling/pacing — four distinct control profiles.
- **Proofreading** is a crisp, well-bounded category.
- The four **match how the sources arrived** (the raw folders), so ingestion maps cleanly, and cross-filing is handled honestly (multi-valued `reading_tasks`) rather than hidden.

## Problems

### 1. Not parallel — mixed levels
Comprehension and skimming are points on a **depth/speed continuum** (reading *modes*); proofreading and search are **tasks**. The scheme mixes "how deeply" with "what for." Reading-to-summarize ([[sources/hyona-lorch-kaakinen-2002-reading-to-summarize]], [[sources/ej1486502]]) sits between comprehension and skimming with no natural home.

### 2. Non-orthogonal — the overlap is large (empirical)
Across the 64 source pages: **56% touch more than one goal**; only 28 are cleanly single-goal.

| Cross-filed pair | sources |
|---|---|
| **comprehension + skimming** | **25** |
| search + skimming | 11 |
| comprehension + search | 7 |
| comprehension + proofreading | 6 |

Comprehension↔skimming is the two ends of **one continuum**, so every "careful vs. skim" study files under both. Search↔skimming shows the skim/scan/search boundary is porous. The four are a continuum plus two tasks with fuzzy edges — not four disjoint bins.

### 3. "Search" is overloaded; "skimming" is a catch-all
The Search hub bundles low-level **visual search / scanning** ([[sources/fisher-1975-reading-visual-search]], [[sources/tarling-2009-page-layout-visual-search]], [[sources/zuo-2023-target-layout-graphic-search-eyetracking]]) with high-level **information-seeking** ([[sources/choo-detlor-turnbull-1999-web-browsing-searching]], [[sources/thatcher-2006-cognitive-search-strategies]], [[sources/capra-marchionini-structure-interaction-search]]) — two constructs at different grain. Skimming (32 sources) absorbs speed-reading, screen-shallowing, disfluency, and summarizing. Both categories are doing too much. (Partial fix already filed: [[syntheses/skimming-vs-scanning-vs-search]].)

### 4. Incomplete
The corpus's own cited goal taxonomy (Rouet/Choo, named in the xlsx gap analysis) is *glanceable / skim / search / deep / learn / proofread / pleasure*. Absent from the four:
- **Learning-for-retention** — durable memory and transfer, distinct from in-the-moment comprehension.
- **Pleasure / leisure** — immersive narrative reading; an **explicit corpus gap** (zero papers).
- **Scanning** — as distinct from information-seeking search.
- **Glanceable** — headlines, signage, notifications.

*Gen-AI update:* the seek-vs-comprehend distinction is now **empirically decodable from eye movements in real time** [[sources/decoding-reading-goals-eye-movements-2024]], supporting the "reading regimes" framing over a flat category list. And LLM-assisted reading is spawning arguably-new goals (delegate/ask-AI) not in any prior taxonomy — see [[syntheses/gen-ai-and-reading]].

## Recommendation
Keep the four hubs as the primary organization, but frame them within a cleaner structure:
1. A **purpose × depth map** (understand / locate / verify / enjoy × careful ↔ expeditious) that places the four goals and marks the empty cells — filed as [[syntheses/reading-goals-purpose-depth-map]].
2. Note explicitly that **Search = scanning + information-seeking** and that **comprehension↔skimming is a continuum**, so the 56% overlap reads as expected, not as a filing error.
3. Register the scope gaps (learning-for-retention, pleasure, glanceable) as "goals outside the corpus," the same way the latent-factor gaps are logged.

## See also
[[syntheses/reading-goals-purpose-depth-map]] · [[concepts/reading-purpose-and-goal]] · [[concepts/latent-factor-matrix-critique]] · hubs [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]].
