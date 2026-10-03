---
type: synthesis
title: "Search — Reading-Task Hub"
reading_tasks: [search]
tags: [hub]
created: 2026-07-26
updated: 2026-10-02
source_count: 18
---

# Search — Reading-Task Hub

How text style, layout, and structure affect **locating specific information** — visual search for targets and information-seeking. Search is fast, selective, and goal-driven; it uses text differently from linear reading ([[sources/fisher-1975-reading-visual-search]]: search ~2–2.5× faster than reading, and less dependent on the word-shape/boundary cues that reading needs).

## Layout & typographic effects on visual search
- **Density:** dense layouts locate targets **faster** (fewer, longer fixations) even though readers *prefer* sparse layouts — a preference≠performance split [[sources/tarling-2009-page-layout-visual-search]].
- **Word boundary / word shape:** degrading inter-word spacing or altering case slows search, but the Type×Space interaction hits **reading more than search** [[sources/fisher-1975-reading-visual-search]].
- **Graphic/infographic topology:** linear ≈ radial for simple location, but **radial beats linear** when the task needs value comparison [[sources/liang-2013-infographics-layout-search-eyetracking]]; icon graphic type is neutral for **familiar** icons [[sources/zuo-2023-target-layout-graphic-search-eyetracking]]. → Layout benefit is **task-dependent**.
- **Expectancy/predictability:** expected, predictable targets are found faster (top-down guidance) [[sources/fisher-1975-reading-visual-search]].

## ★ Information volume: the strongest and most consistent new direction
Four 2026-10 additions all point the same way — more competing elements cost search efficiency — but none of them permits a simple "less is more" rule.

- **More form fields → more fixations, shorter fixations, longer task.** [[sources/li-2009-web-layout-information-forms-locations]]: field count rose → fixation count up (p = .007), **fixation duration down (p < .001)**, task time up (p = .001). Total fixation time **unchanged** (p = .085). Users *spread* attention over more targets rather than spending longer overall.
- **More results → more and longer fixations.** [[sources/lu-et-al-2011-visual-search-information-overload]]: result count rose → fixation count up (p < .001) **and** fixation duration up (p = .014). Here the cost is multiplicative, the opposite signature to Li et al.
- **Text–graphic congruity helps both search and distraction.** [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]]: matched congruity raised search efficiency (p < .001), cut fixations on the matched text (p = .004), and reduced distraction by unrelated elements (p < .001).
- **Typographic variables move search eye movements on webpages.** [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]]: **more headers → fewer fixations (b = −0.92)**, read as reduced second-pass reading. **Correlational** (53 readers, 12 homepages, no manipulation).

## ★ Why "less is more" does not hold
1. **Overload reversed direction mid-range.** Lu et al.: at 4 results fixation duration was **shorter** than at 10 (p = .028); at 60 it was **longer** than at 40 (p < .001). Two reversals inside a rising trend, attributed to strategy change rather than capacity exhaustion.
2. **Individual clusters outrank layouts.** Lu et al.'s cluster analysis found **three visual-search profiles** (text-focused, image-focused, holistic) whose **reading-speed differences exceeded the differences between layouts** — described by the authors as **"non-negotiable."** Any "better layout" claim should name which cluster it suits.
3. **Complexity ratings don't predict performance.** Zhang et al.: complexity ratings differed but explained only η² = .034–.083 and **did not predict comprehension time**. Layout *order* affected fixation duration (p = .002) but not fixation count, saccade amplitude, or comprehension — users adapted to unfamiliar layouts.
4. **★ Documented statistical defects in Zhang et al.:** they report **impossible likelihood ratios** (χ²(1) = 12.59, p < .05 alongside an η² of .000, which would imply a non-significant LR), and their "replicated interaction" **does not appear in the table**, being described only as "similar patterns." Take their directions as more defensible than their statistics. See [[concepts/methodology-critique]].

## ★ Script and direction
[[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] (Arabic L1 readers searching English graphs) found **script familiarity dominating reading direction**: Arabic readers searched **vertical** English faster than horizontal, while native English readers searching vertical Arabic were slower — but the author attributes this to **familiarity with vertical reading**, not to vertical direction itself. Search speed also tracked **L2 proficiency (ρ = 0.586, p = .01)**, which is a reader variable, not a layout effect. See [[concepts/text-direction]], [[concepts/expertise-familiarity]].

## Search as a task mode (not just a layout problem)
- Search spans a continuum from **browsing/scanning to directed search** [[sources/choo-detlor-turnbull-1999-web-browsing-searching]]; users deploy many distinct **cognitive strategies** by task type [[sources/thatcher-2006-cognitive-search-strategies]]; domain instances vary (health) [[sources/pang-2014-online-health-info-seeking]].
- System **structure × interaction style** interacts with search-task type — no universally best design [[sources/capra-marchionini-structure-interaction-search]].
- Individual differences: **cognitive/learning style** shapes relevance criteria [[sources/papaeconomou-relevance-judgments-learning-style]].

## Bridge to comprehension
- Doing a search task changes comprehension: selective, task-relevance-driven processing boosts targeted recall but can cost global understanding [[sources/rouet-2002-search-tasks-comprehension]] — connects to goal-driven reading [[sources/britt-et-al-dp-2022-r1]], [[concepts/reading-purpose-and-goal]].

## Contradictions / tensions
- **Preference vs. performance:** sparse layouts preferred, dense layouts faster [[sources/tarling-2009-page-layout-visual-search]] — recurring theme, see [[concepts/method-type-divergence]]. **★ Ho Sang & Petrarca extend it to typefaces:** familiar faces were preferred yet **not faster** and did **not** improve recall, so familiarity buys liking and nothing measurable. See [[concepts/expertise-familiarity]].
- **When does layout matter?** graphic type/topology effects vanish for simple tasks or familiar stimuli [[sources/zuo-2023-target-layout-graphic-search-eyetracking]] · [[sources/liang-2013-infographics-layout-search-eyetracking]] — effects surface only under higher cognitive demand. **★ Zhang et al. add a third instance:** dashboard layout *order* changed where the eyes went but not search time or comprehension, i.e. an effect that is measurable only in the eye-movement record.
- **★ The corpus's one recurring confound: quantity is never separated from arrangement.** Li, Lu, and Zhang all vary the number of elements; none manipulates arrangement at constant quantity. Every "layout" claim in this cluster is therefore also a "quantity" claim, and the same confound appears at the medium level in [[concepts/screen-vs-paper]] (scrolling vs. amount of text). This is the hub's most important methodological gap.

- **Columns may be a non-issue.** The century-scale review found "almost equal numbers of studies showed advantages and disadvantages ... as well as a preference of numbers of columns in text," and attributes the even split to the absence of a unified approach rather than to genuine equivalence [[sources/tarasov-legibility-of-textbooks-2015]]. For search over multi-column text the confound is that column count changes line length, so a column effect is uninterpretable unless characters-per-line is held constant. See [[concepts/columns]] · [[concepts/methodology-critique]].
- **Line length may be a non-issue too,** for the same reason and with the same caveat: preferences are "highly dispersed," mean legible line length about 100-120 mm, and reported in millimetres rather than characters, so optima are not comparable across studies [[sources/tarasov-legibility-of-textbooks-2015]]. See [[concepts/line-length]].

## Filed analyses
- [[syntheses/skimming-vs-scanning-vs-search]] — how layout supports differ across skimming, scanning, and search.
- [[syntheses/reading-goal-x-text-style-matrix]] · [[syntheses/evidence-based-default-screen-layout]].

## Open questions
- Does the density→speed advantage hold when targets are semantic (not visually distinct)?
- How do search-optimal layouts trade off against comprehension when users switch modes mid-task?
- **★ Does arrangement matter at constant quantity?** Every layout claim in this cluster is confounded with the number of elements. One factorial design (same elements, two arrangements) would be worth more than several more single-factor studies.
- **★ Do the three visual-search clusters (text / image / holistic) predict *which* layout is optimal?** Lu et al. report that cluster differences in reading speed exceed layout differences, so a layout recommendation may need to be a cluster-conditional recommendation.
- **★ Are the two volume signatures (multiplicative in Lu, subtractive in Li) a task difference or a task-presentation difference?** Form completion and result scanning may load differently.
- **Can any search study report a quality-at-fixed-time outcome** rather than raw time, so that faster search that finds less is visible as such?

## Sources backing this hub
[[sources/li-2009-web-layout-information-forms-locations]] · [[sources/lu-et-al-2011-visual-search-information-overload]] · [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] · [[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] · [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]] · [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] · [[sources/arya-2023-assessment-methods-readability-legibility]] · [[sources/fisher-1975-reading-visual-search]] · [[sources/tarling-2009-page-layout-visual-search]] · [[sources/liang-2013-infographics-layout-search-eyetracking]] · [[sources/zuo-2023-target-layout-graphic-search-eyetracking]] · [[sources/capra-marchionini-structure-interaction-search]] · [[sources/papaeconomou-relevance-judgments-learning-style]] · [[sources/choo-detlor-turnbull-1999-web-browsing-searching]] · [[sources/thatcher-2006-cognitive-search-strategies]] · [[sources/pang-2014-online-health-info-seeking]] · [[sources/rouet-2002-search-tasks-comprehension]] · [[sources/tarasov-legibility-of-textbooks-2015]]
