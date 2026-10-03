---
type: concept
title: Simulated Readers
reading_tasks: [comprehension, skimming]
tags: [concept, simulation, computational-model, cognitive-model, evaluation]
created: 2026-10-02
updated: 2026-10-02
source_count: 2
---

# Simulated Readers

## What it is
Using a computational model of a reader — rather than human participants — to predict, generate, or evaluate reading behavior. Simulated readers can consume thousands of text-condition combinations at a cost that human experiments cannot match, and they can be instrumented to expose internal quantities (attention allocation, memory state, fixation-like durations) that humans cannot report. The cost is that every conclusion is conditional on the model's fidelity, which is generally unvalidated.

## The two uses, which should not be conflated
The corpus contains two papers that both substitute simulation for humans but use it for opposite purposes:

1. **Design search** — [[sources/simulation-based-optimization-augmented-reading]] uses a *resource-rational* simulated reader (attention, memory, and time as constrained resources) inside a two-stage optimizer: offline search over the presentation design space, then online personalization from interaction data. Purpose: *find* good presentations.
2. **Evaluation** — [[sources/adaptive-personalization-educational-readings-simulated]] uses a *theory-grounded* simulated learner (Construction–Integration memory, DIME reader factors, KREC misconception revision, Dale–Chall readability signal, BKT-driven adaptation) on materials built from Wikibooks ontologies. Purpose: *judge* whether personalization helps.

A third, adjacent use appears in the framework paper: [[sources/readability-research-an-interdisciplinary-approach]] calls for cumulative, shared datasets and standardized reporting — the infrastructure a simulation program needs.

## How the models are built
- **Resource-rationality:** reading behavior emerges from allocating scarce attention, memory, and time; presentation is optimized against that allocation. Emergent, not fitted.
- **Construction–Integration (C–I):** a spreading-activation memory network over propositions; activation sums drive retrieval, and answers are produced by score-based option selection over the learner's *explicit* memory state — inspectable in a way human data is not.
- **DIME-style reader factors:** individual-difference modifiers on the base learner.
- **KREC:** misconception-driven revision, so incorrect knowledge gets updated rather than accumulating.
- **BKT:** Bayesian Knowledge Tracing drives the adaptive policy — what to add, what to skip.
- **Readability as an open signal:** Dale–Chall via the `textstat` package stands in for perceived text difficulty.
- **Ontology-grounded materials:** learning objectives and knowledge components curated from Wikibooks open textbooks in a browser-based Ontology Atlas; chunks labeled with ontology entities; aligned reading–assessment pairs generated from those labels.

## What the evidence says

**The only empirical result in the corpus is a negative one, and it is domain-dependent.** In [[sources/adaptive-personalization-educational-readings-simulated]], across three sampled subject ontologies: adaptive reading **significantly improved** computer science outcomes; produced **smaller positive but inconclusive** gains in inorganic chemistry; and was **neutral to slightly negative** in general biology.

That single sentence is the corpus's entire empirical contribution to adaptive personalization from simulation, and it argues against the field's usual framing. Adaptation is not uniformly beneficial — its value depends on the knowledge structure of the domain, and in biology the estimated mastery may have been wrong often enough that content removal cost more than it saved.

**Component models are all established; the contribution is the pipeline.** C–I, DIME, KREC, BKT, and Dale–Chall are each borrowed. Nothing new about memory or adaptation is demonstrated; what is demonstrated is an evaluation *architecture* plus the domain-sensitivity finding.

**Simulation's real payoff is instrumentality, not throughput.** Because the learner's memory state is explicit, a simulator can ask "why did adaptation fail here?" in a way a human study cannot. That is the strongest argument for the approach and neither paper exploits it fully — both report outcome scores, not mechanistic diagnosis of the biology failure.

## Why this needs to be treated cautiously in a wiki about *reading*
- **Unvalidated fidelity.** Neither paper validates its simulator against human reading. Every number is a statement about the model.
- **Tiny effective sample.** Three sampled subject ontologies is `n=3` domains. The biology result cannot be generalized — but it also cannot be dismissed, and it is enough to block claims that adaptation is safe by default.
- **Inherited assumptions are invisible.** BKT's knowledge-component decomposition, Dale–Chall's grade-level validity, and C–I's activation parameters all carry assumptions that are silently imported. When a simulated result disagrees with intuition, the cause is usually one of these.
- **Single-source, English, open-textbook materials.** Wikibooks is not a representative curriculum.
- **No human baseline means no effect size.** There is no "how much better than real students" claim available.

## The test these simulations must pass
The corpus happens to contain the human ground truth a simulator would need to reproduce:
- [[sources/accelerating-adult-readers-typeface]] reports a **51% within-person** speed spread between a reader's own fastest and slowest font.
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] reports **11 distinct fonts** selected as optimal by 49 dyslexic/dyspraxic children, no font exceeding ~20%, plus significant within-child gains from objective personalization (errors `2.69 → 1.63`, `p=.028`).
- [[sources/font-type-screen-readability-dyslexia]] and [[sources/good-fonts-for-dyslexia]] supply the category-level direction (sans/monospace/roman > serif/proportional/italic) with the important caveat that reading-time effects are marginal and only 16/66 pairwise comparisons were significant.
- [[sources/rhythmic-subvocalization-poetry-eye-tracking]] supplies the syllable-number effect — fixation durations correlating strongly with pronunciation length (`.84` among lexical variables) — which any reader simulator with phonetic/lexical processing should reproduce and which is a sharp test of subvocalization modeling.

A resource-rational or C–I simulator that cannot reproduce the 51% within-person range and the mono-vs-proportional fixation pattern is not modeling readability.

## Sources
- [[sources/simulation-based-optimization-augmented-reading]] — resource-rational, offline+online design search, no human data
- [[sources/adaptive-personalization-educational-readings-simulated]] — C–I/DIME/KREC/BKT evaluation, domain-dependent result
- Framework context: [[sources/readability-research-an-interdisciplinary-approach]]

## Connections
- [[concepts/resource-rationality]] and [[entities/act-r-and-resource-rational-models]] — the Bai et al. modeling tradition
- [[entities/bayesian-knowledge-tracing]] — drives the adaptation policy
- [[concepts/adaptive-and-personalized-typography]] — what the simulators are optimizing or judging
- [[concepts/individual-differences-in-readability]] — the human variance pattern simulators must reproduce
- [[concepts/method-type-divergence]] — simulated vs. behavioral vs. eye-tracking evidence strength
- Reading-task hubs: [[syntheses/Comprehension]], [[syntheses/Skimming]]

## Evidence gaps worth chasing
1. **Simulator-vs-human validation** on the measures above — the precondition for the whole program.
2. **Mechanistic explanation of the biology failure.** The most informative experiment available: why does adaptation hurt there?
3. **Sensitivity analysis** over C–I activation and BKT transition parameters — do the domain-dependent conclusions survive perturbation?
4. **Non-English, non-textbook materials**, and ontologies built from real curricula rather than Wikibooks.
5. **Skimming as adaptive output.** Adaptive systems implicitly model "skip what you know" as good skimming; the biology result is the first corpus evidence that this can be counterproductive — worth testing directly and filing under [[syntheses/Skimming]].