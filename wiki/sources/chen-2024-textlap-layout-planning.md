---
type: source
title: "Chen et al. (2024) — TextLap: Customizing LLMs for Text-to-Layout Planning"
reading_tasks: [comprehension, search]
tags: [gen-ai, llm, layout-generation, text-to-layout, graphic-design, adaptive]
created: 2026-07-26
updated: 2026-07-26
---

# TextLap: Customizing Language Models for Text-to-Layout Planning

**Citation.** Chen, J., Zhang, R., Zhou, Y., Healey, J., Gu, J., Xu, Z., & Chen, C. (2024). TextLap: Customizing Language Models for Text-to-Layout Planning. *Findings of the Association for Computational Linguistics: EMNLP 2024*, 14275–14289.

**Reading task(s).** Layout generation (relevant to comprehension/search via document/UI layout).

**Question/aim.** Can an LLM generate compelling graphical **layouts** from text instructions?

**Method.** **TextLap** — an LLM fine-tuned on a curated instruction-based layout-planning dataset (**InsLap**); human-built benchmark; compared to strong baselines incl. GPT-4-based methods.

**Style/layout variables manipulated.** **Layout** — LLM produces graphical layout plans (posters, flyers, ads, GUIs, documents) from text. This is the *generation* side of the layout factor (V5/V6).

**Key findings.**
- TextLap outperforms strong baselines (incl. GPT-4 methods) on document-generation and graphic-design benchmarks.
- Demonstrates LLMs can act as automated **layout designers** — the enabling technology for adaptive/personalized layout the corpus never tested empirically.

**Effect direction & size.** Benchmark wins (design quality); **no reading-outcome study** — a systems/generation paper.

**Limitations/caveats.** ML benchmark, not a reading experiment; layout *quality* ≠ reading *performance*. Bridges to the reading literature only as an enabler.

**Connections.** [[concepts/latent-factor-matrix]] (adaptive-layout gap) · [[concepts/layout-topology]] · [[concepts/interaction-style]] · [[syntheses/gen-ai-and-reading]] · [[syntheses/reading-goal-x-controlling-latent-factors]].
