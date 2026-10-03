---
type: concept
title: EOG and Physiological Signals
reading_tasks: [comprehension]
tags: [concept, eog, pupil, blink, regression, physiological, eye-tracking-adjacent]
created: 2026-10-02
updated: 2026-10-02
source_count: 2
---

# EOG and Physiological Signals

## What it is
Electrooculography (EOG): recording voltage from electrodes placed around the eyes to capture the corneo-retinal dipole, yielding signals proportional to eye movement and eyelid activity. Distinct from video-based eye tracking — EOG measures *corneoretinal potential*, not gaze coordinates, so it detects that an eye movement happened and roughly its direction and magnitude, without giving a precise fixation position on a character. Also grouped here: pupil diameter and blink rate, which are physiological effort proxies rather than spatial measures.

## How it's operationalized in this corpus
- **Two channels:** horizontal EOG for reading-related saccades, fixations, and regressions; vertical EOG for line transitions — [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]].
- **Acquisition:** 100 Hz sampling, BIOPAC MP-36; 4th-order Butterworth band-pass filter, 0.1–10 Hz for noise removal.
- **Derived features:**
  - *Reading time* (seconds per text)
  - *Blink rate* = average blinks per text ÷ reading time in minutes
  - *Regression rate* = average regressions ÷ number of words
  - *EOG signal energy* (amplitude of the signal; higher = more effortful reading)
- **Scalogram representation:** continuous wavelet transform of EOG → time-frequency images → CNN classification inputs.
- **Pupil diameter and heatmaps** as a parallel physiological/attentional route in the video-based study — [[sources/chinese-typography-eye-tracking-vertical-horizontal]].

## What the evidence says

**EOG reliably separates dyslexic from typical readers at the group level.** In [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] all four physiological/behavioral measures differ at `p<0.0001` across grades 2–4: reading time ↑, blink rate ↑, regression rate ↑, EOG signal energy ↑. Interpreted as more effortful, more disrupted reading.

**Blink rate is usable as a cognitive-load proxy but is noisy.** It was highest in dyslexia most strongly in grades 2–3, with the grade-4 gap much smaller; and in some typefaces the TDC group blinked *more* than the dyslexia group. Grade-4 attenuation is unexplained.

**Channel informativeness dominates model architecture.** On the same recordings, horizontal-channel classification reached `99.97%` accuracy (DyslexiaNet) while vertical-channel reached only `73.73%` — a ~26-point gap. Since line transitions should be *easy* to detect, this asymmetry implies the vertical channel's signal is dominated by noise/artifact rather than by line-transition information, and ResNet50's vertical-channel specificity swinging from 100% to 6.17% across folds confirms degenerate behavior. Horizontal EOG, which carries reading-related saccades and regressions, is the informative channel.

**DyslexiaNet (4 conv layers) beat AlexNet, ResNet50, and MobileNetV2 on both channels while training fastest** (96 s vs. 193/804/1978 s horizontal) — attributed to avoiding overfitting on the smaller, noisier vertical-channel dataset.

**Near-ceiling accuracy is a validation-red flag, not a strength.** 3,000 scalogram windows per group drawn from only 36 children, validated with 5-fold CV, almost certainly splits *windows* rather than *participants*. Adjacent windows from one continuous recording are near-duplicates. Reported as 99.97% segment-level separability, this should not be read as diagnostic accuracy; participant-level grouped CV is required for that claim.

**Pupil diameter tracks attentional engagement in a free-viewing task.** In [[sources/chinese-typography-eye-tracking-vertical-horizontal]] vertical-text posters produced higher pupil diameter for both text (`p=0.024`) and image (`p=0.001`) regions than horizontal — a *context-of-interest* measure, distinct from effort-under-reading which blink rate is meant to capture.

## Method trade-offs vs. video eye tracking
| | EOG | Video eye tracking |
|---|---|---|
| Spatial precision | none (no fixation location) | high (0.25°–0.5° accuracy; EyeLink 1000 @ 500 Hz used in [[sources/rhythmic-subvocalization-poetry-eye-tracking]]) |
| Cost/portability | low; school-deployable | high; lab-bound |
| Blink/EOG energy | direct | requires video blink detection or external sensors |
| Word-level fixation analysis | not possible | possible — required for the category claims in [[sources/font-type-screen-readability-dyslexia]] and [[sources/good-fonts-for-dyslexia]] |

EOG's affordability is its main argument (the DyslexiaNet authors target real-time school deployment and clinical decision support). Its cost is that **it cannot resolve word-level readability** — it flags that a text was hard, not which word or which typeface feature caused it. That is why its typeface findings are necessarily coarser than the eye-tracking literature's.

## Sources
- [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] — EOG acquisition, features, channel asymmetry, CNN classification
- [[sources/chinese-typography-eye-tracking-vertical-horizontal]] — pupil diameter as engagement measure (video-based)
- Contrast: [[sources/rhythmic-subvocalization-poetry-eye-tracking]], [[sources/font-type-screen-readability-dyslexia]], [[sources/good-fonts-for-dyslexia]] — video eye tracking for word-level measures

## Connections
- [[concepts/eye-tracking-measures]] — the video-based sibling; do not pool effect sizes across the two
- [[concepts/font-type-typeface]] — where EOG's coarse typeface signal lives
- [[concepts/dyslexia-font-recommendations]] — EOG adds a third, non-replicating typeface nomination
- [[concepts/eog-and-physiological-signals]] ↔ [[concepts/eog-and-physiological-signals]] — the clinical-validity gap
- [[concepts/method-type-divergence]] — the wiki's tracking of eye-tracking vs. behavioral vs. self-report
- Reading-task hub: [[syntheses/Comprehension]]

## Evidence gaps worth chasing
1. **Participant-level (grouped) cross-validation** to get an honest diagnostic accuracy; the current 99.97% is not credible as a clinical number.
2. **Validation against video eye tracking** on the same participants — do EOG-derived regression rates correspond to measured regressive saccades?
3. **Vertical channel cleanup** (line-transition detection should not be a 74%-accuracy problem) before any vertical-channel claim is trusted.
4. **Blink-rate controls** for non-reading causes (fatigue, luminance, screen refresh) — grade-4 attenuation and TDC>dyslexia inversions are unexplained.
5. **EOG for reading effort during *comprehension* tasks** rather than detection — nobody has used EOG energy as a comprehension-difficulty index.