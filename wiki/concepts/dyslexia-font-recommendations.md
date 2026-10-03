---
type: concept
title: Dyslexia Font Recommendations
reading_tasks: [comprehension]
tags: [concept, dyslexia, typeface, accessibility, recommendation]
created: 2026-10-02
updated: 2026-10-02
source_count: 7
---

# Dyslexia Font Recommendations

## What it is
The claim that specific typefaces improve screen reading for people with dyslexia, and the question of whether any such font can be named at all. It spans empirical eye-tracking studies, personalization instruments, and clinical diagnostic work, and it is the corpus's most contested topic.

## How it's operationalized across studies
Three distinct approaches, with different epistemics:
1. **Population-level recommendation.** Rello & Baeza-Yates test 12 fonts in dyslexia samples and derive a recommended set via category contrasts and partial-order (dominance) analysis — [[sources/good-fonts-for-dyslexia]], [[sources/font-type-screen-readability-dyslexia]].
2. **Per-child objective selection.** Lorusso et al. run an objective, performance-driven procedure where reading time and error counts on nonwords/pseudosentences select each child's own best font/size/spacing — [[sources/validating-personalized-visual-auditory-parameters-dyslexia]].
3. **Biomarker-guided nomination.** İleri et al. use EOG features (reading time, blink rate, regression rate, signal energy) to rank typefaces per grade level — [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]].
4. **No-recommendation position.** Tarasov's century-spanning review finds no typeface difference on speed, comprehension, or recall, and concludes "no special type font is suggested to use in print and everyone is free to choose it themselves" — leaving familiarity and preference to decide — [[sources/tarasov-legibility-of-textbooks-2015]].

## What the evidence says

**The three approaches nominate disjoint sets of typefaces.**

| Source | Language | Signal | Nominated best |
|---|---|---|---|
| Rello & Baeza-Yates 2016 | English | fixation duration, reading time | Helvetica, CMU Sans Serif, Arial (non-dominated); Verdana, Times |
| Rello & Baeza-Yates 2013 | English | fixation duration | reduced set; Courier shortest fixation |
| İleri et al. 2025 | Turkish | EOG (time/blink/regression) | BonvenoCF, TTKB Dik Temel ABC, Times New Roman |
| Lorusso et al. 2024 | Italian | within-child accuracy/speed | none — 11 distinct fonts chosen by 49 AD children |
| Wallace et al. 2020 | English (typical adults) | WPM + comprehension | none — no consensus winner |
| Tarasov et al. 2015 | English (print, review) | speed / comprehension / recall | none — "everyone is free to choose it themselves" |

**A population-level "best font" has never replicated across studies.** No typeface is nominated by more than one independent research group in this corpus.

**The strongest shared finding is negative and methodological: within-child heterogeneity exceeds between-font variance.**
- [[sources/accelerating-adult-readers-typeface]]: **51%** within-person speed spread between a reader's own fastest and slowest font; only 18% read fastest in their preferred font.
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]]: 11 fonts selected as optimal by 49 AD children; most frequent font reaches <20% of selections; no font family differentiated the groups (`p>.05`).
- [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]]: concludes explicitly that "each child could differ individually."

**Group differences in the dyslexia *deficit* are robust; font effects within them are not.** In [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] dyslexia vs. TDC differences are significant at `p<0.0001` for reading time, blink rate, regression rate, and EOG energy — while typeface comparisons are exploratory with no pairwise statistics. In [[sources/good-fonts-for-dyslexia]] the category claim survives on fixation duration but **not** on reading time (`W=4556, p=.09`), with only 16/66 pairwise comparisons significant.

**Familiarity may drive preference without driving performance.** [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] attributes second-graders' good performance with TTKB Dik Temel ABC to it being the official Ministry of Education textbook font — a training/familiarity confound rather than a legibility property.

## Where studies disagree
- **Recommendation vs. individualization.** Rello & Baeza-Yates recommend a specific accessible set; Lorusso et al. explicitly decline to rank and report that no font exceeds 20% of selections. Same broad population (dyslexic/dyspraxic children), opposite conclusion. This is the sharpest contradiction in the corpus.
- **A fourth position, and the oldest: refuse to recommend.** Tarasov et al. surveyed roughly a century of print legibility work and found no typeface effect on speed, comprehension, or recall — so no typeface should be prescribed. Note this *predates* all four dyslexia studies above. The field's most confident recommendations are also its newest, and the prior literature review did not license them. See [[concepts/methodology-critique]].
- **Cross-script transfer is explicitly denied.** Tarasov: "very few researchers have examined non-English texts… guidelines cannot be simply applied to non-English script" because word forms, letter shapes, average word length, and connectivity all differ. This *retroactively justifies* the Turkish and Italian samples above, and predicts in advance that three language-specific sets should disagree. The corpus supports that prediction, though each study was designed for its own population rather than to test it.
- **Speed vs. fixation.** Effects are consistently robust on fixation duration and marginal or absent on reading time — the metric readers actually experience.
- **Typical vs. dyslexic readers.** Wallace et al. find heterogeneity among typical adults with no consensus font; Rello & Baeza-Yates find category-level patterns with a recommended set. These may be reconcilable (population + outcome level differ), but neither paper tests the other's population.
- **Roman vs. serif disagreement.** Rello & Baeza-Yates treat "roman" and "serif" as separate categories (roman favorable, serif unfavorable), while most public guidance treats them as one "serif" family. The category scheme is doing real work in the claim and is not standard.

## Methodological caveats that weaken every recommendation
- **Nonfactorial font bundles.** All three Rello/DyslexiaNet studies compare fonts that differ on slant, serifness, proportionation, weight, and x-height simultaneously. No single property is isolable.
- **Preference is collected but not used.** In [[sources/font-type-screen-readability-dyslexia]] dyslexic readers rated italic *more* favorably (`2.73` vs. `3.21`, `p=.002`) despite the performance pattern.
- **Text confounding.** DyslexiaNet used textbook texts from one grade *above* each participant's grade, so font conditions are entangled with text difficulty; Rello used only 12 texts.
- **Default-option bias.** In [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] sans-serif was pre-selected as the default (because it is widely recommended for dyslexia), inflating its representation; the authors concede cross-family comparison is compromised.
- **Small, single-site, single-language samples.** N=48 (2013), N=97/48-dyslexic (2016), N=23-dyslexic + 13 TDC (DyslexiaNet), N=49 AD (Lorusso). No independent replication of any recommended set.
- **Non-commensurable measurement across the whole field.** Tarasov's diagnosis is that studies are not comparable at all because font size, spacing, and line length were measured in uncoordinated units under uncontrolled lighting, and he proposes x-height in millimetres as the single typeface measure. No study in this corpus used that standard — which means the "three non-replicating sets" above may reflect measurement mismatch as much as genuine population difference. See [[concepts/methodology-critique]].

## Sources
- [[sources/font-type-screen-readability-dyslexia]] — TACCESS 2016, mixed design with control group, recommended set
- [[sources/good-fonts-for-dyslexia]] — ASSETS 2013 original, within-group only
- [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] — EOG, Turkish, BonvenoCF
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] — individualized selection, no ranking
- [[sources/accelerating-adult-readers-typeface]] — typical adults, individual variance
- [[sources/readability-research-an-interdisciplinary-approach]] — framework arguing against any single correct format
- [[sources/tarasov-legibility-of-textbooks-2015]] — century-spanning print review; no typeface effect, no recommendation, cross-script caveat

## Connections
- [[concepts/font-type-typeface]] — parent concept
- [[concepts/italic-and-slant]] — the one style-level finding that converges
- [[concepts/individual-differences-in-readability]] — the mechanism behind the heterogeneity
- [[concepts/preference-versus-effectiveness]] — why user-facing font pickers fail
- [[concepts/expertise-familiarity]] — Tarasov's and Wallace's shared explanation (familiarity, not design)
- [[concepts/methodology-critique]] — Tarasov's diagnosis that the non-replication is partly measurement failure
- [[concepts/font-size]] and [[concepts/line-spacing]] — where the *group* signal actually appeared
- [[concepts/eye-tracking-measures]], [[concepts/eog-and-physiological-signals]]
- Reading-task hub: [[syntheses/Comprehension]]

## Evidence gaps worth chasing
1. **Direct replication** of the Rello & Baeza-Yates recommended set in a second language and script.
2. **Factorial designs** separating slant, serifness, proportionation, weight, and x-height — the field cannot currently name a property, only a font.
3. **Reading time as primary outcome**, not fixation duration, at adequate power.
4. **Comprehension testing**, absent from every recommendation study here.
5. **Print vs. screen** for dyslexia font advice — the entire evidence base is screen-based, which is an odd constraint given that dyslexic children read schoolbooks in print.
6. **Re-run the whole field under a shared measurement standard** (x-height in mm, ISO 3664:2009 lighting, 0.4 m viewing distance) and see whether the three recommended sets converge. Until then the non-replication cannot be interpreted.
7. **Slant/italic is still untested by any review** — [[sources/tarasov-legibility-of-textbooks-2015]] has no italic coverage, so the corpus's most convergent finding has never been meta-analyzed.