---
type: concept
title: Layout and Line Breaks
reading_tasks: [comprehension, skimming]
tags: [concept, layout, line-breaks, line-spacing, whitespace, poem-layout]
created: 2026-10-02
updated: 2026-10-02
source_count: 2
---

# Layout and Line Breaks

## What it is
The arrangement of text into visual units — where lines break, where paragraphs and stanzas divide, how much vertical space separates them, and whether a semantic boundary coincides with a visual boundary. Distinct from typeface properties and from writing direction: this is about *where the visual structure falls*, not what the characters look like or which axis they flow along.

## Scope boundary
This page owns **break placement** — where a line, paragraph, or stanza boundary falls relative to a semantic boundary. It does not re-argue the sibling knobs, which keep their own pages: vertical gap size is [[concepts/line-spacing]]; horizontal extent is [[concepts/line-length]] / [[concepts/characters-per-line]]; units per block is [[concepts/paragraph-length]]; indentation-as-seg cue is [[concepts/segmentation-indentation]]; surrounding empty space is [[concepts/whitespace-margins]]; column structure is [[concepts/columns]]; flow axis is [[concepts/text-direction]]. Overlap is real and intentional — the pages differ by *which knob*, not by which studies. Cite the knob-specific page unless the finding is specifically about alignment of break to semantics.

## How it's operationalized across studies
- **Line-break alignment manipulation (the cleanest causal test in the corpus):** verse endings aligned to line breaks ("poem layout") versus verse endings occurring mid-line ("prose layout") — [[sources/rhythmic-subvocalization-poetry-eye-tracking]].
- **Line spacing held constant as a control:** 1.5 in [[sources/rhythmic-subvocalization-poetry-eye-tracking]]; 2.0 in [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]].
- **Line spacing as a user-adjustable parameter:** [[sources/situfont-adaptive-mobile-typography-svi]] exposes line spacing alongside font size, weight, and character spacing.
- **Page/screen fitting:** multi-page poem presentation, up to 13 lines per page, 1920×1080, stimuli split across up to 3 pages — [[sources/rhythmic-subvocalization-poetry-eye-tracking]].
- **Stanza structure as an experimental control:** stanzas 3 and 5 deliberately kept rhythmically regular so readers could re-acquire a pattern after an anomaly — [[sources/rhythmic-subvocalization-poetry-eye-tracking]].
- **Text/image layout ratio:** [[sources/chinese-typography-eye-tracking-vertical-horizontal]] varies how text and imagery share the poster field (but with layout tied to writing direction).
- **Simulated reflow/density:** Dale–Chall readability as an open signal in [[sources/adaptive-personalization-educational-readings-simulated]] — a *measure* of density rather than a manipulation.

## What the evidence says

**Line breaks act as attentional and structural markers, and their effect depends on what the break aligns with.** This is the corpus's most direct evidence that layout position is itself a causal style variable.

In [[sources/rhythmic-subvocalization-poetry-eye-tracking]] the interaction, not the main effect, is the finding:
- **Metrical anomalies** disrupted reading robustly **in poem layout** — significant three-way interaction of layout × version × anomaly-type(metric) for gaze duration, regression-path duration, and total reading time; post-hoc inconsistent-vs-consistent contrasts significant across all four measures. Metral anomalies read **slower in poem than in prose layout** (all measures).
- **Rhyme anomalies** produced their strongest effects **in prose layout** — reliable three-way interactions for single fixation duration, gaze duration, and regression-path duration. Without visual verse cues, rhyme becomes the anchor readers use to recover the poetic structure.

So the layout that best supports metrical processing is **not** the one that best supports rhyme processing. Line breaks are not a uniform readability aid; they are cues whose utility depends on which structure the reader needs to reconstruct.

**The paper attributes pausing at verse endings to closure effects, enhanced by the poem's visual presentation** — line breaks therefore serve as *temporal* boundaries in an inner-speech timeline, not merely as whitespace. Reading speed is understood as shaped by a predicted verse-duration unit (2–4 s, peak ~2.5–3.5 s) rather than by characters-per-line.

**Corroborating evidence for a poetry-layout cost:** the paper reports that Fechino et al. (2020) found longer gaze durations and higher rereading probability in poetry layout, and Menninghaus & Wallot (2021) found longer total gaze durations on verse-final words when rhyme and/or meter were present.

## Where studies disagree
- **Reflowing text costs structure.** In prose layout readers must use rhyme to recover structure, and rhyme anomalies there were *more* disruptive than in poem layout. By contrast [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] standardized line spacing at 2.0 across conditions and treated spacing as a control, finding typeface and size — not spacing — to carry the signal. Responsive web reflow and print poetry reflow may impose similar costs; nobody in the corpus has tested this directly.
- **Spacing as signal vs. spacing as nuisance.** Line spacing is a manipulated variable in [[sources/situfont-adaptive-mobile-typography-svi]] (with reported goodput gains and reduced workload) but is only ever a *controlled constant* in the eye-tracking studies. It has never been isolated as a factor with comprehension measured.
- **Layout vs. direction.** [[sources/chinese-typography-eye-tracking-vertical-horizontal]] varies vertical vs. horizontal text and finds large fixation-duration differences; [[sources/rhythmic-subvocalization-poetry-eye-tracking]] varies break placement within a fixed horizontal direction and finds content-type-dependent interactions. These are **different variables** and should not be pooled — see [[concepts/text-direction]].

## Mechanisms proposed (mostly untested here)
- **Closure/segmentation:** line endings delimit units and trigger pausing (Smith 1968; Fuller 2001), affecting rhythm maintenance and breath/pause patterning.
- **Saccade and regression planning:** line-final positions are known saccade-amplitude extremes and problematic for eye-movement behavior — the corpus paper knowingly kept one critical region at the last word of a screen and flags this as a design concession.
- **Parafoveal benefit of short lines:** untested in this corpus.
- **Load contribution:** the corpus paper uses Load Contribution to allocate viewing time across lines, finding predictable allocation — a bridge to global-attention accounts.

## Sources
- [[sources/rhythmic-subvocalization-poetry-eye-tracking]] — primary evidence; layout × content-type interaction
- [[sources/chinese-typography-eye-tracking-vertical-horizontal]] — layout entangled with writing direction
- Secondary/control-only: [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]], [[sources/situfont-adaptive-mobile-typography-svi]]

## Connections
- [[concepts/line-spacing]] — sibling concept; spacing is the density knob, line breaks are the segmentation knob
- [[concepts/text-direction]] — do not conflate
- [[concepts/selective-attention]] — line breaks as attentional markers
- [[concepts/rhythm-rhyme-and-prosody]] — the mechanism this concept operates through
- [[concepts/eye-tracking-measures]] — regression-path and gaze-duration measures carry the effects
- Reading-task hubs: [[syntheses/Comprehension]], [[syntheses/Skimming]]

## Evidence gaps worth chasing
1. **Line length and line breaks manipulated independently** in prose comprehension — line breaks are essentially untested outside verse.
2. **Spacing as an isolated factor** with comprehension outcomes, rather than as a fixed constant.
3. **Reflow cost:** does prose text reflowed to variable line lengths (responsive web, e-reader zoom) suffer the same anchoring loss the prose-layout poetry condition shows?
4. **Do layout effects generalize beyond verse?** The corpus paper explicitly flags this as an open question.
5. **Interaction with reading direction:** do line-break effects hold for vertical Chinese text? Untested.