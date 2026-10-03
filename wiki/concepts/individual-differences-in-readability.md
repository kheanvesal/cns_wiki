---
type: concept
title: Individual Differences in Readability
reading_tasks: [comprehension, proofreading, search, skimming]
tags: [concept, individual-differences, personalization, adaptability]
created: 2026-10-02
updated: 2026-10-02
source_count: 6
---

# Individual Differences in Readability

## What it is
The claim that the readability of a given text presentation depends on *who* is reading it — that within-person variance across typographic settings can exceed between-font variance across people. Its practical form is personalization: fitting presentation parameters to an individual rather than prescribing one optimum for a population.

## Scope boundary
This page is about **variance in the readability function** — the claim that there is no population-level optimum, plus the personalization designs that follow. It is not about any *one* moderator: reader expertise and stimulus familiarity keep their own page ([[concepts/expertise-familiarity]]), and the contested learning-style construct is [[concepts/cognitive-learning-style]]. The mechanism side (systems that change parameters at read time) is [[concepts/adaptive-and-personalized-typography]]. Overlap with [[concepts/preference-versus-effectiveness]] is deliberate and load-bearing — that page states the dissociation, this page states what happens when you act on it.

## How it's operationalized across studies
- **Objective within-child selection:** readers perform tasks and the system picks their best parameters — [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] (Seleggo test: reading time + examiner-scored accuracy on nonwords/pseudosentences drive font/size/spacing choice).
- **Speed-range measurement:** each reader reads in multiple fonts; the spread between their own fastest and slowest is the effect — [[sources/accelerating-adult-readers-typeface]].
- **Context-triggered adaptation:** parameters shift with situational state rather than person — [[sources/situfont-adaptive-mobile-typography-svi]] (sensor-detected SVI conditions).
- **Subjective preference:** readers pick their own font — [[sources/accelerating-adult-readers-typeface]] (double-elimination toggle tournament), [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] (TTS voice choice).
- **Simulated personalization:** an adaptive policy driven by learner mastery state — [[sources/adaptive-personalization-educational-readings-simulated]].
- **Design-space optimization per reader model:** [[sources/simulation-based-optimization-augmented-reading]] (resource-rational simulated reader, offline search + online adaptation).
- **Framework-level assertion:** [[sources/readability-research-an-interdisciplinary-approach]] argues there is no single correct format and readability must be tuned to individual and context.

## What the evidence says

**Within-person variance is large and directly measured.** In [[sources/accelerating-adult-readers-typeface]] readers averaged **303 WPM** in their preferred font and **347 WPM** in their fastest (15% faster); only **18%** read fastest in their preferred font and **23%** read *slowest* in it. Slowest-font average was 230 WPM, giving a **51% within-person spread** — the headline number of the corpus for this concept.

**Objective personalization produces measurable gains; subjective personalization does not.**
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]]: personalized vs. standard parameters, within-child, whole sample (N=78) — reading errors `2.69 → 1.63` (~39% reduction, `Z=−1.91, p=.028`); dictation accuracy `Z=−1.65, p=.0495`; reading speed `Z=−1.66, p=.049`. Gains concentrate in the dyslexic group for dictation (`Z=2.05, p=.020`) and are absent in typical readers (`Z=−0.09, p=.463`).
- [[sources/accelerating-adult-readers-typeface]]: preference *fails* — **41%** of readers scored their **lowest** comprehension in their preferred font; ~59% scored highest. Font familiarity predicted nothing (speed `r=0.042`, comprehension `r=0.033`).

This is the corpus's sharpest methodological contrast: **objective performance-based selection works; subjective preference selection does not.** Both papers collect both kinds of data, and they disagree about which matters.

**No font wins the population.** No typeface exceeded ~20% of selections among 49 AD and 29 TD children; 11 fonts were chosen as optimal in the AD group, 14 in TD. Among typical adults, top preference winners were near-tied (Noto Sans 9, Montserrat 8, Garamond 8).

**Personalization gains are domain-dependent, and can be negative.** In [[sources/adaptive-personalization-educational-readings-simulated]] adaptive reading significantly helped computer science, was inconclusive for inorganic chemistry, and was **neutral to slightly negative for biology** — with only three sampled subject ontologies and no human participants. Adaptive systems prune text based on estimated mastery; that pruning was not free.

## Where studies disagree
- **Adaptation as pure upside vs. adaptation as risky.** [[sources/situfont-adaptive-mobile-typography-svi]] reports consistent goodput improvement with comprehension flat; the paper's own limitation section notes adjustments can fire *unintentionally* during scrolling and turn adaptation into an interruption. [[sources/adaptive-personalization-educational-readings-simulated]] finds a domain where adaptation hurts. The corpus does not establish that adaptation is monotonically beneficial.
- **Preference as a route to personalization.** [[sources/accelerating-adult-readers-typeface]] says no; [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] uses subjective selection for TTS but objective selection for typography, and reports the objective route working. Notably, in that paper *visual* gains were marginal while the *auditory* dictation gain in AD was clearly significant — the personalization benefit was strongest in the modality where selection was partly subjective.
- **Human evidence vs. simulated evidence.** [[sources/simulation-based-optimization-augmented-reading]] and [[sources/adaptive-personalization-educational-readings-simulated]] substitute simulated readers for humans; both are unvalidated against real reading. The human evidence ([[sources/validating-personalized-visual-auditory-parameters-dyslexia]], [[sources/accelerating-adult-readers-typeface]]) is the only ground truth available, and it is thin.
- **Reading speed medians can be identical while a test is significant.** In Lorusso et al. the personalized and standard speed medians are both `2.85` — the effect is significant on signed-rank but invisible in central tendency. Treat speed-gain claims from that study as weak; the accuracy gain is the credible one.

## Sources
- [[sources/accelerating-adult-readers-typeface]] — 51% within-person range; preference fails
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] — objective selection works; 11 fonts in 49 children
- [[sources/situfont-adaptive-mobile-typography-svi]] — context-triggered adaptation; comprehension flat
- [[sources/adaptive-personalization-educational-readings-simulated]] — domain-dependent, one negative
- [[sources/simulation-based-optimization-augmented-reading]] — resource-rational personalization, no human data
- [[sources/readability-research-an-interdisciplinary-approach]] — framework: no single correct format

## Connections
- [[concepts/adaptive-and-personalized-typography]] — sibling concept (mechanism side)
- [[concepts/preference-versus-effectiveness]] — the dissociation this concept turns on
- [[concepts/dyslexia-font-recommendations]] — the recommendation-vs-individualization contradiction
- [[concepts/font-type-typeface]], [[concepts/font-size]], [[concepts/line-spacing]] — the parameters being personalized
- [[concepts/simulated-readers]], [[concepts/resource-rationality]]
- Reading-task hubs: all four, via [[syntheses/Comprehension]]

## Evidence gaps worth chasing
1. **Predictors of individual optimum.** No study identifies which measurable attributes (age, reading experience, vision, literacy history) map to a best format — [[sources/accelerating-adult-readers-typeface]] lists this as the open question, and it remains open across the corpus.
2. **Do personalization gains transfer?** All gains are measured in-task, immediately after selection. Nobody has tested whether an individualized setting persists over days. Note [[sources/situfont-adaptive-mobile-typography-svi]] includes a 4-day adaptation period but reports no persistence analysis.
3. **Marginal vs. absolute values.** Does a personalized format still fall short of the best achievable format for that person?
4. **Cost of adaptation.** No source quantifies the interruption cost the SituFont authors themselves identify.
5. **Simulator validation.** Whether resource-rational or C–I/BKT simulated readers reproduce the human within-person ranges above is untested and is the precondition for the simulation-based program.