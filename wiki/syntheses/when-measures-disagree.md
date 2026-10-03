---
type: synthesis
title: "When Measures Disagree — Eye-Tracking vs. Behavioral vs. Self-Report"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [synthesis, query, methodology, eye-tracking, self-report, measurement]
created: 2026-07-26
updated: 2026-10-02
source_count: 21
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

### Added 2026-10

| Manipulation | Measures that disagree | What each says | Interpretation |
|---|---|---|---|
| **Typographic cueing / hierarchy** | **eye-tracking vs behavioral — and they diverge on the *mechanism*** | Overall fixation count and % fixated **unchanged**, but recall far higher (posttest M = 8.78 vs 5.68, p < .001); the significant tracking result was *redistribution* (AOI 6: 100% vs 62.07%, p = .0021) [[sources/lege-2019-typography-efl-eye-tracking]] | Not disagreement — **specification**. Eye-tracking showed *where* attention moved, not *how much*. A null on aggregate fixation would have been misread as a null |
| **Typeface familiarity** | self-report vs **both** other families | Familiar faces **preferred**; **no speed advantage**; **no recall benefit** (null across three experiments) [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] | Preference with nothing behind it — the cleanest "neither" case in the corpus |
| **Disfluent font** | behavioral (accuracy) vs behavioral (error detection) | Accuracy **fell** (93% → 77%, p = .039); error detection **unchanged** (p = .569, equivalence-tested) [[sources/janouskova-2022-font-readability-moses-illusion]] | Cost without benefit. Two behavioral measures, opposite verdicts on the *same* manipulation |
| **Information volume (search)** | fixation count vs fixation duration | More fields → fixations **up** but durations **down**, total fixation time unchanged (p = .085) [[sources/li-2009-web-layout-information-forms-locations]]; more results → **both** up [[sources/lu-et-al-2011-visual-search-information-overload]] | Two studies, same direction, **opposite signatures** — a single aggregate metric would hide this |
| **Medium (print vs digital)** | speed vs comprehension | Print was **much slower** (r = .91, p < .001) [[sources/breso-grancha-2022-digital-print-easy-texts]] while pooled comprehension favors print (g = −.21) [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]] | Speed and understanding can point **opposite ways** — not merely at different magnitudes |
| **Medium, first grade** | self-report vs actual comprehension | Children's *reported* comprehension tracked actual comprehension **regardless of medium**, even where actual comprehension differed [[sources/florit-2025-first-grade-comprehension-monitoring]] | Children were *not* miscalibrated about medium. See the correction below |

**⚠️ Correction to the pre-existing catalogue.** The "Screen vs paper" row above states that metacognition is *systematically* miscalibrated on screen — readers "feel fine while performing worse." **The 2026-10 ingest removes the systematicity claim.** [[sources/halamish-elbaz-2020-childrens-comprehension-metacomprehension]] found metacomprehension judgments **numerically higher on screen, not significant** (t(37) = 1.38, p = .177, d = .21), and Florit et al. found monitoring predicted comprehension across media. **No study in this corpus now shows metacognitive confidence diverging from performance by medium.** The remaining data support "monitoring tracks comprehension" and do *not* support "readers fail to notice the screen penalty." Treat the overconfidence account as an untested mechanism, not a finding — see [[concepts/metacognitive-calibration]] and [[concepts/screen-vs-paper]].

Gen-AI adds fresh cases: the LLM preference-vs-retention split [[sources/kreijkes-2026-llm-notetaking-comprehension]] and NLP-metric-vs-behavior gaps in personalization/layout ([[syntheses/gen-ai-and-reading]]).

**Contrast — a case of agreement:** line-spacing effects on Chinese proofreading show up in **both** behavioral detection ([[sources/chan-2014-line-length-spacing-proofreading]]) **and** eye-tracking fixations ([[sources/huang-2017-line-spacing-simplified-chinese]]). Convergence across method types is the strongest kind of evidence.

## Three kinds of disagreement
1. **Process ≠ product.** Eye-tracking / think-aloud detect changes in *how* reading happens that never reach the outcome measure (size, reading purpose, reading goal). The manipulation touched processing/effort but not the final representation.
2. **Preference ≠ performance.** Self-report and behavioral performance point opposite ways (density; proofreading settings). What people like isn't what makes them accurate/fast.
3. **Feeling ≠ knowing (miscalibration).** ~~Metacognitive self-report is systematically wrong in a direction — screen overconfidence — so comfort/confidence can't stand in for comprehension.~~ **Revised 2026-10:** the *systematic* screen-overconfidence claim is **not supported by this corpus**. The only direct test is a null (p = .177), and first graders monitored comprehension accurately across media. What survives is the weaker, methodological point: **self-report and performance are different constructs and must not be substituted for one another**, which is now argued on measurement grounds rather than on an empirical overconfidence effect. See [[concepts/method-type-divergence]].

**★ A fourth kind, added 2026-10: aggregate vs. partitioned measures.** Lege et al.'s fixation result was null in aggregate and strong when partitioned by AOI; Lu et al. and Li et al. produced opposite signatures across fixation count and duration. **A summary statistic over eye movements can hide an effect that a partitioned one reveals.** This is a reporting practice, not a construct disagreement, and it cuts against the grain of the usual "prefer behavioral measures" rule — sometimes the behavioral summary is the one that is uninformative.

## What to trust, for which claim
- **"Does it work?"** → **behavioral product** measures (comprehension, accuracy, detection). Treat these as decisive for effectiveness.
- **"Why / how does it work?"** → **eye-tracking / process** measures. Best for mechanism and for diagnosing *null* outcomes (was the effect absent, or just absorbed by strategy?).
- **"Will people use it / tolerate it?"** → **self-report**. Legitimate for adoption, fatigue, and satisfaction — but **never** as evidence of performance.
- **Strongest evidence:** **triangulation** — when process, product, and (ideally) preference converge.

## Interpretive rule of thumb
When **eye-tracking shows an effect but the outcome doesn't**, the manipulation most likely changed **surface processing/legibility/effort**, not the **[[concepts/situation-model]]** — i.e., it bought speed or comfort, not comprehension (consistent with [[sources/kintsch-1998-comprehension]] levels). **★ But check the reverse case first:** [[sources/lege-2019-typography-efl-eye-tracking]] shows a large outcome effect with a *null* aggregate eye-tracking result, where the eye-movement evidence existed at the AOI level. Before concluding "process moved, product didn't," check whether the process measure was aggregated.

When **preference and performance conflict**, choose by the goal: optimize **performance** for accuracy-critical tasks (proofreading, high-stakes comprehension), **preference** only where adoption/comfort is the point. **★ And note the third possibility, now realized:** they can *both* be absent — familiarity produced preference with no speed and no recall benefit [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] — in which case optimizing for either buys nothing.

## Why this matters for the wiki
Every source page here flags its **method type** (per CLAUDE.md domain notes). This page is the lens for reconciling apparently contradictory findings: often they aren't contradictions at all — they're different measures answering different questions.

**★ Third-party confirmation.** [[sources/arya-2023-assessment-methods-readability-legibility]] — a PRISMA systematic review of 49 studies — independently organizes the field into three families (**formula-based, eye-tracking, subjective rating**) and reaches the same verdict that they diverge. It also identifies a **fourth** family this wiki had not tracked: **readability formulas**, which score text complexity but not typographic or digital complexity, so they cannot adjudicate any of these questions. Its finding that subjective ratings "capture user perspectives that quantitative metrics overlook" is compatible with the preference≠performance rows above — subjective data is informative about comfort and uninformative about performance.

---
*Filed from a QUERY on 2026-07-26; catalogue extended and one row corrected 2026-10-02. Deepens [[concepts/method-type-divergence]]. Related: [[concepts/metacognitive-calibration]], [[concepts/reading-comfort-preference]], [[concepts/eye-tracking-measures]], [[concepts/screen-vs-paper]], [[concepts/legibility]]; hubs [[syntheses/Comprehension]] · [[syntheses/Proofreading]] · [[syntheses/Search]] · [[syntheses/Skimming]].*
