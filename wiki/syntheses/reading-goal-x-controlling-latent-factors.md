---
type: synthesis
title: "Reading-Goal × Controlling Latent Factors"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, latent-factors, control, matrix, cross-hub]
created: 2026-07-26
updated: 2026-07-26
source_count: 30
---

# Reading-Goal × Controlling Latent Factors

The abstraction of [[syntheses/reading-goal-x-text-style-matrix]]. That matrix listed *observable* style variables; here we roll them up into the **12 latent factors** of [[concepts/latent-factor-matrix]] (V1–V6 visual, L1–L6 linguistic — **definitions + examples: [[concepts/latent-factor-definitions]]**) and ask a sharper question: **which latent factors *control* the outcome for each reading goal?** — not which are *studied*, but which actually govern performance.

**Control legend.** ● controlling (varying it moves the outcome) · ◐ modulating (secondary/conditional) · ○ weak/neutral (studied but doesn't move the outcome) · — untested here.
**Engagement** = how often the factor is **manipulated as a core independent variable** for that goal — High-coded studies only, *mentions/reviews excluded* (per the [[concepts/latent-factor-matrix-critique]] fix): **▓** ≥3 studies · **▒** 1–2 · **░** none.

> **Revised 2026-07-26 per critique:** engagement recomputed on manipulated-IV-only (was weighted H/M/L, which inflated attention with mentions); **V5 and L5 merged** into one text-structure row (r=+0.66 — they were the same construct coded twice); L-block non-independence noted below.

## Control matrix

| Latent factor | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **V1 Spatial density** (cpl, spacing, margins) | ◐ ▓ | ● ▓ | ● ▒ | ◐ ▓ |
| **V2 Glyph legibility** (typeface, size, disfluency, case) | ○ ▓ | ◐ ▓ | ◐ ▒ | ○ ▓ |
| **V3 Salience distribution** (emphasis, cueing) | ◐ ░ | ◐ ░ | ● ▒ | ● ▒ |
| **V4 Temporal presentation** (pacing, timing) | ◐ ░ | ◐ ▒ | — ░ | ● ▒ |
| **V5 ⊕ L5 Text structure** (layout mapping + rhetorical scaffolding — *one construct, r=+0.66*) | ● ▓ | ◐ ░ | ● ▓ | ● ▓ |
| **V6 Navigation structure** (scroll↔page↔linked↔tiered) | ○ ░ | ◐ ▒ | ● ▒ | ◐ ▓ |
| **L1 Lexical sophistication** | ◐ ░ | ○ ▒ | ○ ░ | ◐ ░ |
| **L2 Syntactic complexity** | ◐* ░ | — ░ | — ░ | ◐* ░ |
| **L3 Cohesion** | ● ▒ | ○ ░ | ◐ ▒ | ◐ ▒ |
| **L4 Compression** | ◐* ░ | — ░ | ◐ ░ | ●* ░ |
| **L6 Narrativity / genre** | ◐ ▒ | — ░ | — ░ | ◐ ░ |

`*` = **controlling-but-untested**: theory says it should govern the outcome, but the corpus never varies it as an independent variable (see gaps).

> **L-block non-independence.** L1/L2/L3/L5 are strongly inter-correlated (L1–L2 +0.64, L2–L3 +0.60, L3–L5 +0.53) — the six linguistic "factors" behave like ~1–2 underlying dimensions, not six. Read the L-rows as facets of "linguistic difficulty/structure," not orthogonal levers.

### What the manipulated-only recompute changed
Dropping mentions **shrinks the situational and linguistic shades** while leaving genuinely-manipulated visual factors intact — the inflation the critique predicted:
- **V3 (salience)** and **V4 (temporal)** for skimming fall ▓→▒ (skim V4: 9 mentions but only 1 manipulation; V3: 9→1).
- **V6 (navigation)** for search falls ▓→▒ (9→2).
- **V2 (glyph legibility)** stays ▓ — it is genuinely the most-manipulated factor (skimming: 9 studies), which *sharpens* the coverage≠control finding: the most-manipulated factor has the weakest control.
- **L4 (compression)** is manipulated **zero** times in the 63-paper xlsx corpus — confirming its `*` controlling-but-untested status. *(Gen-AI update: the new LLM-summary studies now manipulate compression as an input and find real, ability-dependent comprehension effects — [[sources/rolle-2025-gpt-tools-comprehension]], [[sources/kreijkes-2026-llm-notetaking-comprehension]]; see [[syntheses/gen-ai-and-reading]]. L4 is moving from untested to emerging.)*

## Controlling-factor signature per goal

**Comprehension → text structure (V5/L5) + L3 cohesion.** Deep understanding is controlled by **cohesion** plus the merged **text-structure** factor (rhetorical scaffolding and its layout mapping — headings/organizers): [[sources/kintsch-1998-comprehension]], [[sources/ej1486502]], [[sources/lemarie-lorch-perywoodley-2012-headings]], [[sources/18_63]]. Glyph legibility (V2) is the *most-engaged* factor yet only ○ — it sets a floor, not a ceiling ([[sources/ej1079769]], [[sources/richardson-legibility-serif-sans-serif]]). See [[syntheses/does-style-improve-comprehension]].

**Proofreading → V1 (low-level spatial density).** Error detection is controlled by **line spacing / line number / line length**, with V2 and V6 (scrolling) modulating: [[sources/chan-2014-line-length-spacing-proofreading]], [[sources/huang-2017-line-spacing-simplified-chinese]]. Linguistic factors barely matter for surface error-spotting. Caveat: evidence is almost all Chinese-script ([[entities/alan-chan-cityu-group]]).

**Search → V6 + V5 + V3 + V1 (navigation, structure, salience, density).** Locating information is controlled by **navigation structure** and **layout-structure mapping**, plus **target salience** and **density**: [[sources/capra-marchionini-structure-interaction-search]], [[sources/hemminger-marcial-2012-scrolling-pagination]], [[sources/liang-2013-infographics-layout-search-eyetracking]], [[sources/tarling-2009-page-layout-visual-search]], [[sources/fisher-1975-reading-visual-search]]. Linguistic factors are nearly irrelevant.

**Skimming → V3 + V4 + text structure (V5/L5).** Gist reading is controlled by **signaling/salience** that marks high-value regions, by **temporal presentation** (time pressure triggers satisficing), and by **text structure**: [[sources/duggan-payne-2011-skim-satisficing]], [[sources/lemarie-lorch-perywoodley-2012-headings]], [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]]. The deep theoretical driver is **L4 Compression** (gist = compressing text to its core) — but it is only ever measured as an *outcome*, never manipulated. See [[syntheses/skimming-vs-scanning-vs-search]].

## The central finding: coverage ≠ control
- **V2 Glyph legibility is over-studied relative to its control** — and this survives the stricter recompute. Even counting *manipulations only*, V2 is the most-manipulated factor (skimming: 9 studies) yet it is ○/◐ for three of four goals. Legibility is a **threshold** variable — below it, everything fails; above it, more legibility buys speed/comfort, not outcome. The biggest misallocation of research effort in the corpus.
- **The controlling factors are structural and situational**, not typographic: text structure (V5/L5), V3 (salience), V6 (navigation), V4 (temporal), and — for comprehension — cohesion (L3). This is the [[concepts/text-style-vs-layout]] split stated in factor terms: **glyph-level = threshold; layout = control.**
- **Controlling-but-untested cells (`*`)** are the highest-value research gaps: **L2 syntactic complexity** (should govern comprehension/skim, never varied) and **L4 compression** (the mechanism of skimming, only ever an outcome). Matches the xlsx "Missing Innovations" list ([[concepts/latent-factor-matrix]]). **Gen-AI is now closing the L4 gap** (AI summaries manipulate compression — [[syntheses/gen-ai-and-reading]]); L2 remains genuinely untested.
- **Each goal has a distinct control signature**, so a layout tuned by latent factor should target a *different* factor per goal — comprehension: fix structure/cohesion; proofreading: tune spatial density; search: engineer navigation+salience; skimming: engineer salience+pacing.

## Caveats
- "Control" here is inferred from effect-direction evidence in the source pages, much of it single-study; ● vs ◐ for thinly-studied cells is provisional.
- Engagement (▓▒░) now counts **manipulated-IV studies only** (mentions/reviews excluded) — this is the fix for the earlier inflation flagged in [[concepts/latent-factor-matrix-critique]]. The **control** ratings (●◐○) come from source-page effect directions and are independent of the coding.
- V5/L5 are **merged** here (r=+0.66); the L-block is treated as non-independent (see note above). Both are provisional workarounds — a proper fix is a revised coding scheme (see the critique's recommendations).
- The corpus rarely crosses two factors in one study, so **interaction control** (does V5 only help when V2 is above threshold?) is essentially untested.

---
*Filed from a QUERY on 2026-07-26 (transform of [[syntheses/reading-goal-x-text-style-matrix]]). Grounds: xlsx per-folder factor engagement + source-page effect directions. Related: [[concepts/latent-factor-matrix]], [[syntheses/does-style-improve-comprehension]], [[syntheses/when-measures-disagree]]. Hubs: [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]].*
