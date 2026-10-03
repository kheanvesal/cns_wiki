---
type: entity
title: DyslexiaNet
reading_tasks: [comprehension]
tags: [entity, model, deep-learning, cnn, eog, dyslexianet]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# DyslexiaNet

## What it is
A lightweight convolutional neural network proposed in [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] (İleri et al., 2025) to classify children as dyslexic or typically developing from **EOG** recordings taken during reading, and indirectly to help identify a child's most suitable typeface/font size.

## Architecture and inputs
- Input: **scalogram images** — continuous-wavelet-transform (CWT) time-frequency representations of EOG signals, converted to images.
- Depth: **4 convolutional layers** (deliberately shallow).
- Channels analyzed separately: **horizontal EOG** (saccades, fixations, regressions) and **vertical EOG** (line transitions).
- Validation: 5-fold cross-validation, 3,000 scalograms per group.

## Performance
| Channel | Model | Accuracy | Sensitivity | Specificity | F1 | Train time |
|---|---|---|---|---|---|---|
| Horizontal | **DyslexiaNet** | **99.968 ± 0.04%** | 99.966 | 99.966 | 99.968 | 96 s |
| Horizontal | AlexNet | 99.94 ± 0.068% | 99.96 | 99.92 | 99.94 | 193 s |
| Horizontal | MobileNetV2 | 99.80 ± 0.20% | 99.96 | 99.63 | 99.80 | 1978 s |
| Horizontal | ResNet50 | 97.71 ± 5.01% | 95.00 | 99.93 | 97.43 | 804 s |
| Vertical | **DyslexiaNet** | **73.732 ± 3.04%** | 63.734 | 83.724 | 70.504 | 102 s |
| Vertical | AlexNet | 65.61 ± 2.67% | 54.43 | 76.80 | 60.97 | 273 s |
| Vertical | MobileNetV2 | 57.01 ± 2.61% | 42.61 | 71.44 | 49.70 | 2195 s |
| Vertical | ResNet50 | 53.35 ± 1.87% | 55.56 | 51.13 | 49.95 | 744 s |

**DyslexiaNet is both the most accurate and the fastest to train on both channels.** The authors attribute this to simplicity avoiding overfitting, especially on the smaller/noisier vertical-channel data. Horizontal ≫ vertical by ~26 points for every model, indicating the vertical channel is noise-dominated rather than information-limited.

## Critical caveat — the 99.97% is not a diagnostic accuracy
With 3,000 windows drawn from **36 children** and standard (non-grouped) 5-fold CV, folds almost certainly contain windows from the *same participant and same recording*. Adjacent CWT windows are near-duplicates. The number should be read as **segment-level separability**, not as the ability to classify a new child. The paper's stated ambition — a clinical decision-support system for physicians — is not supported by its validation design.

## Where it is used in the wiki
- [[concepts/eog-and-physiological-signals]] — as the primary EOG/classification exemplar
- [[concepts/font-type-typeface]] — its typeface nomination (BonvenoCF) is exploratory
- [[concepts/dyslexia-font-recommendations]] — the third non-replicating typeface recommendation

## Related entities
- [[entities/erciyes-university]] — origin
- [[entities/biopac-eog]] — acquisition hardware