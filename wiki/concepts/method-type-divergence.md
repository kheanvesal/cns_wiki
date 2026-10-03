---
type: concept
title: "Method-Type Divergence (behavioral vs. eye-tracking vs. self-report)"
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [methodology, self-report, eye-tracking, behavioral, preference-vs-performance]
created: 2026-07-26
updated: 2026-10-02
source_count: 20
---

# Method-Type Divergence

**What it is.** The three dominant measure types in this corpus — **behavioral** (speed, accuracy), **eye-tracking** (fixations, saccades, regressions), and **self-report** (comfort, preference, aesthetics) — frequently **disagree** for the same manipulation. A style change can shift preference without shifting performance, or move eye movements without moving test scores.

**Instances in the corpus.**
- Spacing changes **comfort** but not speed/comprehension [[sources/interletter-line-spacing-reading-speed-comprehension]].
- Reading purpose changes **think-aloud** behavior but not offline comprehension [[sources/journal-of-educational-psychology-1999]].
- Sparse layouts **preferred**, dense layouts **faster** [[sources/tarling-2009-page-layout-visual-search]].
- Proofreading: performance-optimal ≠ preferred settings [[sources/chan-ng-display-factors-chinese-proofreading]] · [[sources/2534-handheld-whitespace-reading]].
- Font effects visible in **gaze** but weak in outcomes [[sources/beymer-font-size-type-online-reading]].
- Screen vs paper: comprehension gap + **metacognitive miscalibration** (feel fine, perform worse) [[sources/clinton-2019-paper-vs-screens-meta]] · [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]].
- AI reading tools: students **prefer** the LLM while note-taking gives better retention [[sources/kreijkes-2026-llm-notetaking-comprehension]] (Gen-AI-era preference≠performance).
- Context-adaptive mobile typography improves **goodput and self-reported workload together** while comprehension accuracy stays **flat** — speed/subjective gain, comprehension null [[sources/situfont-adaptive-mobile-typography-svi]].
- Dyslexia typeface advice: effects robust on **fixation duration**, marginal/absent on **reading time** (only 16/66 pairwise significant) [[sources/good-fonts-for-dyslexia]]; italic penalty significant in non-dyslexic readers (`p<.001`) but not dyslexic ones (`p=.120`) [[sources/font-type-screen-readability-dyslexia]].
- Simulated personalized reading improves **accuracy** (errors `2.69→1.63`) with no speed gain [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] — accuracy-motivated, not speed-motivated, personalization.

### New instances (2026-10 ingest)
- **A null eye-movement result alongside a large behavioral effect.** [[sources/lege-2019-typography-efl-eye-tracking]]: typographic cueing produced much better recall (total posttest M = 8.78 vs 5.68, p < .001) with **no difference in average fixations or overall percent fixated** (67.38% vs 64.66%, null). The significant eye-tracking finding was *redistribution* — AOI 6, the region carrying multiple cues, was fixated by 100% vs 62.07% (p = .0021). **Eyeballs did not work more; they worked somewhere else.**
- **Preferred but not faster.** [[sources/ho-sang-petrarca-2025-beyond-typeface-value]]: participants preferred familiar sans faces; those same faces were **not faster**. Preference and speed dissociate in the direction that matters for design guidance — people choose what is not measurably better for them.
- **Speed and comprehension move in opposite directions across media.** [[sources/breso-grancha-2022-digital-print-easy-texts]]: print was **much slower** than digital (r = .91, p < .001), i.e. the opposite of the usual digital-faster assumption, while the comprehension advantage sits with print per the pooled estimate. Speed and understanding are not merely differently sensitive — they can point opposite ways.
- **A positive comprehension effect from a font manipulation that produced the *opposite* of its intended cost.** [[sources/diemand-yauman-oppenheimer-fortune-favors-bold]]'s disfluent fonts *slowed* reading while *improving* retention — the only corpus instance where a cost and a benefit are demonstrated in the same study, making it the cleanest test of whether disfluency is a trade.
- **Disfluency cost without benefit.** [[sources/janouskova-2022-font-readability-moses-illusion]]: hard font lowered factual accuracy (p = .039) while leaving error detection unchanged (p = .569, equivalence-established). Performance measure and the target reflective behavior diverged.
- **Self-reported comprehension diverges from actual comprehension by medium.** [[sources/florit-2025-first-grade-comprehension-monitoring]]: children reported their comprehension similarly across media, while actual comprehension (especially inferential) differed — a comprehension-level × self-report divergence not previously in the corpus.

## The taxonomy that makes this page predictable
[[sources/arya-2023-assessment-methods-readability-legibility]] — a PRISMA systematic review of **49 studies** (2015–2023) — organizes the entire field into three method families: **formula-based, eye-tracking, and subjective rating.** That is effectively behavioral / eye-tracking / self-report, and it independently arrives at this page's premise. Its finding that **subjective ratings "capture user perspectives that quantitative metrics overlook"** is compatible with [[concepts/preference-versus-effectiveness]]: subjective data can be informative about comfort while being uninformative about comprehension. Both claims are true simultaneously.

Its companion finding is the negative half: **formula-based readability measures (Flesch, Flesch–Kincaid, Fog, SMOG) do not capture modern digital typography** — they score text complexity, not typographic or digital complexity. Every "formula said X but the study found Y" instance on this page is predicted by that.

## The general law: typography moves speed more than it moves understanding
The corpus's century-scale review states this as a finding rather than inferring it from divergences: reading speed, "the main predictor of legibility," is **"more sensitive to typographical factors rather than to comprehension and recall"** [[sources/tarasov-legibility-of-textbooks-2015]]. Every instance above is consistent with it.

**Consequence for interpreting this corpus.** Typography studies that report only speed are measuring the most *reactive* outcome, and the literature is heavily skewed toward that outcome. A null on comprehension is therefore not evidence of "no effect" in the everyday sense — it is evidence that the outcome least sensitive to typography was used. Claims of the form "variable X improves reading" should always name the measure. Tarasov's corollary is that legibility is often operationalized as speed at all ("legibility = read rapidly and easily," after Hughes & Wilkins), which likely explains why the field's headline variable and its most-studied outcome are entangled.

**Implication.** Always record *which* measure a claim rests on (see CLAUDE.md domain notes). Preference/comfort is not evidence of performance, and vice versa. And: when a typography claim is silent on comprehension, treat it as untested on comprehension rather than as a null.

**Deep-dive.** [[syntheses/when-measures-disagree]] — full catalogue of disagreements + what to trust for which claim.

**See also.** [[concepts/reading-comfort-preference]] · [[concepts/metacognitive-calibration]] · [[concepts/eye-tracking-measures]] · [[concepts/methodology-critique]] · [[concepts/legibility]] · [[concepts/readability]] · [[concepts/error-detection]] · [[concepts/preference-versus-effectiveness]] · [[concepts/reading-speed]] · all four hubs.
