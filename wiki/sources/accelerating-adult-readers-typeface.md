---
type: source
title: "Accelerating Adult Readers with Typeface: A Study of Individual Preferences and Effectiveness"
reading_tasks: [comprehension]
tags: [source, typeface, individual-differences, preference, reading-speed, self-report]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Wallace et al. (CHI 2020 Extended Abstracts)

## Citation
Shaun Wallace, Ben D. Sawyer, Rick Treitman, Zoya Bylinskii, and Jeff Huang. 2020. "Accelerating Adult Readers with Typeface: A Study of Individual Preferences and Effectiveness." *CHI '20 Extended Abstracts*, April 25–30, 2020, Honolulu, HI, USA. ACM. DOI: 10.1145/3334480.3382985

## Reading task(s)
Comprehension. Explicitly framed around speed-under-retained-comprehension: the authors define an "effective" font as one yielding high words-per-minute *and* high comprehension, explicitly guarding against mistaking skimming for benefit.

## Question/aim
If users could pick their preferred typeface, would that also be their most effective typeface for reading — measured in speed and comprehension? And is any single font best for all users? The paper states the motivating premise that every adult reader would benefit from faster reading provided comprehension is retained.

## Method
- **N:** 63 recruited (12 university mailing lists, 15 UserTesting.com, 36 Amazon Mechanical Turk); 3 university participants removed for unusually low comprehension scores or lack of comfort with English, leaving **60 analyzed**; 9% of data from the final 60 removed by pre-specified preprocessing.
- **Demographics:** ages 18–55, average 31; 51% female.
- **Setting:** unconstrained web study on participants' own devices in their natural environments, ~40 minutes, $5–$20 compensation.
- **Stimuli:** 16 fonts; passages at 8th-grade reading level, each with two comprehension questions.
- **Preference procedure:** a *toggle task* — participants switch a fixed-width 420px interface (line spacing 1.5, text size locked via custom JavaScript) between paired fonts and stop on the one easier to read, iterated as a double-elimination tournament over pairs to yield a single most-preferred font. This deliberately avoids Likert scales.
- **Effectiveness procedure:** comprehension tests, then a toggle task in which participants read half the passages in their preferred font.
- **Measures:** words-per-minute (WPM), proportion of comprehension questions correct, font familiarity rating (self-report), and post-reading passage interest (5-point Likert).

## Key findings
- **Preference and effectiveness dissociate.** Participants read in their most preferred font at an average of **303 WPM**; in their fastest font at **347 WPM** (15% faster). Only **18%** read fastest in their preferred font; **23%** read slowest in their preferred font. Slowest-font average was 230 WPM, giving a **51% spread** between an individual's slowest and fastest font.
- **Comprehension is also not predicted:** ~59% scored highest comprehension in their preferred font, but **41% scored the lowest** with their preferred font.
- **Beliefs are wrong about the user's own case.** 80% of participants believed their preferred font would also be their most effective; the preference test was nevertheless reliable as a preference measure (92% agreed with their final font recommendation).
- **Font familiarity does not predict anything:** no effect on reading speed (`r=0.042`) or comprehension (`r=0.033`).
- **No font is best for everyone.** Top preference winners were Noto Sans (9 participants), Montserrat (8), and Garamond (8) — a spread-out, near-tied distribution rather than a consensus winner. Results held across three recruitment populations.
- **Interest beats typeface as a speed determinant:** participants slowed down on passages they found interesting (Fig. 4), a confound for unmoderated speed comparisons.
- Qualitative observation: younger participants tended to prefer and read faster in *smaller* fonts.
- Headline claim: people read 51% faster in their fastest than slowest font, translating to roughly 10 additional pages of reading per hour.

## Effect direction & size if reported
The effect is an **individual-level range, not a font-level ranking**: within-person fastest-vs-slowest font difference = **51% of WPM**; preferred-vs-fastest = **15%**. Preferred font was fastest for only 18% of readers. No omnibus font-level speed effect is reported — the paper's finding is heterogeneity, not a winner.

## Limitations/caveats
Extended abstract (limited space; some analyses abbreviated). Self-selected device and environment introduce uncontrolled variance in screen size, font rendering, and reading posture. Comprehension was measured with only two questions per passage, which is coarse for the construct the paper's central claim depends on. Exclusion criteria removed 3 participants plus 9% of data based on WPM/comprehension outliers, which could preferentially remove high-variance readers — the very population where individual differences matter most. No dyslexia or low-vision participants (such cases were actively screened out), no non-native readers, no eye-tracking, and no paper/screen comparison. Passages were short, single-genre, 8th-grade level. Passage interest co-varies with speed and was not statistically controlled. Self-report familiarity ratings are weak instruments.

## Connections
- Concept pages: [[concepts/individual-differences-in-readability]], [[concepts/preference-versus-effectiveness]], [[concepts/font-type-typeface]], [[concepts/skim-comprehension-tradeoff]]
- Entity: [[concepts/individual-differences-in-readability]]
- Hub: [[syntheses/Comprehension]]
- **Directly relevant to Wilkins 2020**: the finding that preference misleads is the empirical case for not shipping default fonts on self-report alone, and for individual-level rather than population-level font selection.
- Tension with [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] (Lorusso et al.): Lorusso finds large *within-child* gains from individualized parameters, which Wallace's 51% within-person speed range independently corroborates.
- Tension with [[sources/readability-research-an-interdisciplinary-approach]] (Beier et al.), which is partly authored by Wallace/Sawyer/Treitman and recommends individual-context tuning; this paper supplies the supporting evidence that within-individual variance exceeds between-font variance.
- Contrast with [[sources/font-type-screen-readability-dyslexia]] (Rello & Baeza-Yates): that study seeks population-level *recommendations* for dyslexia; this study finds no consensus winner among typical adults. The apparent disagreement is partly a matter of population (dyslexic vs. typical readers) and partly of outcome (category-level vs. individual-level).