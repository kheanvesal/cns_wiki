---
type: concept
title: Preference vs. Effectiveness
reading_tasks: [comprehension]
tags: [concept, preference, self-report, comfort, individual-differences]
created: 2026-10-02
updated: 2026-10-02
source_count: 7
---

# Preference vs. Effectiveness

## What it is
The dissociation between what a reader says or prefers and what actually helps them read. Comfort, liking, familiarity, and self-reported quality are cheap to collect and tempting to use as design targets — but they are not the same quantity as speed, accuracy, or comprehension. This concept tracks the evidence on whether subjective readability judgments track objective reading performance.

## Scope boundary
This page is about the **dissociation** — the empirical claim that subjective judgments do not track objective performance. It is not the definition of the self-report measure itself; that lives in [[concepts/reading-comfort-preference]] (and [[concepts/aesthetics]] for the aesthetic subset). The eye-tracking/behavioral/self-report taxonomy behind the dissociation is in [[concepts/method-type-divergence]], and the cross-measure disagreements it produces are worked through in [[syntheses/when-measures-disagree]]. Keep those four roles distinct: this page is the *finding*, those are the *measure* and the *framework*.

## How it's operationalized across studies
- **Preference elicitation by forced choice:** double-elimination toggle tournament over 16 fonts (participant switches a locked-width interface between paired fonts and stops on the easier one) — [[sources/accelerating-adult-readers-typeface]]. Deliberately avoids Likert scales.
- **Preference ratings alongside performance:** Likert preference collected per font in the same session as fixation/reading-time measures — [[sources/font-type-screen-readability-dyslexia]], [[sources/good-fonts-for-dyslexia]].
- **Objective selection as the contrast case:** reading time and examiner-scored accuracy determine parameters, *not* liking — [[sources/validating-personalized-visual-auditory-parameters-dyslexia]].
- **Familiarity as a preference proxy:** self-reported font familiarity tested against speed and comprehension — [[sources/accelerating-adult-readers-typeface]].
- **Engagement/interest as a subjective covariate:** 5-point post-reading passage interest rating collected alongside WPM — [[sources/accelerating-adult-readers-typeface]].
- **System-level proxies:** SUS complexity/ease-of-use, UEQ efficiency/supportiveness/novelty, NASA-TLX workload — [[sources/situfont-adaptive-mobile-typography-svi]].
- **Framed as a field-level gap:** "pleasure, engagement, and preference are systematically neglected" relative to speed and accuracy — [[sources/readability-research-an-interdisciplinary-approach]].

## What the evidence says

**Preference does not predict effectiveness. This is the corpus's best-replicated finding in this area, established across populations and methods.**

- [[sources/accelerating-adult-readers-typeface]]: only **18%** read fastest in their most preferred font; **23%** read slowest in it. **41%** scored their *lowest* comprehension in their preferred font. Yet 80% of participants believed their preferred font was also their most effective.
- [[sources/font-type-screen-readability-dyslexia]]: **preference inversion for italic** — dyslexic readers rated italic `2.73` vs. roman `3.21` (`p=.002`), i.e. *more favorably*, in the same session where italic produced longer reading times.
- [[sources/good-fonts-for-dyslexia]]: collects preference but does not use it in the recommendation logic, despite the same category pattern.

**Familiarity predicts nothing.** No effect of font familiarity on reading speed (`r=0.042`) or comprehension (`r=0.033`) — [[sources/accelerating-adult-readers-typeface]]. Familiarity also failed to explain DyslexiaNet's second-grade advantage for TTKB Dik Temel ABC, which the authors attribute to textbook familiarity rather than legibility.

**Note a genuine conflict on familiarity.** [[sources/tarasov-legibility-of-textbooks-2015]] concludes that since no typeface wins, "the point to pay attention to is the familiarity of the subjects with special typefaces and subjects' preferences" — making familiarity the load-bearing residual of the whole field. [[sources/accelerating-adult-readers-typeface]] tested familiarity directly as a predictor of speed and comprehension and found nothing. **So the corpus's most-repeated hypothesis is also its least-supported**: a review asserts it, and the one direct test refutes it. Tarasov's framing is nonetheless *consistent* with the dissociation above — it hands the decision to preference, which this concept shows is a poor performance signal. Both point away from design-based prescriptions and toward "let the reader choose," for different reasons.

**Preference is a reliable measure of preference, just not of performance.** 92% of participants agreed with their final font recommendation from the toggle tournament — the instrument works; the construct it measures is simply not the one that matters.

**Objective selection outperforms subjective selection where both are available.** In [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] typography was selected by measured reading performance and produced significant within-child gains (errors `2.69 → 1.63`, `p=.028`), while TTS voice was selected subjectively and still produced the clearest group-specific benefit (AD dictation `Z=2.05, p=.020`). This is a partial exception to the dissociation and should not be overstated — the auditory benefit is a group effect in one task, not a within-person preference→performance relationship.

**Interest is a stronger speed covariate than typeface.** Participants slowed on passages they found interesting ([[sources/accelerating-adult-readers-typeface]], Fig. 4) — meaning unmoderated speed comparisons across fonts are confounded by content appeal.

## Where studies disagree / open tensions
- **Is preference worthless, or merely a poor standalone predictor?** The corpus supports "poor standalone predictor." It does **not** establish that preference carries zero information — no source tests preference *in combination with* objective measurement, which is the obvious hybrid design.
- **Workload vs. performance.** [[sources/situfont-adaptive-mobile-typography-svi]] gets significantly better self-reported workload *and* better goodput simultaneously — subjective and objective moving together, unlike the font studies. Explanation unknown; the paper does not test whether users' workload judgments track actual effort.
- **The framework paper's framing cuts against the corpus.** [[sources/readability-research-an-interdisciplinary-approach]] argues preference/pleasure are *neglected* and should be taken seriously, while [[sources/accelerating-adult-readers-typeface]] shows preference is actively misleading for performance. Both can hold: preference may matter for sustained voluntary reading (which is why "will they keep reading?" matters) while failing as a predictor of comprehension on a comprehension test. The corpus does not distinguish these.

## Why this matters for the wiki's methods
Every source page here that recommends a style variable should state whether the claim rests on eye-tracking, behavioral, or self-report data. Across this concept, the pattern is consistent: **self-report measures track preference, not performance.** Claims about what "helps readers" should not rest on self-report alone unless the claim is explicitly about comfort or engagement.

## Sources
- [[sources/accelerating-adult-readers-typeface]] — the core dissociation; familiarity null; interest confound
- [[sources/font-type-screen-readability-dyslexia]] — italic preference inversion in dyslexia
- [[sources/good-fonts-for-dyslexia]] — preference collected, not used
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] — objective selection vs. subjective TTS selection
- [[sources/situfont-adaptive-mobile-typography-svi]] — subjective and objective improve together (counterexample)
- [[sources/readability-research-an-interdisciplinary-approach]] — field-level gap claim
- [[sources/tarasov-legibility-of-textbooks-2015]] — "everyone is free to choose it themselves"; familiarity + preference as the residual

## Connections
- [[concepts/individual-differences-in-readability]] — why preference is an especially poor routing signal
- [[concepts/dyslexia-font-recommendations]] — recommendation framing vs. the dissociation
- [[concepts/expertise-familiarity]] — the assert-vs-refute tension over familiarity
- [[concepts/cognitive-load]] — the SituFont case where subjective and objective agree
- [[concepts/font-type-typeface]], [[concepts/italic-and-slant]] — the variables preference is asked about
- [[concepts/method-type-divergence]] — the eye-tracking/behavioral/self-report distinction
- Reading-task hub: [[syntheses/Comprehension]]

## Evidence gaps worth chasing
1. **Preference × performance combination** as an explicit predictor model, rather than preference alone.
2. **Does the dissociation hold for comfort/pleasure outcomes?** If preference mispredicts speed, does it still predict *enjoyment of reading* — and does enjoyment predict sustained voluntary reading behavior? This is the one place preference may be the right target.
3. **Subjective workload as an effort measure:** SituFont's workload reductions are unvalidated against objective physiological effort (pupil, blink rate, EOG energy — all available in this corpus).
4. **Expert vs. novice readers:** does the preference-performance gap narrow with reading expertise?