---
type: synthesis
title: "Reading-Goal × Controlling Latent Factors"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, latent-factors, control, matrix, cross-hub]
created: 2026-07-26
updated: 2026-10-02
source_count: 41
---

# Reading-Goal × Controlling Latent Factors

The abstraction of [[syntheses/reading-goal-x-text-style-matrix]]. That matrix listed *observable* style variables; here we roll them up into the **12 latent factors** of [[concepts/latent-factor-matrix]] (V1–V6 visual, L1–L6 linguistic — **definitions + examples: [[concepts/latent-factor-definitions]]**) and ask a sharper question: **which latent factors *control* the outcome for each reading goal?** — not which are *studied*, but which actually govern performance.

**Control legend.** ● controlling (varying it moves the outcome) · ◐ modulating (secondary/conditional) · ○ weak/neutral (studied but doesn't move the outcome) · — untested here.
**Engagement** = how often the factor is **manipulated as a core independent variable** for that goal — High-coded studies only, *mentions/reviews excluded* (per the [[concepts/latent-factor-matrix-critique]] fix): **▓** ≥3 studies · **▒** 1–2 · **░** none.

> **Revised 2026-07-26 per critique:** engagement recomputed on manipulated-IV-only (was weighted H/M/L, which inflated attention with mentions); **V5 and L5 merged** into one text-structure row (r=+0.66 — they were the same construct coded twice); L-block non-independence noted below.

## Control matrix

| Latent factor | Comprehension | Proofreading | Search | Skimming |
|---|---|---|---|---|
| **V1 Spatial density** (cpl, spacing, margins) | ◐ ▓ | **● ▓** | ● ▒ | ◐ ▓ |
| **V2 Glyph legibility** (typeface, size, disfluency, case) | ○ ▓ | ◐ ▓ | ◐ ▒ | ○ ▓ |
| **V3 Salience distribution** (emphasis, cueing) | ◐ ░ → **◐ ▒** | ◐ ░ | ● ▒ | ● ▒ |
| **V4 Temporal presentation** (pacing, timing) | ◐ ░ | ◐ ▒ | — ░ | ● ▒ |
| **V5 ⊕ L5 Text structure** (layout mapping + rhetorical scaffolding — *one construct, r=+0.66*) | ● ▓ | ◐ ░ | ● ▓ | ● ▓ |
| **V6 Navigation structure** (scroll↔page↔linked↔tiered) | ○ ░ | ◐ ▒ | ● ▒ | ◐ ▓ |
| **L1 Lexical sophistication** | ◐ ░ | ○ ▒ | ○ ░ | ◐ ░ |
| **L2 Syntactic complexity** | ◐* ░ | — ░ | — ░ | ◐* ░ |
| **L3 Cohesion** | ● ▒ | ○ ░ | ◐ ▒ | ◐ ▒ |
| **L4 Compression** | ◐* ░ | — ░ | ◐ ░ | ●* ░ |
| **L6 Narrativity / genre** | ◐ ▒ | — ░ | — ░ | ◐ ░ |

`▒` on V3/comprehension was upgraded 2026-10 by [[sources/lege-2019-typography-efl-eye-tracking]] (manipulated cueing, recall p < .001). **All 12 factors and their definitions are unchanged** — this ingest altered control ratings and engagement coding only, never the factor set. See [[concepts/latent-factor-definitions]].

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

**★ Upgraded 2026-10, and the script caveat is partly lifted.** [[sources/porte-2001-typographical-error-salience-l2]] manipulated **line length alone** (font, size, spacing, print quality and margins all fixed) in Spanish L2 writers and found **ω² = .42** — 42% of the variance in error recognition, the corpus's largest single-source effect in proofreading, from an isolated variable in a non-Chinese script. **V1 goes ◐ → ● for proofreading.**

- **The control is non-monotonic**, which this framework has no way to express: an inverted U peaking at ≈45 cpl with a *decline* at 35. V1 is not "more spatial granularity is better" but "there is an optimum, and it is task-specific." **Flagged as a coding-schema limitation** — ◐/● cannot represent "controlling with an interior optimum." See [[concepts/line-length]].
- **Porte's ~51% detection ceiling** shows V1 moves a great deal without clearing the skill floor, so V1 is controlling *conditional on* reader skill (L1), not instead of it.
- **Counter-instance within V2:** [[sources/janouskova-2022-font-readability-moses-illusion]] shows a disfluent font *lowering* accuracy (p = .039) while leaving error detection unchanged (p = .569, equivalence-tested). So glyph-level difficulty harms without producing reflection — reinforcing V2 as threshold/○ rather than controlling.

**Search → V6 + V5 + V3 + V1 (navigation, structure, salience, density).** Locating information is controlled by **navigation structure** and **layout-structure mapping**, plus **target salience** and **density**: [[sources/capra-marchionini-structure-interaction-search]], [[sources/hemminger-marcial-2012-scrolling-pagination]], [[sources/liang-2013-infographics-layout-search-eyetracking]], [[sources/tarling-2009-page-layout-visual-search]], [[sources/fisher-1975-reading-visual-search]]. Linguistic factors are nearly irrelevant.

**★ Sharpened 2026-10: V1's search effect is *volume*, and it is confounded with V5.** The four new search studies agree on direction and disagree on mechanism:

- **Quantity raises search cost monotonically** — more form fields → more fixations, shorter fixations, longer task, total fixation time *unchanged* [[sources/li-2009-web-layout-information-forms-locations]]; more results → more *and* longer fixations [[sources/lu-et-al-2011-visual-search-information-overload]]. Two different signatures (subtractive vs. multiplicative), suggesting task-presentation differences.
- **But non-monotonically** — Lu et al. found duration *shorter* at 4 results than at 10 (p = .028) and *longer* at 60 than at 40 (p < .001).
- **★ V5 and V1 are not separated in any of these studies.** All vary element count; none varies arrangement at constant count. So the "V1 controls search" claim is really "V1 *and possibly* V5 control search, and no study can tell you which." This is now the framework's clearest unresolved coding question.
- **★ V3/V6 additions:** text–graphic congruity raised search efficiency (p < .001) and reduced distraction (p < .001) [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]]; more headers → fewer fixations (b = −0.92) [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]].
- **★ Reader-level factors outrank layout:** Lu et al.'s three visual-search clusters differ in reading speed **more than the layouts do**, described as "non-negotiable" — so V1/V5 control ratings may need to be cluster-conditional. See [[concepts/individual-differences-in-readability]].

**Skimming → V3 + V4 + text structure (V5/L5).** Gist reading is controlled by **signaling/salience** that marks high-value regions, by **temporal presentation** (time pressure triggers satisficing), and by **text structure**: [[sources/duggan-payne-2011-skim-satisficing]], [[sources/lemarie-lorch-perywoodley-2012-headings]], [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]]. The deep theoretical driver is **L4 Compression** (gist = compressing text to its core) — but it is only ever measured as an *outcome*, never manipulated. See [[syntheses/skimming-vs-scanning-vs-search]].

## The central finding: coverage ≠ control
- **V2 Glyph legibility is over-studied relative to its control** — and this survives the stricter recompute **and** the 2026-10 ingest. Even counting *manipulations only*, V2 is the most-manipulated factor (skimming: 9 studies) yet it is ○/◐ for three of four goals. Legibility is a **threshold** variable — below it, everything fails; above it, more legibility buys speed/comfort, not outcome. The biggest misallocation of research effort in the corpus.
  - **★ The 2026-10 batch adds the sharpest available test of the threshold claim and it holds.** [[sources/janouskova-2022-font-readability-moses-illusion]] pushed legibility *down* and found the predicted cost (accuracy 93% → 77%, p = .039) with **no compensating benefit** on the reflective outcome (p = .569, equivalence-tested). Threshold variable behaving like a threshold: crossing it costs you, and there is no upside to collect. [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] adds that the most-studied typeface variable — *familiarity* — yields preference without speed or recall benefit. Together: **V2 buys comfort, not comprehension, and this corpus now has positive evidence for both halves.**
- **★ New structural caveat on V5.** [[sources/lege-2019-typography-efl-eye-tracking]] manipulated typographic hierarchy with **21 simultaneous changes** and produced the corpus's best comprehension/recall result for V5 (p < .001). It therefore supports V5 as controlling but **cannot attribute the effect to layout mapping specifically** — bold, colour, size and baseline shift are not separable. Since V5⊕L5 is already a merged construct (r = +0.66), this adds a second, independent reason to treat that row as a composite rather than a factor.
- **The controlling factors are structural and situational**, not typographic: text structure (V5/L5), V3 (salience), V6 (navigation), V4 (temporal), and — for comprehension — cohesion (L3). This is the [[concepts/text-style-vs-layout]] split stated in factor terms: **glyph-level = threshold; layout = control.**
- **Controlling-but-untested cells (`*`)** are the highest-value research gaps: **L2 syntactic complexity** (should govern comprehension/skim, never varied) and **L4 compression** (the mechanism of skimming, only ever an outcome). Matches the xlsx "Missing Innovations" list ([[concepts/latent-factor-matrix]]). **Gen-AI is now closing the L4 gap** (AI summaries manipulate compression — [[syntheses/gen-ai-and-reading]]); L2 remains genuinely untested.
- **Each goal has a distinct control signature**, so a layout tuned by latent factor should target a *different* factor per goal — comprehension: fix structure/cohesion; proofreading: tune spatial density; search: engineer navigation+salience; skimming: engineer salience+pacing.

## Caveats
- "Control" here is inferred from effect-direction evidence in the source pages, much of it single-study; ● vs ◐ for thinly-studied cells is provisional. **★ The 2026-10 batch increased both the strongest and the weakest cells while adding no replications**, so the framework is now simultaneously better-evidenced at its extremes and no better in its middle.
- **★ The coding scheme cannot represent non-monotonic control.** Porte's inverted U in V1/proofreading is genuinely "controlling with an interior optimum," which ◐/●/○ cannot say. Same issue for Lu et al.'s mid-range reversals in V1/search. Recommend adding a **non-monotone marker** (`◐ᇰ`) rather than forcing these cells into a directional code. **Not applied yet** — flagging for review rather than changing the scheme unilaterally.
- Engagement (▓▒░) now counts **manipulated-IV studies only** (mentions/reviews excluded) — this is the fix for the earlier inflation flagged in [[concepts/latent-factor-matrix-critique]]. The **control** ratings (●◐○) come from source-page effect directions and are independent of the coding.
- V5/L5 are **merged** here (r=+0.66); the L-block is treated as non-independent (see note above). Both are provisional workarounds — a proper fix is a revised coding scheme (see the critique's recommendations). **★ The Lege cue-bundle finding is a second, independent argument for demerging or explicitly marking the composite.**
- The corpus rarely crosses two factors in one study, so **interaction control** (does V5 only help when V2 is above threshold?) is essentially untested. **★ Still true, and the 2026-10 batch makes it worse**: Lege bundles 21 changes, which is the opposite of factor isolation — a manipulation that varies V1, V2, V3 and V5 simultaneously and therefore contributes nothing to interaction control.
- **★ V1/V5 non-separability in search** (see above) is a coding problem, not a coverage gap: the studies exist, but they cannot attribute effects to one factor.

---
*Filed from a QUERY on 2026-07-26 (transform of [[syntheses/reading-goal-x-text-style-matrix]]); control ratings revised 2026-10-02. Grounds: xlsx per-folder factor engagement + source-page effect directions. Related: [[concepts/latent-factor-matrix]], [[syntheses/does-style-improve-comprehension]], [[syntheses/when-measures-disagree]], [[syntheses/legibility-measurement-standard]]. Hubs: [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]].*
