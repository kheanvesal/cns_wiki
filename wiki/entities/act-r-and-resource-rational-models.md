---
type: entity
title: "ACT-R and Resource-Rational Models"
reading_tasks: [comprehension]
tags: [entity, modeling, act-r, cognitive-architecture, computational-model]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# ACT-R and Resource-Rational Models

A family of cognitive architectures (ACT-R most prominent) built on a **resource-rational** premise: cognition is effortful computation under hard constraints on activation (attention), latency (time), and retrieval (memory). Behavior is not fitted to data; it *emerges* from the architecture's resource limits.

## Role in the corpus
The resource-rational tradition supplies the modeling backbone for [[sources/simulation-based-optimization-augmented-reading]] (Bai, Zhao & Oulasvirta, 2026), where a simulated reader with constrained **attention, memory, and time** becomes the objective function for typography search — offline over the design space, then online from interaction data.

Contrast with the *other* simulated-reader tradition in the corpus: [[sources/adaptive-personalization-educational-readings-simulated]] uses a **theory-grounded memory** account (Construction–Integration, DIME, KREC) evaluated via BKT, rather than a resource-rational one. The two make different commitments:
- Resource-rational: behavior follows from limits; parameters are scarce resources.
- Architecture/memory-grounded: behavior follows from representation and learning; "resources" are architectural capacities.

## Why resource-rationality is attractive for this wiki
It makes **tradeoffs the primary object** — attention vs. memory vs. time — which is the structure human typography experiments report (e.g., load-allocation patterns in poetry layout) but cannot explain mechanistically. See [[concepts/resource-rationality]].

## Central caveat
No source here validates a resource-rational simulator against human reading data. All resource-rational conclusions are claims about the model. A simulator that cannot reproduce observed human variance (e.g., the 51% within-person font speed range) is not modeling readability.

## Connections
- [[concepts/resource-rationality]] — parent concept
- [[concepts/simulated-readers]] — the broader substitution move
- [[entities/bayesian-knowledge-tracing]] — the rival framework in the Woo et al. pipeline
- [[concepts/cognitive-load]] — behavioral correlate of resource expenditure