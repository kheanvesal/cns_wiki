---
type: synthesis
title: "Gen-AI & Reading — Theme Hub"
reading_tasks: [comprehension, search, skimming]
tags: [hub, gen-ai, llm, theme, gaps]
created: 2026-07-26
updated: 2026-07-27
source_count: 9
---

# Gen-AI & Reading — Theme Hub

A new theme (added 2026-07-26): how **generative AI / LLMs** intersect reading behavior. The original corpus had **zero** Gen-AI papers and effectively stopped ~2025 — a genuine content gap, not a missing citation. These sources map cleanly onto the wiki's *own* identified gaps ([[concepts/latent-factor-matrix]] "Missing Innovations", [[syntheses/reading-goals-purpose-depth-map]]).

## Four ways LLMs touch the corpus's gaps
1. **Compression (L4) — the never-manipulated axis becomes real.** LLM summaries/outlines are literally the full→summary→headline continuum. Now studied as an *input*: AI summaries help weak readers and **harm strong readers** [[sources/rolle-2025-gpt-tools-comprehension]]; LLM-alone study underperforms note-taking for retention [[sources/kreijkes-2026-llm-notetaking-comprehension]].
2. **Linguistic adaptation (L1/L2/L3) — the thin side gets tools.** LLMs rewrite for cohesion, vocabulary, and grammar to a reader profile [[sources/mcnamara-2025-genai-text-personalization]]; prompt strategy matters (Meta/Metric-Guided best; a naïve prompt can make text *worse*) [[sources/hedlin-2025-prompting-readability-chatgpt]]; and a reader study finds simplification **improves readability without hindering learning** [[sources/pascoal-2026-llm-readability-student-comprehension]].
3. **Adaptive layout (the "adaptive vs fixed never compared" gap).** LLMs can *generate* layout from text [[sources/chen-2024-textlap-layout-planning]] — the enabling tech for the personalization the corpus never tested.
4. **Method / reading goals.** LLM-era models decode the reader's **goal** (seek vs comprehend) from eye movements in real time [[sources/decoding-reading-goals-eye-movements-2024]]; prompt-behaviour analysis tracks engagement over time [[sources/ai-reading-support-bloom-2025]].

## Cross-cutting findings
- **Shallowing, redux.** LLM-assisted reading reproduces the screen-**shallowing** pattern: initial ease, weaker durable comprehension — a direct continuation of [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]] and [[sources/clinton-2019-paper-vs-screens-meta]]. Note-taking (active encoding) beats LLM-alone [[sources/kreijkes-2026-llm-notetaking-comprehension]]; longitudinal use drifts to passive reading [[sources/ai-reading-support-bloom-2025]].
- **Preference ≠ performance, again.** Students prefer the LLM while it underperforms note-taking [[sources/kreijkes-2026-llm-notetaking-comprehension]] — the corpus's oldest theme ([[concepts/method-type-divergence]]) in a new setting.
- **Ability moderates.** AI tools help low performers and hurt high performers [[sources/rolle-2025-gpt-tools-comprehension]] — an aptitude × treatment interaction ([[concepts/expertise-familiarity]]); blanket deployment is risky.
- **Goals are decodable regimes.** Real-time goal decoding [[sources/decoding-reading-goals-eye-movements-2024]] empirically supports treating information-seeking vs comprehension as distinct regimes ([[concepts/reading-goals-critique]]).

## Key distinction: simplification vs. summarization
The new studies separate two LLM operations the corpus had lumped together:
- **Simplification** (rewrite: adjust vocabulary/grammar/cohesion, **content preserved**) tends to **help or not hurt** learning [[sources/pascoal-2026-llm-readability-student-comprehension]] · [[sources/hedlin-2025-prompting-readability-chatgpt]] — a genuine readability gain (L1/L2/L3).
- **Summarization / compression** (remove content, L4) can **hurt** durable comprehension and disproportionately harm strong readers [[sources/rolle-2025-gpt-tools-comprehension]] · [[sources/kreijkes-2026-llm-notetaking-comprehension]]; LLM plain-language summaries even rate as good as human ones while comprehending **worse** [[sources/guo-2025-llm-plain-language-summaries]].

Bottom line: **rewriting to be clearer helps; compressing to be shorter can cost understanding.** Prompt design matters — a naïve "make it easier" prompt can make text *less* readable [[sources/hedlin-2025-prompting-readability-chatgpt]].

**Visual reference:** `assets/genai-content-specimens.html` — worked before/after passages for simplification, summarization/compression, personalization, and prompt strategy, each tagged with the verdicts above. AI-generated layout (item 3, [[sources/chen-2024-textlap-layout-planning]]) is shown on `assets/layout-pattern-specimens.html` instead, since it's a layout not a content operation.

## Contradictions / cautions
- **AI summary as "desirable ease" vs desirable difficulty.** LLM summaries reduce effort but can lower durable learning — the mirror image of the [[concepts/disfluency]] "desirable difficulty" debate: here *too little* effort hurts. Flag against naïve "make it easier" claims.
- **Metric ≠ behavior.** Personalization is validated by NLP metrics, not reader outcomes [[sources/mcnamara-2025-genai-text-personalization]]; layout generation by design benchmarks, not reading performance [[sources/chen-2024-textlap-layout-planning]]; simplification often by intrinsic readability scores (Flesch-Kincaid) not comprehension [[sources/hedlin-2025-prompting-readability-chatgpt]]; and automated PLS metrics **fail to track human comprehension** [[sources/guo-2025-llm-plain-language-summaries]]. Treat metric wins as *enabling* evidence, not efficacy.

## Open questions
- Does LLM personalization of cohesion/level actually improve *comprehension* (behavioral), or only NLP metrics?
- Is the AI-summary harm to strong readers a compression effect, an effort effect, or both?
- Can adaptive LLM layout beat a fixed evidence-based default ([[syntheses/evidence-based-default-screen-layout]])?

## Sources
Compression / summaries: [[sources/kreijkes-2026-llm-notetaking-comprehension]] · [[sources/rolle-2025-gpt-tools-comprehension]] · [[sources/guo-2025-llm-plain-language-summaries]] · [[sources/ai-reading-support-bloom-2025]].
Simplification / personalization: [[sources/mcnamara-2025-genai-text-personalization]] · [[sources/hedlin-2025-prompting-readability-chatgpt]] · [[sources/pascoal-2026-llm-readability-student-comprehension]].
Layout / method: [[sources/chen-2024-textlap-layout-planning]] · [[sources/decoding-reading-goals-eye-movements-2024]].
Candidates + PDFs: `raw/GenAI-LLM/_MANIFEST.md`.
