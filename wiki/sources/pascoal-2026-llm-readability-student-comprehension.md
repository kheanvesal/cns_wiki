---
type: source
title: "Pascoal et al. (2026) — Improving Text Readability to Support Student Comprehension (LLM-Powered)"
reading_tasks: [comprehension]
tags: [gen-ai, llm, simplification, readability, prompting, flesch-kincaid, learning, reader-study]
created: 2026-07-26
updated: 2026-07-26
---

# Improving Text Readability to Support Student Comprehension and Learning: An LLM-Powered Approach

**Citation.** Pascoal, G., van den Bosch, M., Viberg, O., Wong, J., & Demmans Epp, C. (2026). Improving Text Readability to Support Student Comprehension and Learning: An LLM-Powered Approach. In *Two Decades of TEL* (EC-TEL 2025), LNCS, pp. 291–305. Springer. doi:10.1007/978-3-032-03870-8_20.

> **Duplicate note.** Two copies in folder (`978-3-032-03870-8_20.pdf`, `Summarization_and_simplification_TEL.pdf`). Ingested once.

**Reading task(s).** Comprehension + learning (academic-text simplification, reader study).

**Question/aim.** Do LLM prompting strategies for simplifying academic texts improve readability **without hindering learning**?

**Method.** Compared two prompting strategies over **N=2,000 texts**: plain-text instructions vs a **Metric-Guided Prompt** (incorporates a readability metric). Intrinsic evaluation via Flesch-Kincaid Grade Level; then a **between-subjects user study, N=37 students** on perceptions + learning gains (original vs simplified).

**Style/layout variables manipulated.** Content-level — LLM **text simplification** (vocabulary + grammar; L1/L2/L3), prompt strategy as IV.

**Key findings.**
- **Metric-Guided Prompt** significantly reduced text complexity (Flesch-Kincaid).
- User study: simplified texts **improved readability without hindering learning** (no comprehension cost).
- Contrast with summarization: **simplification (rewrite, content preserved) helps/neutral**, unlike over-**compression** which can hurt ([[sources/guo-2025-llm-plain-language-summaries]], [[sources/rolle-2025-gpt-tools-comprehension]]).

**Effect direction & size.** Metric-Guided > plain prompt (readability); simplified ≈ original for learning (no loss), N=37.

**Limitations/caveats.** Small reader study (N=37); short-term learning; academic genre.

**Connections.** [[concepts/latent-factor-definitions]] (L1/L2/L3 simplification) · [[concepts/accessibility]] · [[sources/hedlin-2025-prompting-readability-chatgpt]] (same group) · [[sources/mcnamara-2025-genai-text-personalization]] · [[syntheses/gen-ai-and-reading]] · [[syntheses/does-style-improve-comprehension]].
