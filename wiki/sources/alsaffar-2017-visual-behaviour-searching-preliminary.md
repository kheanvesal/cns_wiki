---
type: source
title: "Alsaffar et al. (2017) — visual behaviour in searching information (preliminary)"
reading_tasks: [search]
tags: [source, search, eye-tracking, SERP, reading-direction, RTL-LTR, preliminary, descriptive-only]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Alsaffar et al. (2017) — visual behaviour in searching information (preliminary)

## Citation
Alsaffar, M., Pemberton, L., Rodriguez Echavarria, K., & Sathiyanarayanan, M. (2017). Visual behaviour in searching information: an eye tracking preliminary study. In *2017 IEEE International Conference on Computer Networks & Communications (Comsnets 2017)*. IEEE. ISBN 978-1-5090-5476-3/17. **No DOI.**

## Reading task(s)
**search** (primary). Skimming behavior is described qualitatively but **no skimming outcome is operationalized**.

## Question / aim
Do Arabic (RTL) and English (LTR) users differ in visual-search behaviour and eye movements on the **same English Google SERP**, and are those differences modulated by task type or SERP presentation type? Explicitly a preliminary methodological demonstration.

## Method
- **Design:** **Controlled eye-tracking study, descriptive only** — "As this is a preliminary study results, only two tasks are presented." Analysis in Excel + Tobii Studio. **No inferential statistics performed.**
- **N:** 40 recruited (20 Arabic, 20 English) → **2 excluded from each group for calibration difficulties → 36 analyzed: 18 Arabic + 18 English.** All University of Brighton students (UG/PG), highly educated, technologically literate.
- **Apparatus:** **Tobii eye tracker with Tobii Studio**, AOIs drawn with the built-in definition tool, region-based AOI method (after Salvucci 1999). **Not EyeLink and not head-mounted** — but **the model, sampling rate, temporal resolution, accuracy, viewing distance, and monitor specification are never reported.**
- **Materials:** Real Google SERPs retrieved in advance, saved locally, and provided by the experimenter so results were identical across participants; general-domain topics to limit familiarity. **Task A — plain SERP** (no ads, images, or enriched snippets): "Find a book about child care written by Miriam Stoppard." **Task B — enriched SERP** (enriched snippets + right-hand modules: maps, images, related searches): "How many animals in Pretoria Zoo."
- **Layout variables:** SERP presentation type (plain vs enriched) × result rank/position (results 1–10, **the first two being advertisements**) × user reading direction/culture (Arabic RTL vs English LTR).
- **Measures:** EYE-TRACKING — **time to first fixation** per AOI, fixation count, total fixation duration, fixation order (visualized after Bojko 2013), heat maps. Each SERP divided into **15 AOIs**. BEHAVIORAL — **none quantified**; task accuracy/success not reported as an outcome, no search-completion time. SELF-REPORT — demographics collected but **not analyzed**; satisfaction ratings **not collected**.
- **Reporting note:** time-to-first-fixation and fixation durations are labelled "msec" but the magnitudes (0.23–6.56) are seconds. **This is a unit error in the source.**

## Key findings
**All descriptive. No test statistic, p-value, or effect size appears anywhere in the paper.**
- **Task A, first fixation:** ~**88% of Arabic users fixated first on Result2**, then Top. **Almost 100% of English users fixated first on Result3** — the first *organic* result — because they skipped the first two positions, **which were advertisements.**
- **Task A, fixation count:** Arabic total 1407, mean **108.94**; English total 1337, mean **98.12**. Arabic peaked on Result5 then 7, 6; English on Result7 then 6, 5. **~13% of average fixation count fell on Result7 for both groups** — Result7 held the answer.
- **Task A, fixation duration:** Arabic 471.3 vs English 372.8. **~10% of Arabic participants' fixation duration went to Top and Related Search; English fixated on neither at all.** Top three: Arabic 24% vs English 17%. **Bottom three: Arabic 13% vs English >28%.**
- **Task A strategy:** Arabic read all results sequentially top-to-bottom **despite the first two being ads**; English jumped result-to-result without completing sentences and ignored the ads.
- **Task B, first fixation:** Arabic on Result2 then Top; **English on Middle Images** then Result2. **Counter to the RTL hypothesis, English reached the right-hand side FASTER** (Arabic mean 6.56 s, 5th fixation; English 1.78 s, 3rd).
- **Task B, fixation count:** Arabic mean **98.92**; English mean **119.15**. Most fixations for both fell on **Top Right** (avg 12% Arabic, 18% English). **The Top AOI drew fixations from Arabic users but none from English users** in both tasks. Top Right and Bottom Right drew substantially more from English than Arabic.
- **Task B strategy:** Arabic read the first results intensively and trusted the top three; English jumped between results picking keywords from snippets.

## Effect direction & size if reported
**No effect sizes or statistics exist to report.** Directionally: Arabic users distribute fixations more evenly top-to-bottom and engage lower-ranked results less (bottom three 13% vs >28%); English users concentrate on the upper results, skip advertisements, and — in Task B — reach right-column content faster despite being LTR.

## Limitations/caveats
- **Reports no statistics at all.** The authors state the "main part of the analysis" and "solid conclusions" remain future work. Every claim above is exploratory and must be cited as such.
- Only **2 of 3 planned tasks** analyzed; the Chinese group and mobile presentation not done; satisfaction data not collected.
- **n = 18 per group** after a 20% calibration loss — far too small for a cultural-comparison inference, and the losses may indicate systematic tracking difficulty.
- Unrepresentative sample: single UK university, students.
- **Confounded manipulation:** Arabic participants searched an **English** SERP, so language proficiency is entangled with culture and reading direction. **The RTL-predicted advantage did not materialize** — English reached right-column content faster.
- Implausible unit labels ("msec" for second-scale values). Apparatus under-specified; no accuracy, no task time, no success measure. Task topics may cue prior knowledge. **No DOI; 5-page paper with figure-dependent reporting.**

## Connections
- **The corpus's primary evidence that reading direction changes search allocation**, and it is also its most under-powered source for the point. Because the RTL prediction *failed*, the paper's most defensible contribution is negative: reading direction is **not** sufficient to predict right-column search speed. That belongs in [[concepts/text-direction]] as an open question rather than a settled effect, alongside the significant vertical-vs-horizontal fixation differences in [[sources/chinese-typography-eye-tracking-vertical-horizontal]].
- **Ads as a confound on SERPs is the practically important thread.** Both tasks show English users skipping the two leading advertisements and landing on the first organic result, while Arabic users processed them sequentially. This is a clean illustration of [[concepts/information-seeking-modes]] differing by user population — and it is exactly the kind of effect that a layout recommendation (e.g. "put important content upper-left", from [[sources/li-2009-web-layout-information-forms-locations]]) presumes without controlling for ads.
- **Its self-described preliminary status and total absence of statistics make it a useful contrast case with [[sources/lu-et-al-2011-visual-search-information-overload]]**, which shares the topic and instruments and *does* report p-values — showing what "preliminary" costs in evidential terms. Worth citing in [[concepts/methodology-critique]].
- The 15-AOI region decomposition is a reusable instrument description for [[concepts/visual-search]].
- Hubs: [[syntheses/Search]] · [[concepts/visual-search]] · [[concepts/text-direction]] · [[concepts/information-seeking-modes]]
