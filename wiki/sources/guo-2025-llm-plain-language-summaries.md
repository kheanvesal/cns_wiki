---
type: source
title: "Guo et al. (2025) — Are LLM-Generated Plain Language Summaries Truly Understandable?"
reading_tasks: [comprehension, skimming]
tags: [gen-ai, llm, plain-language-summary, compression, health, comprehension, preference-vs-performance, metric-vs-behavior]
created: 2026-07-26
updated: 2026-07-26
---

# Are LLM-Generated Plain Language Summaries Truly Understandable? A Large-Scale Crowdsourced Evaluation

**Citation.** Guo, Y., Sohn, J. H., Leroy, G., & Cohen, T. (2025). Are LLM-generated plain language summaries truly understandable? A large-scale crowdsourced evaluation. arXiv:2505.10409. (UIUC / UCSF / Arizona / Univ. Washington.)

**Reading task(s).** Comprehension of plain-language summaries (health/medical; compression).

**Question/aim.** Do LLM-generated plain language summaries (PLSs) actually support layperson comprehension — beyond automated scores and Likert ratings?

**Method.** Large-scale crowdsourced study, **N=150 (Amazon MTurk)**. PLS quality via subjective Likert (simplicity, informativeness, coherence, faithfulness) **and** objective **multiple-choice comprehension + recall**. Also tested alignment of **10 automated metrics** with human judgment. Compared LLM- vs human-written PLSs.

**Style/layout variables manipulated.** Content-level — LLM vs human **plain-language summarization** (matrix L4 compression + L1/L3 simplification), for medical text.

**Key findings.**
- LLM PLSs looked **indistinguishable from human ones on subjective ratings** — but **human-written PLSs produced significantly better comprehension**.
- **Automated metrics failed to reflect human judgment** — unsuitable for evaluating PLSs.
- First study to evaluate LLM PLSs on both reader *preference* and *comprehension outcome*.

**Effect direction & size.** Human > LLM for comprehension despite equal subjective quality (significant).

**Limitations/caveats.** Crowdsourced; medical PLS genre; MCQ comprehension proxy.

**Connections.** [[concepts/method-type-divergence]] (subjective≠objective; metric≠behavior) · [[concepts/main-points-vs-detail]] · [[concepts/latent-factor-definitions]] (L4) · [[syntheses/gen-ai-and-reading]] · [[syntheses/when-measures-disagree]] · reinforces [[sources/rolle-2025-gpt-tools-comprehension]].
