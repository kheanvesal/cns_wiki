---
type: entity
title: EyeLink
reading_tasks: [comprehension]
tags: [entity, instrument, eye-tracking, data-acquisition]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# EyeLink

SR Research video-based eye-tracking system family used across the corpus. The two instruments appearing in these papers differ and are **not interchangeable** — see [[syntheses/when-measures-disagree]].

## Instruments in the corpus
- **EyeLink 1000** (SR Research), **500 Hz**, visual accuracy 0.25°–0.5°: used in [[sources/rhythmic-subvocalization-poetry-eye-tracking]] (Beck & Konieczny, Freiburg), with chin-and-head rest, 60 cm viewing distance, **right eye only**, and 9-point calibration/validation achieving spatial error <0.5°.
- **Tobii Pro Fusion**, **250 Hz**, 60–65 cm: used in [[sources/chinese-typography-eye-tracking-vertical-horizontal]] — screen-based, line of sight centred, no head rest mentioned.

## Related software
- **Experiment Builder** (SR Research) — stimulus presentation in the Freiburg study.
- Tobii heatmaps and trajectory maps in the Chinese-poster study.

## Methodological notes worth preserving
- Sampling rate differs (500 vs 250 Hz) across the two sources, so fixation-duration thresholds are not directly comparable.
- The Freiburg study explicitly fixes head position and tracks one eye, trading ecological validity for precision.
- Neither study reports blink-detection reliability; the DyslexiaNet authors chose **EOG** instead specifically because blinks and regressions are directly recoverable from the signal.

## Connections
- [[concepts/eye-tracking-measures]] — the measures these instruments produce
- [[concepts/eog-and-physiological-signals]] — the cheaper alternative used in [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]]
- [[syntheses/when-measures-disagree]] — cross-instrument comparability