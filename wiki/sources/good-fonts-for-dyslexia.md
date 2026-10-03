---
type: source
title: "Good Fonts for Dyslexia"
reading_tasks: [comprehension]
tags: [source, dyslexia, typeface, eye-tracking, accessibility, ass2013]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Rello & Baeza-Yates (ASSETS 2013)

## Citation
Luz Rello (NLP & Web Research Groups, Universitat Pompeu Fabra, Barcelona) and Ricardo Baeza-Yates (Yahoo! Labs & Web Research Group, UPF). 2013. "Good Fonts for Dyslexia." *Proceedings of the 13th ACM SIGACCESS Conference on Computers and Accessibility (ASSETS '13)*. Keywords: Dyslexia, font types, typography, readability, legibility, text layout, text presentation, eye-tracking.
**Note:** this is the conference original; the journal revision with an added non-dyslexic comparison group is [[sources/font-type-screen-readability-dyslexia]] (TACCESS 2016).

## Reading task(s)
Comprehension — self-paced silent reading of short texts on screen; primary outcome is reading speed as proxied by fixation behavior.

## Question/aim
Same motivating question as the later journal version: what is the objective, eye-tracking-measured effect of font type on reading performance for children with dyslexia? Stated as the first experiment to objectively measure typeface impact on reading speed via eye tracking, plus a set of more accessible font recommendations.

## Method
- **Design:** within-subject.
- **N:** 48 subjects, **all with dyslexia** (no control group — this is the key design difference from the 2016 revision).
- **Materials:** 12 texts set in 12 different fonts; fonts again bundle multiple typographic properties, so the comparison is between font *bundles* rather than isolated variables.
- **Measures:** eye-tracking reading time and fixation duration, plus preference.
- **Analysis:** Wilcoxon tests on pairwise font comparisons; category-level contrasts (sans vs serif, monospaced vs proportional, roman vs italic).

## Key findings
- **Category-level claim:** sans-serif, monospaced, and roman styles significantly improved *fixation-based* reading performance over serif, proportional, and italic fonts.
- **Explicitly weaker conclusion than the abstract's framing:** the authors state the conclusions are weaker because the category differences in **reading time were not statistically significant**. The robust result is at the fixation-duration level, not the speed level.
- **Italic vs roman, reading time:** `W=4556, p=.09` — nonsignificant, though italic fonts were **consistently numerically slower** than their roman counterparts in every comparison.
- **Courier** had significantly shorter fixation duration than six of the other fonts.
- **Arial Italic** had significantly longer fixation duration than eight of the other fonts.
- Only **16 of 66** pairwise fixation-duration comparisons reached significance — a low hit rate that the authors present transparently.
- Recommended a set of more accessible fonts on this basis.

## Direction and size if reported
- **Monospace / sans / roman → shorter fixation duration** than serif / proportional / italic (significant at the category level on fixation measures).
- **Italic → longer reading time numerically in every contrast, but not significantly** (`W=4556, p=.09`).
- **Courier → shortest fixation duration** of the 12 (significantly shorter than 6 others).
- **Arial Italic → longest fixation duration** (significantly longer than 8 others).
- **16/66 pairwise comparisons significant** — this ratio is the honest measure of the evidence's strength and should be carried forward alongside any "category" claim.

## Limitations/caveats
- **No control group** — every effect is a within-dyslexia-group contrast, so there is no baseline for what "normal" performance looks like and no way to tell whether dyslexia-specific fonts differ from generally-legible fonts. The 2016 revision adds this comparison.
- **Reading-time effects are nonsignificant.** The headline "significantly improved reading performance" claim in the abstract is about fixation duration, not speed; reading time is the outcome a reader actually cares about, and it did not move significantly.
- **Low pairwise hit rate** (16/66) means most font differences are indistinguishable; any recommendation is therefore order-restricted, not a true ranking.
- **Nonfactorial font bundles** confound serifness, proportionation, slant, and weight — no single property can be isolated.
- **Age/education confound** with dyslexia not addressed; children were still acquiring literacy, so absolute reading times are not interpretable.
- **Text dependence** across 12 texts; short texts and 8th-grade-level content.
- **Comprehension not measured** as an outcome; no claim about comprehension.

## Connections
- Concept pages: [[concepts/font-type-typeface]], [[concepts/dyslexia-font-recommendations]], [[concepts/italic-and-slant]], [[concepts/eye-tracking-measures]]
- Entities: [[concepts/eye-tracking-measures]], [[concepts/dyslexia-font-recommendations]]
- Hub: [[syntheses/Comprehension]]
- **Primary evidence link to** [[sources/font-type-screen-readability-dyslexia]]: same authors, same 12×12 materials, later journal version adds 49 non-dyslexic participants and turns within- into mixed design. Cite the 2016 paper for the category claim *with group contrast*, and this paper for the original within-group fixation analysis.
- **Directly relevant to Wilkins 2020:** the nonsignificant reading-time result plus the low pairwise hit rate is a concrete instance of a recommended-font list outrunning its evidence base — the same critique leveled at dyslexia font advice generally.
- **Contradicts** the popular claim that italic fonts specifically harm dyslexic readers: here the italic penalty is numerically consistent but statistically absent (`p=.09`), and the significant extreme is one specific font (Arial Italic), not the italic category.
- Contrast with [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]], whose Turkish EOG data also favors non-standard typefaces and again flags its typeface findings as exploratory — convergent caution across two very different measurement modalities.