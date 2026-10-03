---
type: source
title: "Li, Song, Lu & Zhong (2009) — web page layout, information forms and locations"
reading_tasks: [search]
tags: [source, search, eye-tracking, web-layout, information-form, screen-location, visual-search]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Li, Song, Lu & Zhong (2009) — web page layout, information forms and locations

## Citation
Li, M., Song, Y., Lu, S., & Zhong, N. (2009). The layout of web pages: A study on the relation between information forms and locations using eye-tracking. In *Advanced Multimedia Theory and Technology (AMT 2009)*, LNCS 5820, pp. 207–216. Springer-Verlag. **No DOI.**

## Reading task(s)
**search** (targeted visual search with a known target). Not reading, not comprehension.

## Question / aim
What is the relation between **information form** (text vs graphic) and **information location** (five screen zones) in determining visual-search efficiency on a webpage — a relation previous work had only examined one factor at a time — and do floating advertisements disrupt search?

## Method
- **Design:** Eye-tracking study, **two experiments**. Exp 1 = 5 locations × 2 information forms; Exp 2 = Exp 1 materials + floating advertisements. Participants randomly divided into **10 groups**. Analysis by F-tests on fixation duration with a **100 ms minimum fixation threshold**.
- **N:** **Exp 1: 50** undergraduates/postgraduates, age 21–25 (M = 23.0, SD 1.3). **Exp 2: 50**, age 18–27 (M = 23.0, SD 2.0). All right-handed, normal/corrected vision, frequent internet users, proficient mouse users, **no prior eye-tracking experience**.
- **Materials:** **Artificial, purpose-built pages.** Each page divided into **5 locations** — a center area plus four quadrants (upper-right, upper-left, lower-left, lower-right), each ≈20% of the page, in a "tortoise shell" configuration. **Information form operationalized as exactly two levels: TEXT = a Chinese phrase of 3–6 Chinese words; PICTURE = a well-known corporate logo (Sony, Motorola).** Two pages per location → **10 pages per experiment**. **Each target appeared only once per page**, and was always described in text on a pre-page so participants did not know whether it would be text or picture. 19-in LCD, 1024×768, 60 Hz, ~60 cm.
- **Apparatus:** **Tobii T120, 120 Hz**, via Tobii software.
- **Measures:** EYE-TRACKING only — **fixation duration, defined as the sum of all fixation durations over the whole search task**, used as the sole index of search efficiency, plus first-fixation location. BEHAVIORAL — click-to-confirm. **No accuracy, no search-completion time, no click latency, no saccade amplitude, no scanpath, no pupil.**

## Style/layout variables
(i) **information form** (text vs logo) × (ii) **location** (center, four quadrants) × (iii) **floating advertisement** (present/absent, Exp 2 only), reproduced at real size and speed with a different trajectory per page.

## Key findings
- **Information form main effect: F(1,490) = 76.64, p < .001** — logos are fixated for less total time than text.
- **Location main effect: F(4,490) = 8.34, p < .001.**
- **Information form × location interaction: F(4,490) = 11.16, p < .001.**
- **Picture superiority holds everywhere except quadrant III.** Text is fixated significantly longer than picture at 4 of 5 locations; **in quadrant III the picture is fixated *longer* than text** — the only reversal.
- **Text: worst in the center area and quadrant IV** (both longer than I, II, III; center vs quadrant IV **not** significantly different; no differences among I, II, III).
- **Picture: best in quadrant II, worst in quadrant III.**
- **First fixation is centrally anchored: 90% of participants' first fixation fell in the center area.** The authors explain the center's long total fixation duration via **inhibition of return** — attention returns to center are inhibited, so searching there takes longer.
- **Design recommendation: put important information (text *or* picture) in quadrant II (upper-left);** avoid text in quadrant IV and the center; avoid pictures in quadrant III. For center text, use larger size or bright color.
- **Floating ads had no significant effect** at any location: center F(1,98) = 0.10, p = .75; Q I F = 0.01, p = .92; Q II F = 0.02, p = .89; **Q III F = 3.87, p = .05**; Q IV F = 1.70, p = .20.

## Effect direction & size if reported
Form: picture < text in fixation duration, F(1,490) = 76.64, p < .001 — **the largest effect reported, and the only one with a clean omnibus test.** Location and interaction also large (F = 8.34 and 11.16). Post-hoc contrasts are **figure-embedded significance stars only — no numeric post-hoc F values and no effect sizes are tabulated**.

## Limitations/caveats
- **Internal inconsistency:** quadrant III returns F(1,98) = 3.87, p = .05 — nominally significant, and in the *opposite* direction to the paper's claim — while the text and conclusion state "no significant difference" for all locations.
- **Per-cell n ≈ 5** (50 participants / 10 groups); power for individual location contrasts not reported.
- Chinese-language text and implicitly Chinese participants — **script and reading-direction confounds** limit generalization to LTR/Latin reading, and the "center first-fixation" result may be script-specific.
- Highly artificial 5-zone "tortoise shell" layout with tiny logos; **low ecological validity** for 2009 web pages.
- **Fixation duration as the sole efficiency proxy**, defined in a way (sum over the whole task) that mechanically rewards fewer, briefer fixations; no accuracy or time measure.
- No effect sizes, no numeric post-hoc statistics for the central location × form claims. Short proceedings paper; no DOI.

## Connections
- **Paired directly with [[sources/lu-et-al-2011-visual-search-information-overload]]** — same author group, same 5-zone layout, same Tobii apparatus, extending from form × location to information *quantity*. Read together they form the most complete layout-by-search picture in the corpus, and [[sources/lu-et-al-2011-visual-search-information-overload]]'s recommendation to present important information as a picture independently corroborates the picture-superiority finding here.
- **Adds the spatial dimension the corpus's search literature mostly lacks.** Most search sources manipulate layout *structure* (cards, lists, columns, symmetry); this one manipulates raw *position*. The upper-left recommendation is the corpus's most concrete positional finding — see [[concepts/layout-topology]] and [[concepts/visual-search]].
- **Text-vs-picture as "information form" is the same construct as [[concepts/graphic-type]] and [[concepts/text-graphic-integration]]**, isolated here as a search-efficiency manipulation rather than a comprehension one. Worth noting the wiki's graphic-type evidence is largely comprehension-based; this source extends it to search.
- **The null on floating advertisements is a useful negative** given how much attention ads attract — relevant to [[concepts/information-density]] and to the complexity effects in [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]].
- Hubs: [[syntheses/Search]] · [[concepts/visual-search]] · [[concepts/layout-topology]] · [[concepts/graphic-type]]
