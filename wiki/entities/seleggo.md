---
type: entity
title: Seleggo
reading_tasks: [comprehension]
tags: [entity, tool, personalization, dyslexia, tts, web-app]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Seleggo

## What it is
An objective procedure and web app for identifying **individualized** visual and auditory parameters that facilitate online text reading, developed and validated in [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] (Lorusso et al., 2024). Originating from Seleggo NPO (Besozzo, Italy); the app is commercially owned (Seleggo NPO / Betterdays Ltd.), and the paper declares a competing financial interest.

## The key methodological feature
Visual parameters are selected by **measured performance, not preference**:
1. Child reads nonwords and pseudosentences aloud; reading time is **auto-recorded** and accuracy is **judged by the examiner** (correct syllables / errors).
2. The system selects the best combination of **font, size, and spacing** from the child's own error and timing profile.
3. Auditory parameters: child chooses a preferred TTS voice, then identifies the nonword the TTS pronounces most accurately.

This asymmetry — objective for typography, subjective for voice — matters: the objective pathway produced significant within-child gains, while the subjective pathway's benefit was group-specific (stronger in dyslexic/dyspraxic children for dictation, `Z=2.05, p=.020`).

## Population and validation
- **N=78** Italian children, ages 8–14: 49 atypical reading development (AD), 29 typical development (TD).
- **Within-child validation:** personalized vs. standard parameters (average of two standard fonts; default TTS voice).
- **Results:** text reading errors `2.69 → 1.63` (`Z=−1.91, p=.028`); reading speed `Z=−1.66, p=.049` (medians identical at `2.85`); dictation accuracy `Z=−1.65, p=.0495`.
- **Group signal:** Somers' `D=0.273, p=.013` for font size (AD chose larger sizes), spacing `p=.436` (nonsignificant); font-choice frequency did not differentiate groups (`p>.05`).
- **No single font won:** 11 fonts chosen as optimal in AD, 14 in TD; most frequent <20%.

## TTS parameters
Both groups performed better with **slowed speech (speed 0.8)** and **lower pitch (0.6)**; pitch association significant (`Somers' D=0.143, p=.005`), speed marginal (`D=0.150, p=.054`).

## Known limitation — default-option bias
Because sans-serif is widely recommended for dyslexia, it was **pre-selected as the default**, so children only actively chose among the other two families. This inflates sans-serif representation in the results. The authors state within-family and between-group comparisons remain informative, but any **cross-family font comparison is compromised** — a serious constraint given how often the font-choice tables are read as rankings.

## Where it is used in the wiki
- [[concepts/individual-differences-in-readability]] — the strongest human evidence for objective personalization
- [[concepts/preference-versus-effectiveness]] — objective-selection vs. subjective-selection contrast
- [[concepts/dyslexia-font-recommendations]] — the "no single font" counterposition
- [[concepts/multimodal-and-audio-support]] — TTS parameter findings
- [[concepts/font-size]] — the variable where the AD/TD group difference actually appeared

## Related entities
- [[entities/irccs-e-medea]] — clinical partner
- [[entities/text-to-speech-tts]] — auditory channel