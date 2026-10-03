---
type: entity
title: "Bayesian Knowledge Tracing (BKT)"
reading_tasks: [comprehension]
tags: [entity, modeling, bkt, adaptivity, educational-technology]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Bayesian Knowledge Tracing

A probabilistic model of learner knowledge over time. It maintains a probability that the learner has mastered each *knowledge component*, updated after each response (correct/incorrect), and supports decisions about what to teach, re-teach, or skip.

## Role in the corpus
Used in [[sources/adaptive-personalization-educational-readings-simulated]] (Woo et al., 2026) to drive the adaptive policy over educational readings. Learner state feeds the simulated reader; BKT estimates mastery; adaptation responds to it.

## Why it matters for style/layout research
BKT is the implicit theory of **what adaptive layout is doing**. It encodes an assumption that skipping or compressing already-mastered content is beneficial — i.e. that adaptive selection implements good skimming. The corpus provides a caution: in the general-biology domain, adaptive reading was **neutral to slightly negative**, implying the mastery estimates were often wrong enough that pruning cost more than it saved. That single result is the only corpus evidence bearing on whether "skip what you know" is actually a good rule.

## Assumptions inherited (flagged by the corpus)
- Knowledge components are discretized and correctly identified; a wrong decomposition breaks the estimate.
- Mastery transitions are modeled per-component with fixed slip/guess parameters.
- When these are mis-specified, the adaptive system's decisions degrade — as the biology result suggests.

## Connections
- [[concepts/simulated-readers]] — the modeling family
- [[concepts/adaptive-and-personalized-typography]] — what BKT controls
- [[sources/adaptive-personalization-educational-readings-simulated]] — sole source
- [[syntheses/Skimming]] — the "skip mastered content" assumption