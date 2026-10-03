---
type: entity
title: "BIOPAC MP-36"
reading_tasks: [comprehension]
tags: [entity, instrument, eog, data-acquisition]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# BIOPAC MP-36

Multi-channel physiological data acquisition system (BIOPAC Systems) used to record **EOG** signals in [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] (Erciyes University).

## Role
Acquired EOG at **100 Hz** during reading tasks, with manual, research-assistant-controlled transitions between the 28 texts, recording stopped on text completion, and reading duration captured automatically for synchronization with the signals. Signals were managed via the BIOPAC system while stimuli were presented in PowerPoint.

## Signal chain (as used here)
1. EOG electrodes around the eyes capture the corneo-retinal dipole.
2. **Horizontal channel** → saccades, fixations, regressions (reading-related movement).
3. **Vertical channel** → line transitions.
4. Pre-processing: **4th-order Butterworth band-pass filter, 0.1–10 Hz**.
5. Derived features: reading time, blink rate (blinks ÷ reading minutes), regression rate (regressions ÷ word count), EOG signal energy.
6. CWT → scalogram images → CNN classification ([[entities/dyslexianet]]).

## Note
MP-36 is a general-purpose research platform, not a reading-specific device — its role here is low-cost, deployable biosignal capture, consistent with the authors' school/clinic deployment goal. See [[concepts/eog-and-physiological-signals]] for how EOG compares to video eye tracking.

## Connections
- [[concepts/eog-and-physiological-signals]] — the signal and its features
- [[entities/erciyes-university]] — the group that used it
- [[entities/dyslexianet]] — the model consuming its output