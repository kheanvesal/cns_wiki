---
type: source
title: "Rhythmic subvocalization: An eye-tracking study on silent poetry reading"
reading_tasks: [comprehension]
tags: [source, poetry, rhythm, rhyme, layout, subvocalization, eye-tracking, verse]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Beck & Konieczny (JEMR 2021)

## Citation
Judith Beck and Lars Konieczny (Cognitive Science, University of Freiburg, Germany). 2021. "Rhythmic subvocalization: An eye-tracking study on silent poetry reading." *Journal of Eye Movement Research* 13(3): 5. DOI: 10.16910/jemr.13.3.5. Received 24 November 2019; published 14 September 2021. ISSN 1995-8692.

## Reading task(s)
Comprehension. Silent reading of extended literary/poetic text with a two-stage analysis: reading-time measures first, then word-skipping, then local-context re-reading. The stimuli are long multi-page poems, so sustained comprehension of verse is the task.

## Question/aim
Three questions, stated in §1: (1) would an MRRL rhythm (metrically regular, rhymed language) bearing an "audible gestalt" be perceivable to readers reading *silently*? (2) If so, would eye movements show sensitivity to anomalies within that gestalt? (3) Can eye movements themselves provide evidence for subvocalization, and in which measures? The paper also asks whether the **layout** condition (poem vs. prose) modulates these effects.

## Key theoretical claim
Silent reading of MRRL builds up **auditive expectations** organized around a rhythmic "audible gestalt," and this rhythm is generated **through subvocalization**. This implies an implicit prosody account: phonological/stress representations, not merely visual word recognition, govern eye behavior. The paper motivates this against work on metrical grids (Lerdahl), stress expectation management (Kotz), and entrainment of neural oscillators to rhythm.

## Method
- **N:** 38 participants (23 female, 15 male), mean age 28.87 years (`SD=12.33`, range 19–76), all native German speakers recruited via the Sona System at Freiburg. 29 students or participants with no clear occupation, 8 employees, 1 retiree (aged 76). All had normal or corrected-to-normal vision; naïve to the study purpose.
- **Apparatus:** SR Research EyeLink 1000, **500 Hz**, visual accuracy 0.25°–0.5°, chin-and-head rest, 60 cm viewing distance, **right eye only** tracked, 9-point calibration/validation with spatial error <0.5°.
- **Design:** **2 × 2 between-subject**, layout (poem vs. prose) × version (original vs. rhythm/rhyme-violating), applied to 8 German poems × 4 conditions = 32 texts, distributed across 4 Latin-square presentation lists so each participant saw 2 texts per condition. Presentation order randomized.
- **Typography (held constant):** Trebuchet MS, font size 30, line spacing 1.5, 1920×1080 display, up to 13 lines per page; stimuli spanned up to 3 pages.
- **Manipulations:** metrical anomaly, rhyme anomaly, and combined meter+rhyme anomaly, inserted against ABAB rhyme schemes. First stanza established the rhythm (so readers could acquire expectations); stanzas 3 and 5 were rhythmically regular to allow re-acquisition; stanza 7 allowed complete deviation from the rhyme scheme.
- **Measures:** single fixation durations (SFD), gaze durations (GAZE), regression-path durations (RPD), total reading times (TRT), word-skipping probability, Load Contribution (CLP-style), and region-based re-reading time on pre-rhymes and on the local context.
- **Analysis:** linear mixed-effects models with participants and items as random factors, Satterthwaite df (lmerTest). A staged strategy: main model (design factors only), then complete model (adding lexical/IA variables), then post-hoc contrasts (Table A–C). Extreme values filtered/outlier-trimmed by measure at ≤0.09%.
- **Two-stage approach** (a stated methodological contribution): a reduced "main" model isolates the layout × version × anomaly-type effects, avoiding contamination from lexical predictors.

## Key findings
- **Readers were sensitive to rhythmic-gestalt anomalies in silent reading** — the central claim, and the basis for inferring subvocalization. If no rhythm had been induced, the manipulations would have gone unnoticed.
- **Metrical anomalies** produced robust disruptions **in the poem layout**: a significant three-way interaction of layout × MRRL_version × anomaly-type(metric) for GAZE, RPD, and TRT (SFDs only marginal, `p=.066`, on the two-way test), on top of a two-way layout × metric-anomaly interaction for SFD, GAZE, RPD and a main effect of version for RPD and TRT. Post-hoc contrasts of inconsistent vs. consistent versions in poem layout were significant for SFD, GAZE, RPD, and TRT (directional hypothesis confirmed). Metrical anomalies also read **slower in poem than prose layout** (all measures).
- **Rhyme anomalies behaved oppositely — stronger in prose layout**: reliable three-way interactions for SFD, GAZE, and RPDs plus a two-way layout × rhyme interaction for SFD; post-hoc contrasts significant for gaze durations and RPDs. Prose layout lacks visual verse cues, so rhyme becomes the **anchor** for the poetic gestalt.
- **Combined meter+rhyme anomalies in prose layout** produced *shorter* GAZE but *longer* RPDs than consistent counterparts — interpreted as early regressive saccades during first-pass reading (triggered and completed early).
- **Anomaly-type comparisons in poem layout:** metric vs. rhyme and metric vs. r&m contrasts significant for SFD, GAZE, RPD (r&m significant on all measures).
- **Re-reading was systematic, not incidental:** rhyme anomalies triggered **re-reading of the pre-rhymes**; metrical anomalies caused **re-reading of the local context** (1–6 words before the critical region).
- **Evidence for graded subvocalization:** fixation durations correlated highly with pronunciation length measured in syllables — the correlation with word length/frequency predictors is reported as high in the paper's discussion — and there was parafoveal processing of pronunciation-related features. The authors argue this "clearly speaks in favor of a close alignment of eye movements and the inner voice."
- **TDC-style layout effect:** the paper reports in its framing that verse-final words receive longer total gaze durations when rhyme and/or meter are present (citing Menninghaus & Wallot 2021) and notes Fechino et al. (2020) found longer gaze durations and higher rereading probability in poetry layout.
- **Overall conclusion:** strict verse-by-verse poem layout strengthens rhythmic expectations and yields robust meter-anomaly effects; MRRL in prose layout instead elicits rhyme effects, indicating the language was still processed rhythmically but via rhyme anchors.

## Direction and size if reported
- **Metrical anomaly → ↑ reading time / ↑ gaze duration / ↑ regression in poem layout** (three-way interaction significant for GAZE, RPD, TRT; SFD marginal `p=.066`). Post-hoc directional contrasts significant across SFD, GAZE, RPD, TRT.
- **Rhyme anomaly → ↑ reading time in prose layout**, stronger than in poem layout (three-way interaction significant for SFD, GAZE, RPD).
- **The core finding is an interaction, not a main effect:** meter effects peak in poem layout, rhyme effects peak in prose layout. Exact coefficient estimates, SEs, and effect sizes are tabulated in Table 4 and Tables 6–9 in the source; the extracted text does not preserve the full coefficient table, so no numeric magnitude is asserted here.
- **Syllable-number effects were large** — the paper characterizes the syllable/pronounceability effect on fixation duration as indicating "a high degree of subvocalization," with fixation-duration correlations among lexical variables reaching `.84` (Table 1). This is the strongest quantitative claim about mechanism in the paper.

## Limitations/caveats
Authors' stated limitations (all five):
1. **Stimulus errors and natural-text fragility.** Long natural texts are error-prone; an ABAB rhyme-scheme error crept into the first stanza of "9 Leben" (argued not to affect beat extraction), and two mid-collection corrections were needed — a wrong final word in stanza 5 of "Flüstern" (corrected from participant 23 onward) and apostrophe/orthographic errors (corrected from participant 29 onward). Affected data points were coded accordingly.
2. **Anomalies were not homogeneous.** Adding one vs. two syllables could produce floating stress, diffraction, or an extra beat; the design cannot attribute specific eye-movement reactions to specific kinds of rhythmic deviation.
3. **Anomaly type was confounded with position.** Each anomaly type always occurred at the same location, so anomaly effects may be confounded with practice or position effects. A rotation design is promised for a separate publication.
4. **Lexical covariates of successor words were omitted** — word length and frequency could affect parafoveal recognition and saccade planning but were not analyzed in the complete model.
5. **Position-within-line and position-within-stanza were not modeled**, so within-stanza reading dynamics (which repeat periodically) remain unexamined.
Additional caveats:
- **Ecology/generalizability:** 8 purpose-written German poems, not natural published verse; effects may not extend to non-MRRL poems, where an inherent beat may be absent — the authors flag this as an open question.
- **Sample:** convenience pool including one 76-year-old retiree; no dyslexic or low-vision participants; wide age range (19–76) introduces unmodeled heterogeneity.
- **Right eye only**, desktop monitor at 60 cm — results may not transfer to reading on paper or mobile.
- **No comprehension test.** All conclusions rest on reading-time and re-reading measures; whether anomaly-induced disruption affects comprehension is untested.
- **Design effect sizes reported mostly as significance flags** rather than with full inferential detail in the extracted text.

## Connections
- Concept pages: [[concepts/layout-and-line-breaks]], [[concepts/rhythm-rhyme-and-prosody]], [[concepts/rhythm-rhyme-and-prosody]], [[concepts/selective-attention]], [[concepts/eye-tracking-measures]], [[concepts/eye-tracking-measures]]
- Entities: [[entities/eyelink]], [[entities/university-of-freiburg]]
- Hub: [[syntheses/Comprehension]]
- **The corpus's clearest evidence that line-breaking itself is a causal style variable.** Where most studies manipulate font, size, or spacing, this paper isolates *layout* (verse endings aligned to line breaks vs. mid-line) and finds it interacts with content type: the layout that best supports metrical processing is *not* the one that best supports rhyme processing. Add to [[concepts/layout-and-line-breaks]].
- **Reframes [[concepts/text-direction]]:** the vertical/horizontal debate is about *which axis text flows along*; this paper is about *where breaks fall along that axis*. Related but distinct variables that should not be conflated in the wiki.
- **Complements** [[concepts/selective-attention]]: verse endings function as visual boundaries that elicit pausing, so line breaks operate as attentional markers, not merely whitespace.
- Method note for [[concepts/method-type-divergence]]: the staged main-model-then-complete-model strategy is a good template for factorial typography studies with many lexical covariates, and complements the mixed-model approach in [[sources/font-type-screen-readability-dyslexia]].
- Relevant to skimming: re-reading of local context and pre-rhymes is a precision-reading behavior; the prose layout's reliance on rhyme anchors suggests **removing visual line structure increases the cognitive cost of locating structure** — a caution for layouts that reflow text, relevant to [[syntheses/Skimming]] and to responsive web design.
- Conflicts to log: the paper reports that Menninghaus & Wallot (2021) found longer gaze durations on verse-final words when rhyme or meter present, and that Fechino et al. (2020) found longer gaze durations and higher rereading in poetry layout — these are independent corroborations of a poetry-layout cost. Note that the present study found rhyme anomalies *weaker* in poem layout, a partial disagreement worth recording in [[concepts/rhythm-rhyme-and-prosody]].