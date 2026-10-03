---
type: concept
title: "Visual Search"
reading_tasks: [search, skimming]
tags: [concept, eye-tracking, fixation, search-efficiency, information-overload, layout-order, text-congruency]
created: 2026-07-26
updated: 2026-10-02
source_count: 9
---

# Visual Search

**What.** Scanning a display to locate a target; faster than reading and differently dependent on word-form/layout cues.

**Sources.** [[sources/fisher-1975-reading-visual-search]] · [[sources/tarling-2009-page-layout-visual-search]] · [[sources/zuo-2023-target-layout-graphic-search-eyetracking]] · [[sources/li-2009-web-layout-information-forms-locations]] · [[sources/lu-et-al-2011-visual-search-information-overload]] · [[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] · [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] · [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]]

## The recurring pattern: more elements cost time, but not monotonically, and not for everyone
The search cluster added in 2026-10 is consistent on direction and inconsistent on size.

- **More form fields → slower, more fixations, shorter fixations.** [[sources/li-2009-web-layout-information-forms-locations]]: as the number of fields on a registration page rose, **fixation count increased (p = .007), fixation duration decreased (p < .001), and task time increased (p = .001).** Total fixation time was unchanged (p = .085) — the users *distributed* attention over more targets rather than spending longer overall.
- **More search results → more fixations, longer fixations, longer task.** [[sources/lu-et-al-2011-visual-search-information-overload]]: increasing result count raised fixation count (p < .001) **and** fixation duration (p = .014), so the cost is multiplicative.
- **Both point the same way:** information volume degrades search efficiency monotonically. Li's participants searched a *structured form*; Lu's searched *unstructured results*. The effect survives both.

## Why it is not a simple "less is more" rule
Three findings in the cluster block a clean capacity account:

1. **Overload reversed direction at the top of the range.** [[sources/lu-et-al-2011-visual-search-information-overload]]: at 4 results fixation duration was **shorter** than at 10 (p = .028), and at 60 results it was **longer** than at 40 (p < .001). Within a rising trend there are two reversals, so "more is worse" is not true at every step. Lu et al. attribute this to search strategy changing with result count rather than to capacity being exceeded.
2. **Individual differences are as large as the layout effect.** Lu et al.'s own cluster analysis found **three distinct visual-search profiles** — text-focused, image-focused, and holistic. Reading speed differences between clusters were **larger than the differences between layouts.** Lu et al. describe them as **"non-negotiable."** Any claim that a layout is better "for readers" should name which cluster it suits.
3. **Complexity was not the operative variable in dashboards.** [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]]: layout order affected layout type (p < .001) and layout type affected **comprehension time (p = .034)**, but **layout order did not affect comprehension time directly** and did not affect search. Complexity ratings differed but **did not predict performance** (η² = .034–.083). Users adapted to unfamiliar layouts, so "complexity" as a subjective rating is a poor predictor of search cost.

## Layout order, text–graphic congruity, and the congruity caveat
- **Order matters for where the eyes go, and little else.** Zhang et al.: vertical layout order affected **fixation duration (p = .002)** but **not fixation count, saccade amplitude, or comprehension**. Layout type changed search time (p < .001) and comprehension time (p = .034) but not accuracy.
- **Text–graphic congruity speeds up search *and* reduces distraction.** Zhang et al.: matched congruity raised search efficiency (p < .001), cut fixations on the matched text (p = .004), and reduced distraction from unrelated elements (p < .001).
- **Direction and script matter.** [[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] (Arabic L1 readers searching English graphs): **script familiarity dominates direction.** Arabic readers searched vertical English text faster than horizontal; native English readers searching vertical Arabic were slower — but the author attributes the difference to **script familiarity with vertical reading**, not to vertical direction itself. See [[concepts/text-direction]].
- **Typographic variables move eye movements during webpage reading.** [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]] found **more page headers → fewer fixations (b = −0.92)**, read as *reduced second-pass reading*, alongside effects of font size, typeface, and contrast. **Correlational only** — 53 participants viewing 12 university homepages, no manipulation, and the authors do not rule out that readable pages simply get read once.

## Confounds that recur in this cluster
- **Quantity is never separated from arrangement.** Li, Lu, and Zhang all vary the number of elements; none manipulates arrangement while holding quantity fixed. [[concepts/screen-vs-paper]]'s "scrolling vs. quantity" gap is the same confound at the medium level.
- **Verbal ability tracks search performance and is seldom controlled.** Lu et al. note that field-dependent participants in their own prior work were faster searchers. Alsaffar's L1-Arabic/L2-English sample makes this acute: search speed tracked **L2 proficiency (ρ = 0.586, p = .01)**, faster searchers being the more proficient readers. **These are not layout effects.**
- **Task type is under-specified.** Alsaffar's is graph enumeration, Zhang's is target search, Lu's is result scanning, Li's is form completion. Rates are not comparable across them.
- **Statistical reporting defects.** Zhang et al. report **impossible likelihood-ratio values** — χ²(1) = 12.59, p < .05 while an η² of .000 would imply a non-significant LR — and their **"replicated interaction" is not in the table** and is described only as "similar patterns." Treat Zhang's effect sizes as unusable pending correction; their direction-of-effect conclusions are more defensible than their statistics.

## See also
[[concepts/scanning]] · [[concepts/information-density]] · [[concepts/expectancy-predictability]] · [[concepts/individual-differences-in-readability]] · [[concepts/text-graphic-integration]] · [[concepts/layout-topology]] · [[concepts/text-direction]] · [[concepts/web-layout]] · [[concepts/satisficing-foraging]] · [[concepts/method-type-divergence]] · [[syntheses/Search]] · [[syntheses/Skimming]]
