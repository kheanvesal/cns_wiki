---
type: source
title: "SituFont: A Just-in-Time Adaptive Intervention Interface for Enhancing Mobile Readability in Situational Visual Impairments"
reading_tasks: [comprehension]
tags: [source, adaptive-typography, accessibility, svi, mobile, workload]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# SituFont (Chen et al., CHI 2026)

## Citation
Jingruo Chen, Kexin Nie, Mingshan Zhang, Chun Yu, Zhiqi Gao, Kun Yue, Yuanchun Shi, and Chen Liang. 2026. "SituFont: A Just-in-Time Adaptive Intervention Interface for Enhancing Mobile Readability in Situational Visual Impairments." *Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems (CHI '26)*, April 13–17, 2026, Barcelona, Spain. ACM, 25 pages. DOI: 10.1145/3772318.3791020

## Reading task(s)
Comprehension (read-aloud comprehension testing under simulated situational visual impairment). Also touches proofreading-adjacent self-correction only insofar as participants were free to reread; no proofreading measure.

## Question/aim
Two RQs, stated in §5: RQ1 — does SituFont improve reading performance compared to traditional displays under varying situational visual impairment (SVI) conditions? RQ2 — how do users perceive SituFont's workload and overall experience? The system detects reading context from smartphone sensors and adjusts font parameters just-in-time, with a human-in-the-loop correction step.

## Method
Three-part mixed-method program.
- **Study 1 (formative):** semi-structured interviews, N=15, ages 19–52. Used to identify factors affecting SVI.
- **Study 2 (modeling):** controlled scenario study, N=18 university students, ages 18–25, spanning six scenarios combining light, motion, and vibration. Used to collect labeled training data for the adjustment model.
- **Study 3 (user study):** within-subject, N=12 (5 male, 6 female, 1 non-binary), `M=22.3`, `SD=4.1`, range 18–34. Native Mandarin smartphone users, none clinically diagnosed with visual impairment. Eight simulated SVI scenarios. Timeline: pretest questionnaire → 4-day adaptation → comparison of SituFont against a traditional (non-adaptive) baseline.
- **Measures:** reading goodput (correctly read characters / total reading time, expressed in CPM; participants read aloud at normal pace with audio recorded), comprehension accuracy, NASA-TLX workload, User Experience Questionnaire (UEQ), System Usability Scale (SUS), plus qualitative feedback.

## Style/layout variables manipulated
Font size, font weight (thickness), line spacing, and character spacing — four parameters exposed as user-adjustable controls in the native Android UI and driven by the adaptation model from sensor context.

## Key findings
- SituFont consistently improved reading goodput across the tested SVI conditions; comprehension accuracy remained stable across both interfaces (no significant comprehension difference).
- SituFont significantly reduced NASA-TLX mental and physical workload relative to baseline.
- UEQ: significantly higher for SituFont on efficiency, supportiveness, and novelty; marginal differences on stimulation and perspicuity.
- SUS: significantly lower complexity and higher ease of use and consistency, at the cost of slightly higher initial learning effort.
- Study 1 established that situational factors (ambient light, motion/noise, fatigue, distraction) are user-recognized triggers; all 15/15 participants reported difficulty reading in vehicles.
- A stated limitation of the design is that adjustments can fire unintentionally during scrolling or text selection, turning adaptation into an interruption — motivating "disruption-safe" activation in future work.

## Effect direction & size if reported
Direction is unambiguous and consistent: **goodput ↑**, **mental and physical workload ↓**, **comprehension flat (nonsignificant)**. Exact effect sizes for goodput and NASA-TLX are presented graphically (Figures 10–11); the extracted text does not state numeric CPM or TLX values, so no pooled magnitude is reported here.

## Limitations/caveats
Authors' stated limitations: young adult native Chinese speakers only; short HSK Level 5 passages (likely ceiling effects on comprehension); simulated rather than clinical SVI; no diagnosed visually impaired or older participants. Additional limitations noted: only 8 of 16 possible factorial SVI scenarios were run and there is no neutral baseline; context-recognition metrics are limited; no comparison against machine-learning baselines or ablations for the Label Tree; personalization feedback is coarse/binary.

## Connections
- Concept pages: [[concepts/adaptive-and-personalized-typography]], [[concepts/font-size]], [[concepts/line-spacing]], [[concepts/cognitive-load]], [[concepts/cognitive-load]]
- Entity: [[concepts/text-direction]]
- Hub: [[syntheses/Comprehension]]
- Supports the Beier et al. framework ([[sources/readability-research-an-interdisciplinary-approach]]) that readability should be tuned to situation and individual; complements [[sources/validating-personalized-visual-auditory-parameters-dyslexia]], which personalizes per child rather than per context.
- Tension with [[sources/accelerating-adult-readers-typeface]]: that study found no reliable way to predict an individual's best font from preference; SituFont instead uses sensor-driven contextual inference plus explicit user correction.