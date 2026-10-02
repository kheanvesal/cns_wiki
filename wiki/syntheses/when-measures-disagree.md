---
type: synthesis
title: "When Measures Disagree — Eye-Tracking vs. Behavioral vs. Self-Report"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, methodology, eye-tracking, self-report, measurement]
created: 2026-07-26
updated: 2026-07-26
source_count: 10
---

# When Measures Disagree — Eye-Tracking vs. Behavioral vs. Self-Report

A deep-dive expanding [[concepts/method-type-divergence]]. Across this corpus, the **same style manipulation** routinely produces **different verdicts depending on the measure**. Knowing *which* measure to trust — and for *what claim* — is essential to reading this literature correctly.

## The three measure families
- **Behavioral (product):** speed, accuracy, comprehension/detection scores. The ground truth for *effectiveness*.
- **Eye-tracking (process):** fixations, saccades, regressions, scanpaths. Reveals *how/where* effort is spent — mechanism.
- **Self-report:** comfort, preference, aesthetics, metacognitive confidence. Predicts *adoption and experience*, not performance.

## Catalogue of documented disagreements

| Manipulation | Measures that disagree | What each says | Interpretation |
|---|---|---|---|
| **Font size** | eye-tracking vs comprehension | Gaze shifts with size [[sources/beymer-font-size-type-online-reading]]; comprehension unchanged [[sources/ej1079769]] | Size eases *processing/legibility*, not understanding |
| **Line/letter spacing** | self-report vs behavioral | Comfort differs; speed & comprehension null [[sources/interletter-line-spacing-reading-speed-comprehension]] | Real experiential effect, no performance effect |
| **Reading purpose** | process vs product | Think-aloud/online behavior changes; offline scores don't [[sources/journal-of-educational-psychology-1999]] | Strategy shifts without changing the test outcome |
| **Reading goal/task** | eye-tracking vs outcome | Early, global eye-movement adjustment [[sources/reading-goal-task-eye-fixation-patterns]] | Processing is retuned even where products look similar |
| **Layout density (search)** | performance vs preference | Dense locates targets faster; sparse *preferred* [[sources/tarling-2009-page-layout-visual-search]] | Preference actively contradicts performance |
| **Proofreading display/whitespace** | performance vs preference | Objective-best ≠ preferred settings [[sources/chan-ng-display-factors-chinese-proofreading]], [[sources/2534-handheld-whitespace-reading]] | Optimizing preference can cost accuracy |
| **Screen vs paper** | self-report (metacognition) vs performance | Comprehension worse on screen, yet confidence not lower — overconfidence [[sources/clinton-2019-paper-vs-screens-meta]], [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]] | Readers *feel* fine while performing worse |
| **AI reading tool** (LLM vs note-taking) | self-report (preference) vs performance | Students **prefer** the LLM and rate it more helpful, yet note-taking yields better retention/comprehension [[sources/kreijkes-2026-llm-notetaking-comprehension]] | Preference contradicts performance (Gen-AI era) |

Gen-AI adds fresh cases: the LLM preference-vs-retention split [[sources/kreijkes-2026-llm-notetaking-comprehension]] and NLP-metric-vs-behavior gaps in personalization/layout ([[syntheses/gen-ai-and-reading]]).

**Contrast — a case of agreement:** line-spacing effects on Chinese proofreading show up in **both** behavioral detection ([[sources/chan-2014-line-length-spacing-proofreading]]) **and** eye-tracking fixations ([[sources/huang-2017-line-spacing-simplified-chinese]]). Convergence across method types is the strongest kind of evidence.

## Three kinds of disagreement
1. **Process ≠ product.** Eye-tracking / think-aloud detect changes in *how* reading happens that never reach the outcome measure (size, reading purpose, reading goal). The manipulation touched processing/effort but not the final representation.
2. **Preference ≠ performance.** Self-report and behavioral performance point opposite ways (density; proofreading settings). What people like isn't what makes them accurate/fast.
3. **Feeling ≠ knowing (miscalibration).** Metacognitive self-report is systematically wrong in a direction — screen overconfidence — so comfort/confidence can't stand in for comprehension.

## What to trust, for which claim
- **"Does it work?"** → **behavioral product** measures (comprehension, accuracy, detection). Treat these as decisive for effectiveness.
- **"Why / how does it work?"** → **eye-tracking / process** measures. Best for mechanism and for diagnosing *null* outcomes (was the effect absent, or just absorbed by strategy?).
- **"Will people use it / tolerate it?"** → **self-report**. Legitimate for adoption, fatigue, and satisfaction — but **never** as evidence of performance.
- **Strongest evidence:** **triangulation** — when process, product, and (ideally) preference converge.

## Interpretive rule of thumb
When **eye-tracking shows an effect but the outcome doesn't**, the manipulation most likely changed **surface processing/legibility/effort**, not the **[[concepts/situation-model]]** — i.e., it bought speed or comfort, not comprehension (consistent with [[sources/kintsch-1998-comprehension]] levels). When **preference and performance conflict**, choose by the goal: optimize **performance** for accuracy-critical tasks (proofreading, high-stakes comprehension), **preference** only where adoption/comfort is the point.

## Why this matters for the wiki
Every source page here flags its **method type** (per CLAUDE.md domain notes). This page is the lens for reconciling apparently contradictory findings: often they aren't contradictions at all — they're different measures answering different questions.

---
*Filed from a QUERY on 2026-07-26. Deepens [[concepts/method-type-divergence]]. Related: [[concepts/metacognitive-calibration]], [[concepts/reading-comfort-preference]], [[concepts/eye-tracking-measures]]; hubs [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]].*
