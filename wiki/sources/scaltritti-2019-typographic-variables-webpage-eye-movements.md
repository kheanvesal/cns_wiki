---
type: source
title: "Scaltritti et al. (2019) — typographic variables on webpage reading, eye movements"
reading_tasks: [comprehension]
tags: [source, eye-tracking, web-layout, typographic-variables, dyslexia, naturalistic, mixed-effects]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Scaltritti et al. (2019) — typographic variables on webpage reading, eye movements

## Citation
Scaltritti, M., Miniukovich, A., Venuti, P., Job, R., De Angeli, A., & Sulpizio, S. (2019). Investigating effects of typographic variables on webpage reading through eye movements. *Scientific Reports*, 9, 12711. https://doi.org/10.1038/s41598-019-49051-x

## Reading task(s)
**comprehension** (primary). Silent self-paced reading of real webpages; no search component.

## Question / aim
Which visuo-typographic features of **real** webpages affect eye movements during reading, and do those effects differ by age (adults vs children) and reading ability (typical vs dyslexia)? Explicitly framed as an ecological complement to factorial manipulations using artificial stimuli.

## Method
- **Design:** Eye-tracking study, **naturalistic/correlational, within-subject** — not a factorial manipulation. 50 real webpages sub-sampled from 160 to maximize predictor variance; predictors entered as **continuous measured properties** in 4 sequential blocks (luminance contrast → font size + line spacing → font type/style → column width + left alignment) in linear mixed-effects models, with stepwise backward elimination and likelihood-ratio comparison. Random intercepts for participants and webpages.
- **N:** 85 Italian native speakers recruited → **4 excluded** (2 non-completion, 1 eye-tracking difficulty, 1 incompatible reading scores) → **final N = 79**. Adults typical 20 (15 F, 23.55 y); Adults dyslexia 20 (9 F, 22.43 y); Children typical 20 (10 F, 11.55 y); **Children dyslexia 19** (7 F, 11.47 y).
- **Materials:** **Real webpages** saved as 1,600-px-wide screenshots, sliced into 1,200-px pieces (mean 2.36/page, SD 0.66), bottom whitespace padded with dark-gray hatching to emulate scrolling. Italian. Each participant saw **5 pages**; each page was seen by only **2 participants per group**.
- **Apparatus:** **EyeLink 1000 Plus**, desktop mount, 1,000 Hz, right eye (3 left), velocity 30°/s, acceleration 8,000°/s; chin rest, 75 cm, 21-in 40×30 cm monitor; E-Prime 2.
- **Measures:** EYE-TRACKING — average fixation duration, fixation count, average saccade amplitude, restricted to text AOIs; blinks and blink-adjacent fixations <100 ms removed; durations and amplitudes **log-transformed**. BEHAVIORAL — 2-AFC comprehension accuracy **collected only as an attention check, never reported**. SELF-REPORT — post-page interest, website familiarity, perceived audience; **perceived reading difficulty lost to a programming error**.

## Style/layout variables
**13 measured predictors** (11 visuo-typographic + 2 linguistic): amount of text; page length; luminance contrast (WCAG 2.1 ratio); font size (log 1.61–3.97, page-averaged **10–18.46 pt**); line spacing (**40%–350% of font size**, page-averaged 110%–201%); sans-serif proportion; bold proportion; italic proportion; underlined proportion; header proportion; column width (max cpl, length-weighted); left-alignment ratio; plus SUBTLEX-IT word frequency and mean word length.

## Key findings
- **Font size ↓ average fixation duration** (b = −0.13, SE = .04, t = −3.12), **stronger in children** (Age × Font Size b = −0.10, t = −3.09), **not moderated by dyslexia**. Adults: ~20 ms difference between smallest and largest font text.
- **Font size ↑ saccade amplitude** (b = 0.43, t = 5.24) with **no effect on fixation count** — interpreted as accommodation to larger orthographic stimuli, not a perceptual-span change.
- **Line spacing ↑ saccade amplitude** (b = 0.52, t = 2.18); **adults benefit, children null** (Age × Line Spacing b = −0.42, t = −2.55).
- **Page length ↓ fixation duration** (b = −2.54e−05, t = −3.48) holding amount of text constant — larger pages are *less* visually crowded.
- **Left-aligned text ↓ fixation count** (b = −0.26, t = −2.09); **more headers ↓ fixation count** (b = −0.92, t = −2.32); both homogeneous across groups. Headers did not affect saccade amplitude → interpreted as reduced **second-pass reading/regressions**, not span.
- **Column width is the complex result.** Three-way Age × Dyslexia × Column Width: b = 0.33, t = 3.24. Narrowest→widest change in fixation count: **typical adults ~10% increase (301→331); children with dyslexia ~18% increase (482→569); adults with dyslexia ~19% *decrease* (532→430); typical children ~22% *decrease* (476→370)**. The authors state this "calls for additional investigations."
- **Dyslexia cost on fixation duration scales with age** (Age × Dyslexia b = 0.18, t = 2.63).
- **Amount of text ↑ fixations** (b = 2.97e−04, t = 8.17) **attenuated in children** (b = −5.95e−05, t = −2.77) while saccade-amplitude increase is **exaggerated** in children (b = 1.30e−05, t = 2.20) → interpreted as children skimming longer texts.
- **Guideline support table (Table 4):** supported = limit page content, min 12–14 pt, 1.5 line spacing, use section headings, left-justify; partial = avoid wide columns; **null = high luminance contrast, avoid italics, use bolding, avoid underlining, plain sans-serif**.

## Effect direction & size if reported
Coefficients are reported as b, SE, and **t only — no p-values anywhere in the paper**, and block-level LRTs are deferred to Supplementary Tables S1–S2. Directional summary: font size ↑ → fixation duration ↓ and saccade amplitude ↑; line spacing ↑ → saccade amplitude ↑ (adults); left alignment and headers → fixation count ↓; column width → reverses sign across four age×ability groups.

## Limitations/caveats
- **No p-values are reported for any coefficient.** The effects carrying the paper's conclusions are presented as t-values only.
- **Correlational, not causal.** The 50 "combinations" are measured natural webpage configurations, so **no causal claim about any single typographic variable is licensed** — the title's "effects of typographic variables" overstates what the design supports.
- **Extremely low per-item exposure:** each page seen by only 2 participants per group; 5 pages per participant.
- **Comprehension accuracy was collected but never reported**, and the perceived-difficulty item was lost to a programming error — so the paper cannot connect its eye-tracking results to comprehension at all.
- Visual acuity not assessed pre-experiment (authors' own limitation). Static screenshots with simulated scrolling; exploration permitted during reading.
- Dyslexic participants had instructions and questions **read aloud**, so were not blind to group status. Fonts likely too small to reveal the dyslexia-specific crowding benefit the authors expected.
- Subgroup cells of 19–20 are small for interaction tests (dyslexic children n = 19).
- Italian only. Table 4 states line spacing as "1.5 point," ambiguous (likely 1.5×).

## Connections
- **The ecological counterpart to the factorial studies, and the reason it must be cited with care.** Its nulls on italics, bold, underline, luminance contrast, and font type are *the most consequential in the corpus* precisely because they come from real pages in realistic ranges rather than artificial extremes — this is the strongest available answer to [[sources/ho-sang-petrarca-2025-beyond-typeface-value]]'s observation that typeface effects are null in typical ranges, and to [[sources/tarasov-legibility-of-textbooks-2015]]'s familiarity/preference framing.
- **Directly tensions with the corpus-wide italic penalty.** The italic finding elsewhere is a *style-level tracking-metric* effect (see [[concepts/italic-and-slant]]); here italic proportion is null. Both can hold — italic is bad when used as the body face, unremarkable when sprinkled as emphasis at typical web proportions — but the wiki should say so rather than let the contradiction stand unexplained.
- **Its column-width sign reversal across four groups is the single strongest evidence that line length cannot be given a directional recommendation independent of reader.** This is a major input to [[concepts/line-length]] and to the contradictions section of [[syntheses/Comprehension]]. Compare the ≈45 cpl inverted-U optimum in [[sources/porte-2001-typographical-error-salience-l2]] and the 45–75 cpl range in [[sources/nanavati-bias-2005-optimal-line-length]].
- **Children skimming longer texts** (attenuated fixation growth, exaggerated saccades) is independent evidence for [[concepts/skimming-strategy]] as an age-graded strategy, and connects to [[sources/halamish-elbaz-2020-childrens-comprehension-metacomprehension]].
- **Supports the existing web-layout consensus** at [[concepts/web-layout]] (headers help, left alignment helps, wide columns risky) while uniquely quantifying the cost.
- Hubs: [[syntheses/Comprehension]] · [[concepts/web-layout]] · [[concepts/line-length]] · [[concepts/eye-tracking-measures]]
