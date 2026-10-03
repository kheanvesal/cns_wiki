---
type: source
title: "The Effect of Font Type on Screen Readability by People with Dyslexia"
reading_tasks: [comprehension]
tags: [source, dyslexia, typeface, eye-tracking, screen-readability, accessibility]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Rello & Baeza-Yates (TACCESS 2016)

## Citation
Luz Rello and Ricardo Baeza-Yates (Web Research Group, DTIC, Universitat Pompeu Fabra, Barcelona). 2016. "The Effect of Font Type on Screen Readability by People with Dyslexia." *ACM Transactions on Accessible Computing (TACCESS)* 8(4), Article 15, 33 pages, May 2016. DOI: 10.1145/2897736
**Note:** this is the 2016 journal article, a revision/extension of the 2013 ASSETS paper [[sources/good-fonts-for-dyslexia]]; the filename contains "2015" but the article is 2016.

## Reading task(s)
Comprehension — self-paced silent reading of short texts on screen. The paper frames reading time as the primary accessibility outcome; comprehension questions were asked but the analysis centers on fixation behavior and reading speed.

## Question/aim
What is the *objective*, eye-tracking-measured effect of typeface on screen reading performance for people with and without dyslexia? Stated aim: the first experiment to objectively measure typeface impact on reading speed via eye tracking, and to derive a set of recommended, more accessible fonts.

## Method
- **Design:** mixed between-within subjects.
- **N:** 97 participants, **48 with dyslexia**, remainder without. Ages and group means not reported in the extracted text.
- **Materials:** 12 texts set in 12 different fonts — a 12 × 12 crossing, so each font is a nonfactorial bundle of several typographic properties (serif/sans, proportionation, italic, weight).
- **Measures (eye tracking):** reading time, fixation duration, fixation count; plus participant preference ratings.
- **Analysis:** category-level contrasts (sans vs serif, monospaced vs proportional, roman vs italic), nonparametric tests, and dominance/partial-order analysis to rank fonts without assuming a single winner.

## Key findings
- **Category-level headline:** sans-serif, monospaced, and roman styles significantly improved reading performance over serif, proportional, and italic styles.
- **Monospace vs proportional, fixation duration:** dyslexia group monospace `0.22 (SD 0.05)` vs. proportional `0.26 (0.07)`, `p<.001`; control group `0.19 (0.03)` vs. `0.20 (0.03)`, `p=.002`. Monospace advantage is *larger* in the dyslexia group.
- **Monospace vs proportional, reading time:** category effect `χ²(1)=3.40, p=.065` — trend, not significant.
- **Italic vs roman, reading time:** overall category effect `χ²(1)=27.27, p<.001`, but **the dyslexia-group effect was not significant** (`p=.120`) — the italic penalty is driven by non-dyslexic readers.
- **Italic preference:** dyslexia group preferred italic `2.73 (SD≈1.20)` vs. roman `3.21 (1.22)`, `p=.002` — dyslexic readers rated italic **more favorably** despite the performance pattern.
- **Recommended accessible fonts:** a partial-order (dominance) analysis yielded a recommended set — Helvetica, CMU Sans Serif, and Arial were the only non-dominated candidates; Verdana and Times followed.
- Effect direction is consistent across groups on fixation duration; the group difference is in effect *magnitude* for monospace, and in the *direction of the preference-performance dissociation* for italic.

## Direction and size if reported
- **Monospace → shorter fixation duration** in both groups: dyslexic `0.22→0.26` (`p<.001`), control `0.19→0.20` (`p=.002`); reading-time benefit trend only (`p=.065`).
- **Italic → longer reading time** overall (`χ²=27.27, p<.001`), **but not within dyslexia** (`p=.120`).
- **Italic → lower preference in dyslexia** (`2.73` vs. `3.21`, `p=.002`) — a preference/performance inversion.
- Italic-vs-roman within-group WPM difference is reported in the source's tables; the extracted text does not preserve the non-dyslexic italic cell, so it is omitted here rather than reconstructed.

## Limitations/caveats
- **Nonfactorial font bundles.** The 12 fonts differ on many dimensions at once (serifness, proportionation, slant, weight, x-height), so category effects cannot be attributed to any single property. This is the paper's core inferential weakness.
- **Group-age confound** (dyslexic and control age distributions differ) — noted in the paper's own limitations.
- **Text dependence:** 12 texts only, not counterbalanced against font properties; text difficulty and font effects are entangled.
- **Reading time vs. fixation duration divergence** is reported but not reconciled; the monospace benefit is robust on fixation duration and marginal on reading time.
- **Comprehension effects unresolved** — comprehension was not the primary outcome and no comprehension conclusion is drawn.
- **Heterogeneous dyslexia:** no phonological-deficit subtype analysis; the dyslexia group is treated as homogeneous.
- Preference is collected but not integrated into the recommendation logic, despite the italic inversion.

## Connections
- Concept pages: [[concepts/font-type-typeface]], [[concepts/dyslexia-font-recommendations]], [[concepts/italic-and-slant]], [[concepts/eye-tracking-measures]], [[concepts/preference-versus-effectiveness]]
- Entities: [[concepts/eye-tracking-measures]], [[concepts/dyslexia-font-recommendations]]
- Hub: [[syntheses/Comprehension]]
- **Primary contradiction to log:** this paper recommends a fixed accessible font set (Helvetica, CMU, Arial), whereas [[sources/accelerating-adult-readers-typeface]] finds no font best for all readers and a 51% within-person range, and [[sources/readability-research-an-interdisciplinary-approach]] argues there is no single correct format. Populations differ (dyslexia vs. typical adults), so these are not strictly incompatible — but the recommendation framing itself is contested.
- **Italic pattern vs. this paper's sibling:** [[sources/good-fonts-for-dyslexia]] (ASSETS 2013) reports the same category ranking but with weaker conclusions (reading-time differences nonsignificant, `W=4556, p=.09` for italic). The 2016 revision strengthens the sample but the italic penalty still fails to reach significance within the dyslexia group. Record as "category claim robust in abstract, weak within-group."
- **Preference inversion here anticipates** the same dissociation in [[sources/accelerating-adult-readers-typeface]] (41% scored lowest comprehension in their preferred font).
- Contrast with [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]], which reaches a *different* typeface conclusion — BonvenoCF best — using EOG rather than fixation metrics in Turkish rather than English; see [[concepts/font-type-typeface]] for the reconciliation.