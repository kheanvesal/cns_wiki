---
type: source
title: "Validation of a Web App Enabling Children with Dyslexia to Identify Personalized Visual and Auditory Parameters Facilitating Online Text Reading"
reading_tasks: [comprehension]
tags: [source, dyslexia, personalization, font-size, spacing, tts, assistive-technology]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Lorusso et al. (Multimodal Technologies and Interaction 2024)

## Citation
Maria Luisa Lorusso, Francesca Borasio, Paola Panetto, Mariangela Curioni, Giada Brotto, Giulio Pons, Alex Carsetti, and Massimo Molteni. 2024. "Validation of a Web App Enabling Children with Dyslexia to Identify Personalized Visual and Auditory Parameters Facilitating Online Text Reading." *Multimodal Technologies and Interaction* 8(5), Article 5. DOI: 10.3390/mti8010005. Affiliations: IRCCS E. Medea (Bosisio Parini); Seleggo NPO (Besozzo); Betterdays Ltd. (Milan).

## Reading task(s)
Comprehension, with dictation (writing to TTS audio) as a secondary accuracy outcome. The web app targets online text reading for children with reading disorders.

## Question/aim
Can a web app validly identify *individualized* visual (font, size, spacing) and auditory (TTS voice, speed, pitch) parameters that improve each child's online reading, and does the app's own procedure demonstrate convergent validity across typical and atypical readers?

## Method
- **N:** 78 Italian children, ages 8–14 — **49 atypical reading development (AD)**, **29 typical development (TD)**.
- **Procedure ("Seleggo test"):** an objective, performance-driven selection rather than pure subjective choice. Children read nonwords and pseudosentences; reading time is auto-recorded and accuracy judged by the examiner; the system selects the best combination of font, size, and spacing. Auditory parameters: children choose a preferred voice, then select the nonword the TTS software pronounces best. Objective reading measures, not questionnaire preference, drive visual selection.
- **Validation step:** after selection, each child's performance under their **personalized** parameters is compared **within-subject** against performance under **standard** parameters (average of the two standard fonts; default TTS voice).
- **Statistics:** Mann–Whitney U for group comparisons (nonparametric, given skewed accuracy data); Wilcoxon signed-rank for personalized-vs-standard within-child comparisons, **one-tailed**; Somers' D for asymmetric association between ordinal qualitative variables; chi-square, Lambda, and Goodman–Kruskal tau for font-selection/group association.
- **Conflict of interest:** the Seleggo web app is owned by Seleggo NPO, an author affiliation; a competing financial interest is declared.

## Key findings
- **Group differences confirm task validity** (AD vs. TD): TTS matching accuracy `3.93` vs. `3.78` syllables (median), `U=416, p=0.004`; word reading speed `1.34` vs. `1.07` syll/s, `U=390, p=0.001`; word reading errors `7.30` vs. `19.27`, `U=282.5, p<.001`; pseudosentence reading speed `1.62` vs. `1.30` syll/s, `U=405.5, p=0.002`; pseudosentence errors `4.82` vs. `11.93`, `U=285, p<.001`.
- **Personalization beats standardization** (whole sample, N=78): text reading speed — Seleggo `2.85 (0.51–4.78)` vs. standard `2.85 (0.54–4.70)`, `Z=−1.66, p=0.049` (1-tailed); text reading accuracy — Seleggo `1.63` vs. standard `2.69` errors %, `Z=−1.91, p=0.028`; dictation accuracy — Seleggo `9` vs. standard `9` errors, `Z=−1.65, p=0.0495`.
- **Group predicted size, not spacing:** Somers' `D=0.273, p=0.013` for font size; spacing `p=0.436` (nonsignificant).
- **Font selection frequency did not differentiate groups** on any of the three association measures (all `p>0.05`).
- **Size distribution diverges:** 75% of TD chose size level 2, while AD children were dispersed across the three levels. 40.82% of AD chose spacing level 4 (the widest) versus 34.48% of TD at level 1.
- **No single font wins:** 11 distinct fonts selected as optimal in AD, 14 in TD; the most frequent reached <20% of outcomes. Biryani (`17.24%`/`16.33%`) and Merriweather Sans (`17.24%`/`18.37%`) led; EasyReading™ chosen by only 5–10%; Times New Roman and Roboto by only 2–3%.
- **TTS parameters converge:** both groups performed better with slowed speech (speed `0.8`) and lower pitch (`0.6`); speed Somers' `D=0.150, p=0.054` (trend), pitch `D=0.143, p=0.005`.
- **The strongest personalization benefit is auditory and dyslexia-specific:** dictation personalization was clearly significant in the AD group (`Z=2.05, p=0.020`) but absent in TD (`Z=−0.09, p=0.463`).
- Authors explicitly frame the aim as *not* ranking fonts — the target is each child's own optimum.

## Direction and size if reported
- **Personalized > standard within-child**, on all three outcomes at marginal-to-moderate significance: reading speed `p=.049`, reading accuracy `p=.028` (errors 2.69 → 1.63, a ~39% reduction), dictation accuracy `p=.0495` (median identical at 9, so the gain is in distribution, not center).
- **AD gains from personalization exceed TD gains** specifically for dictation (`p=.020` vs. `p=.463`) — the personalization benefit is concentrated where the deficit is.
- Reading-speed medians are *identical* across conditions (`2.85` vs. `2.85`); the effect is significant on the signed-rank test but **not** visible in the central tendency. Treat the speed gain as weak; the accuracy gain is the more credible one.
- No font-selection effect on group (`p>.05`), so **typeface choice per se carried no signal** here — size and spacing carried the group signal.

## Limitations/caveats
- **Default-option bias in the selection procedure:** sans-serif was pre-selected as the default because it is widely recommended for dyslexia, while children had to actively select among the other two families. This inflates sans-serif representation in the final distribution. The authors state within-family and between-group comparisons remain informative, but any cross-family font comparison is compromised — which limits the font-choice findings substantially.
- **One-tailed tests throughout** for the personalization comparisons, with no clear a-priori hypotheses for the group differences (those were two-tailed). One-tailed testing inflates false-positive risk for the headline claims.
- **Marginal p-values** (`.049`, `.0495`) sit right at threshold.
- **Heterogeneous AD group:** mixes children with a formal diagnosis of specific reading disorder with children having special educational needs. The authors are careful to note results should **not** be read as dyslexia-specific, and the SD is unrelated to that mix.
- **Not a font-ranking study by the authors' own statement** — but the frequency tables invite exactly that reading.
- Small per-cell sample sizes for group × condition comparisons; subgroup analyses were underpowered (differences between groups in personalization benefit were all `p>0.733`, and dictation `p=0.210`).
- Dictation depends on both visual decoding and auditory processing, so it confounds the two personalization channels; the significant AD auditory effect cannot be cleanly attributed to TTS alone.
- Child-selected TTS parameters are subjective even though visual ones were objective — asymmetric procedure across the two modalities.
- Declared competing financial interest (app ownership).
- No long texts, no comprehension test, and no transfer to daily reading; nonwords and pseudosentences only.

## Connections
- Concept pages: [[concepts/individual-differences-in-readability]], [[concepts/font-size]], [[concepts/line-spacing]], [[concepts/font-type-typeface]], [[concepts/preference-versus-effectiveness]], [[concepts/multimodal-and-audio-support]], [[concepts/adaptive-and-personalized-typography]]
- Entities: [[entities/seleggo]], [[entities/irccs-e-medea]], [[entities/text-to-speech-tts]]
- Hub: [[syntheses/Comprehension]]
- **Strongest evidence in the corpus for individualization over population prescription**, and the closest human analogue to [[sources/accelerating-adult-readers-typeface]]'s 51% within-person font range and to [[sources/readability-research-an-interdisciplinary-approach]]'s no-single-format claim.
- **Contradicts the recommendation framing of** [[sources/font-type-screen-readability-dyslexia]] and [[sources/good-fonts-for-dyslexia]]: both recommend specific font sets, whereas this paper finds no font exceeds ~20% of selections and explicitly declines to rank. Same population (dyslexic/dyspraxic children), opposite conclusion — the clearest contradiction pair in the corpus.
- Also contradicts [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]], which nominates a single best typeface (BonvenoCF); here, individualized selection spreads across 11 fonts in AD alone.
- TTS evidence links to the multimodal/assistive strand; note the group-specific auditory benefit is the one place where personalization clearly beat standardization by a non-marginal margin.
- Method contrast worth logging: Lorusso uses **objective performance-based selection**, whereas [[sources/accelerating-adult-readers-typeface]] uses **subjective preference**. Lorusso's data show why — objective selection produces significant within-child gains; subjective preference does not predict effectiveness (41% of readers scored their *lowest* comprehension in their preferred font).