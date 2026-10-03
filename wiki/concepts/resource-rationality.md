---
type: concept
title: Resource Rationality
reading_tasks: [comprehension]
tags: [concept, modeling, resource-rationality, computational-model, attention]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Resource Rationality

## What it is
The modeling assumption that cognitive behavior emerges from the allocation of limited resources — attention, memory, and time — rather than from a fitted mapping between inputs and outputs. Reading behavior under this account is a *consequence* of constraints, so a presentation is better when it lets the reader achieve the goal with less resource expenditure. Related entity: [[entities/act-r-and-resource-rational-models]].

## How it's operationalized in the corpus
In [[sources/simulation-based-optimization-augmented-reading]] (Bai, Zhao & Oulasvirta, 2026), a resource-rational **simulated reader** is the objective function for typography search:
- **Resources:** attention, memory, and time, each constrained.
- **Optimization:** offline search over the presentation design space, then online personalization from interaction data during use.
- **Stated motivation:** existing augmented-reading systems "rely heavily on heuristics, opaque data-driven models" — resource-rational simulation is offered as the interpretable, explainable, scalable alternative.

## Why the wiki cares
Resource-rationality changes what counts as evidence. A resource-rational account makes *tradeoffs* the primary object: attention vs. memory vs. time. This is exactly the structure the human typography studies report but cannot explain.

The human findings that a resource-rational account would need to reproduce:
- **51% within-person WPM spread** between a reader's own fastest and slowest font ([[sources/accelerating-adult-readers-typeface]]).
- **Objective personalization gains**: errors `2.69 → 1.63` ([[sources/validating-personalized-visual-auditory-parameters-dyslexia]]).
- **Load-allocation patterns**: the poetry-layout Load Contribution results ([[sources/rhythmic-subvocalization-poetry-eye-tracking]]), where viewing time is distributed across lines in a predictable way — a resource-allocation signature.
- **A 26-point classification gap between EOG channels** ([[sources/dyslexianet-eog-deep-learning-dyslexia-detection]]), indicating that some channels carry the reading-relevant signal and others are noise.

## Critical caveat
No source validates a resource-rational simulator against human reading. Every resource-rational conclusion in the corpus is a statement about the model, not about readers. The main risk is **objective misspecification**: a simulator can confidently optimize for the wrong thing. This is why [[sources/readability-research-an-interdisciplinary-approach]]'s call for shared datasets and standardized reporting matters — it is the precondition for checking simulator fidelity.

## Sources
- [[sources/simulation-based-optimization-augmented-reading]] — sole source

## Connections
- [[concepts/simulated-readers]] — parent concept
- [[entities/act-r-and-resource-rational-models]] — the modeling tradition
- [[concepts/cognitive-load]] — the resource most relevant to layout
- [[concepts/individual-differences-in-readability]] — resource levels vary per person, which is why allocation must be personalized
- [[concepts/cognitive-load]] — the behavioral correlate of resource expenditure
- Reading-task hub: [[syntheses/Comprehension]]

## Evidence gaps worth chasing
1. **Fidelity validation** against the human variance patterns above.
2. **Resource measurement in humans** — eye-tracking gives fixation counts; memory is not measured in any corpus typography study; time is. A resource-rational account is only testable if all three are measured.
3. **Sensitivity analysis** over resource weights — does the optimal presentation change if attention is weighted differently from time?
4. **Empirical comparison** of resource-rational search against the heuristic baselines the paper critiques.