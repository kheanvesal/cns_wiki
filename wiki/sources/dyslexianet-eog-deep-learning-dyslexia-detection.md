---
type: source
title: "DyslexiaNet: Examining the Viability and Efficacy of Eye Movement-Based Deep Learning for Dyslexia Detection"
reading_tasks: [comprehension]
tags: [source, dyslexia, eog, deep-learning, typeface, font-size, eye-tracking]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# İleri, Altıntop, Latifoğlu & Demirci (JEMR 2025)

## Citation
Ramis İleri, Çiğdem Gülüzar Altıntop, Fatma Latifoğlu, and Esra Demirci. 2025. "DyslexiaNet: Examining the Viability and Efficacy of Eye Movement-Based Deep Learning for Dyslexia Detection." *Journal of Eye Movement Research* 18, Article 56. DOI: 10.3390/jemr18050056. Received 10 July 2025; accepted 10 October 2025; published 15 October 2025. Affiliations: Department of Biomedical Engineering and Department of Child and Adolescent Psychiatry, Erciyes University, Kayseri, Türkiye. Funded by TÜBİTAK (119E055); ethics approval 2018/565.

## Reading task(s)
Comprehension (silent reading of grade-level texts). The **primary** purpose is diagnostic classification of dyslexia from eye-movement signals, not evaluation of reading style — but the stimuli manipulation is a genuine typeface × font-size factorial, making the style findings usable (with heavy caveats) for typography.

## Question/aim
Two questions, stated in §1 and §4: (a) can EOG-derived features identify which typeface/font-size combination suits a child with dyslexia, and (b) can a deep network classify dyslexia from EOG signals recorded during those reading tasks? The authors note this is the first study to determine a suitable typeface using EOG signals.

## Method
- **N:** 23 children with dyslexia (13F, 10M) aged 8–10, plus **13 age–sex matched typically developing controls (TDC)**. Grades 2, 3, 4 (ages 7–8, 8–9, 9–10). Combined N=36.
- **Diagnosis:** DSM-5 criteria plus a specific learning disability (SLD) battery, by a child and adolescent psychiatrist; comorbid psychiatric illness, epilepsy, cerebral palsy, developmental delay, and CNS abnormalities excluded.
- **Signal:** **EOG, not eye-tracking** — horizontal and vertical channels recorded at 100 Hz via BIOPAC MP-36; 4th-order Butterworth band-pass filtered 0.1–10 Hz. EOG captures blinks, saccades, regressions, and line transitions indirectly.
- **Stimuli:** 28 distinct Turkish texts, **7 typefaces × 4 font sizes** (14–22 pt), line spacing standardized at 2.0 for all texts except text 28 (spacing control). Texts drawn from Ministry of National Education textbooks **one grade level above** the participant's grade (to reduce familiarity) — an ecological-validity choice, but it also confounds text difficulty with grade.
- **Behavior/physiology measures:** reading time, blink rate (blinks per reading minute), regression rate (regressions per word), and EOG signal energy.
- **Classification:** scalogram images (CWT) from EOG signals fed to AlexNet, ResNet50, MobileNetV2, and the proposed **DyslexiaNet** (4 convolutional layers). Channels analyzed separately; 3,000 scalograms per group; **5-fold cross-validation**; metrics accuracy, sensitivity, specificity, F1.

## Key findings
**Group differences (dyslexia vs. TDC) — all significant:**
- Reading time significantly higher for dyslexia (`****`, `p<0.0001`) across all three grades.
- Blink rate significantly higher for dyslexia (`****`, `p<0.0001`), most strongly in grades 2–3; grade 4 showed the smallest gap. Some typefaces showed *higher* blink rates in TDC than in the dyslexia group.
- Regression rate significantly higher for dyslexia (`****`, `p<0.0001`) across all font sizes and grades.
- EOG signal energy significantly higher for dyslexia (`****`, `p<0.0001`); interpreted as more effortful reading.

**Typeface/font-size findings (dyslexic readers) — exploratory, no pairwise stats:**
- **BonvenoCF** was most consistently favorable: fastest reading times in grades 2–4, lowest regression across 14–20 pt, low blink rates. Grade 3: BonvenoCF 16 pt fastest (`34.956 s`), BonvenoCF-Colored 20 pt close (`35.252 s`). Grade 4: BonvenoCF 20 pt lowest (`33.324 s`).
- **TTKB Dik Temel ABC** — the official Ministry of Education textbook font — was influential, plausibly through familiarity; low regression at 20 pt.
- **Colored variants** (colored syllables with BonvenoCF; colored Times New Roman) supported decoding and reduced cognitive load, consistent with reduced regression.
- **Italic fonts consistently produced longer reading times** across grades 2 and 3 — stated as a pattern, not a tested contrast.
- Larger sizes (20 pt) tended to reduce regressions in younger readers.
- TDC showed minimal reading-time variation across typefaces, i.e. font style matters less for fluent readers.

**Classifier performance — channel asymmetry is the headline:**
- **Horizontal channel (reading-related saccades/fixations/regressions):** near-ceiling for all models — AlexNet `99.94 ± 0.068%`, ResNet50 `97.71 ± 5.01%`, MobileNetV2 `99.80 ± 0.20%`, **DyslexiaNet `99.968 ± 0.04%`** (sensitivity 99.966, specificity 99.966, F1 99.968). Training times: 193, 804, 1978, 96 s respectively.
- **Vertical channel (line transitions):** much harder — AlexNet `65.61 ± 2.67%`, ResNet50 `53.35 ± 1.87%`, MobileNetV2 `57.01 ± 2.61%`, **DyslexiaNet `73.732 ± 3.04%`** (sensitivity 63.734, specificity 83.724, F1 70.504). Training times: 273, 744, 2195, 102 s.
- ResNet50 and MobileNetV2 on the vertical channel show enormous fold variance (e.g. ResNet50 specificity from 100% to 6.17%), indicating degenerate folds — the vertical-channel numbers are unstable, not merely low.
- **DyslexiaNet was both the most accurate and the fastest to train** (96 s horizontal, 102 s vertical), attributed to a simpler 4-layer architecture avoiding overfitting on the smaller vertical-channel dataset.
- Statistical comparison of networks used one-way ANOVA with Dunnett correction; training-time comparison used unpaired t-test with Welch's correction and one-way ANOVA with Dunnett.

## Direction and size if reported
- **Typeface direction:** BonvenoCF > others for dyslexic readers on reading time, blink rate, and regression; italic worst. **No effect sizes or p-values are reported for any typeface or font-size contrast** — the paper states typeface findings are exploratory because pairwise font comparisons were not performed.
- **Classifier direction:** DyslexiaNet best on both channels; horizontal ≫ vertical. Horizontal DyslexiaNet accuracy `99.968%` vs. vertical `73.732%` — a **26-point gap** attributable to channel informativeness, not model quality.
- **Group effect sizes are reported only as significance stars** (`p<0.0001`) without means, SDs, or test statistics in the extracted text; individual reading times are given for the fastest conditions only.

## Limitations/caveats
Authors' stated limitations:
- **Typeface findings are explicitly exploratory** — no pairwise statistical comparisons between fonts were performed, and text content was not strictly controlled. The BonvenoCF recommendation is therefore a pattern, not a demonstrated effect.
- **Small sample** (23 dyslexia, 13 TDC) and restriction to one age range and one language (Turkish), limiting generalizability.
- Data set and models do not fully capture the multidimensional nature of dyslexia; multimodality and long-term follow-up are deferred to future work.
- **Near-ceiling horizontal-channel accuracy is a red flag for data leakage.** Scalograms are windowed segments from the same continuous EOG recordings on which the models were validated; with 3,000 windows per group from only 36 children, 5-fold CV almost certainly splits windows — not participants — across folds. Adjacent windows from the same trial are near-duplicates. The reported 99.97% should be read as segment-level separability, not as a generalizable diagnostic accuracy; participant-level (grouped) cross-validation would be required to support clinical use.
- **ECG/EOG energy differences are group-level, not condition-level**, so they do not validate any individual child's optimal font.
- Grade-above-grade text selection confounds font conditions with text difficulty.
- Blink rate is a crude cognitive-load proxy with substantial non-reading causes (fatigue, dryness, luminance).
- Only one clinical site; no independent replication; no non-Turkish or non-Latin script validation; no comparison against eye-tracking-based classification.
- The paper's own framing as a **decision-support system for physicians** outruns what the validation design supports.

## Connections
- Concept pages: [[concepts/font-type-typeface]], [[concepts/font-size]], [[concepts/italic-and-slant]], [[concepts/eye-tracking-measures]], [[concepts/eog-and-physiological-signals]], [[concepts/dyslexia-font-recommendations]], [[concepts/text-color-and-visual-salience]]
- Entities: [[entities/dyslexianet]], [[entities/erciyes-university]], [[entities/biopac-eog]]
- Hub: [[syntheses/Comprehension]]
- **Principal contradiction with** [[sources/font-type-screen-readability-dyslexia]] and [[sources/good-fonts-for-dyslexia]]: those nominate Helvetica/CMU/Arial, Verdana and Times; this nominates **BonvenoCF** and TTKB Dik Temel ABC. Different languages (Turkish vs. English), different signals (EOG vs. fixation), different age bands. Note both papers flag their own typeface claims as weaker than the category claims — see [[concepts/dyslexia-font-recommendations]] for the reconciliation.
- **Converges with** both Rello papers on one point: **italic fonts are the most consistently disfavored style** across three independent studies, three languages, and two measurement modalities. This is the strongest cross-study style finding in the corpus and should anchor [[concepts/italic-and-slant]].
- **Converges with** [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] on the absence of a universal font (there, 11 fonts chosen by 49 AD children; here, individualized variation explicitly invoked in the conclusion: "each child could differ individually").
- Method contrast: EOG is a cheap, non-invasive proxy for deployment in schools, but it cannot resolve word-level readability the way fixation-based eye tracking does in the Rello studies — worth recording in [[concepts/eog-and-physiological-signals]] and [[concepts/method-type-divergence]].
- The colored-font finding (colored syllables aiding decoding) connects to [[concepts/text-color-and-visual-salience]] and is a candidate for a new concept page on color-based legibility aids; it is currently the only corpus evidence for that variable.