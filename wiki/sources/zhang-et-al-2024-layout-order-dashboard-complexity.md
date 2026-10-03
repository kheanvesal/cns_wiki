---
type: source
title: "Zhang, Zhang, Jiang & Ge (2024) — layout order and interface complexity in dashboards"
reading_tasks: [search]
tags: [source, search, eye-tracking, layout-order, interface-complexity, dashboards, gestalt, statistics-quality]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Zhang, Zhang, Jiang & Ge (2024) — layout order and interface complexity in dashboards

## Citation
Zhang, N., Zhang, J., Jiang, S., & Ge, W. (2024). The effects of layout order on interface complexity: an eye-tracking study for dashboard design. *Sensors*, 24(18), 5966. https://doi.org/10.3390/s24185966

## Reading task(s)
**search** (primary and only). Icon-target visual search and counting. **Comprehension is not measured** — and there is **no text content in the stimuli at all**: chart information is replaced entirely by icons. Skimming is not measured.

## Question / aim
Does "layout order" moderate the adverse effect of interface complexity on visual search, and is the *position of the core chart* the critical component of layout order?

## Method
- **Design:** Two **within-subject** eye-tracking experiments plus a three-stage pre-experimental stimulus-validation phase (simplified abstraction → subjective ratings → computed symmetry and unity). Exp 1: **2 (layout order) × 3 (complexity)**. Exp 2: **3 (layout order) × 3 (complexity)** plus a 5-position core-chart sub-analysis. Linear mixed-effects regressions in R with likelihood-ratio tests and ΔAIC; **a priori power analysis reported**.
- **N:** Validation phase **50** volunteers. **Exp 1: 43 recruited → 1 dropped (2 SD below remaining mean) → 42 analyzed** (17 M / 26 F, 20–25 y, mean 22.3). **Exp 2: 40** (17 M / 23 F, 21–26 y, mean 23.9). All right-handed, normal/corrected vision, no color blindness, digital-interface experience. Single Chinese university (Nanjing Forestry University).
- **Platform:** Dashboard-style interfaces at 1920×1080. Derived from **200 real dashboards → 60 "typical" interfaces → abstracted → 36 standardized stimuli**. **Monochromatic**: black charts on white background, **core chart outlined in red**.
- **Definition of "layout order" — not reading order.** It is a two-part construct: (1) **overall visual order**, the degree of **visual symmetry and unity** among charts, computed from NGO's (1977) aesthetic model; (2) **sequential browsing order**, the **position of the "core chart."** Levels: **High** = fully symmetrical/uniform, core chart centered (symmetry ≈ 1.0, unity ≈ 0.89–0.91); **Mid** = partially symmetrical, core chart on an axis but off-center; **Low** = asymmetrical, core chart off every axis. **Complexity operationalized purely as chart count: low 5, medium 9, high 13.**
- **Apparatus:** **Tobii 250 Fusion**, screen-based remote, 250 Hz, accuracy 0.9°; ErgoLAB; HP 27-in; viewing distance 580–620 mm. ~300 lx office lighting.
- **Measures:** BEHAVIORAL — response time (correct trials only; Exp 1 3.3% errors, 10.3% excluded as MAD outliers; Exp 2 3.9% errors, 5.5% excluded); accuracy measured implicitly via payment but **not reported as an outcome**. EYE-TRACKING — total fixation count (TFC), total gaze duration (TGD), scanpaths, hotspot maps, with **AOI = the multi-chart area outside the red-bordered core chart**. SELF-REPORT — none in the experiments (5-point Likert used only for stimulus construction).

## Key findings
- **Stimulus validation confirms the manipulation:** unity F(2,33) = 46.11, p < .001; symmetry F(2,33) = 235.4, p < .001. *(Text says 45 interfaces but df = 33 and Table 2 lists 36 — internal inconsistency.)*
- Icons successfully equated: concreteness F(19,980) = 0.027, p = .871; complexity p = .845; familiarity p = .805.
- **Power: 0.985 (Exp 1) and 0.979 (Exp 2)**, at an assumed **large** η²p = 0.14.
- **Exp 1 complexity main effect on RT:** ΔAIC = −1795.5, LLRχ²(1) = 1799.52, **p < .001**.
- **Exp 1 layout order main effect: RT decreases from low to high layout order**, ΔAIC = −25.7, LLRχ²(1) = 27.72, **p < .001**.
- **Exp 1 order × complexity interaction:** ΔAIC = −16.5, LLRχ²(1) = 20.53, **p < .001** — the RT advantage of high order *widens* as complexity increases.
- **TFC cell means (low→high complexity):** disordered 5.170 → 10.158 → 14.048; ordered 4.286 → 8.899 → 12.257. Order effect p < .001; interaction p < .001.
- **TGD cell means:** disordered 0.874 → 1.755 → 2.543 s; ordered 0.748 → 1.561 → 2.196 s. Order p < .05; interaction p < .05.
- **Scanpath/hotspot qualitative findings:** both order types begin on the target icon in the core chart, then shift to the no-core area. **High-order interfaces produce left-to-right, top-to-bottom scanpaths with balanced, symmetrical hotspots; low-order produce scattered scanpaths and markedly redder (more fixated) hotspots in the no-core area.**
- **Exp 2 replications:** complexity RT p < .001; **order RT p < .001**; core-chart location RT p < .001; TFC complexity p < .001, order p < .001; TGD complexity p < .001, order p < .001.
- **Five-position comparison: left-center significantly faster than mid-center on RT**, reported p < .05. Left-center/mid-order scanpaths traverse the no-core area **clockwise**, clearer and more consistent than mid-center/high-order.
- **Theoretical account:** Gestalt grouping (symmetrical elements group faster → fewer units, lower load) + chunking theory + VWM capacity ~4 objects, which explains why the high-order advantage is *weakest at low complexity* (only 4 no-core charts, within VWM capacity).

## Effect direction & size if reported
Directionally unambiguous and large: higher layout order → faster, fewer, shorter fixations; complexity → more of everything; the order advantage grows with complexity in Exp 1. **However the inferential reporting is internally unreliable** (see caveats), so magnitudes should not be cited.

## Limitations/caveats
- **Mathematically impossible reported statistics:** negative LLRχ² values (−736.19, −5.58), χ²(1) = **1.26 reported with p < .05**, and "LLRχ²(1) = 22291.30". ΔAIC signs and magnitudes are inconsistent; one interaction is called significant at p = .045 with a negative ΔAIC. **The Exp 2 order × complexity interaction fails to replicate** (TFC p = .61, TGD p = .21) despite being reported as significant on RT with contradictory values.
- **The headline recommendation (left-center > center) is supported by RT only and directly contradicted by both eye-tracking metrics** (center vs left-center null on TFC p = .82 and TGD p = .86). Core-chart position is null as a main effect on both (p = .48, p = .22). **Flag as contested.**
- Authors' own remaining confounds: chart size inconsistencies, non-core chart aspect ratios, proportion of white space.
- **Icons-as-content is drastically simpler than real dashboard content** — no text, color coding, or animation.
- Target-icon redundancy (1–3 identical copies) may itself alter search behavior; task limited to search, not data analysis or decision-making.
- Eye tracker could not obtain temporal/spatial AOI data.
- Not underpowered (power 0.985 / 0.979), but the assumed effect size is large and the reporting, not the sample size, is the binding weakness.

## Connections
- **The corpus's clearest statement that "layout order" is a distinct variable from reading order.** Anyone reading "layout order" as left-to-right vs top-to-bottom would misread this paper — the manipulation is **symmetry/unity plus core-chart position**. This matters for [[concepts/layout-topology]] and for how the corpus should treat "order" claims at all.
- **Independent support for Gestalt grouping as the mechanism behind layout effects on search**, arriving from a different paradigm (abstracted dashboards) than the web-page work. It corroborates the visual-ordering account in [[sources/li-2009-web-layout-information-forms-locations]] and the scanpath evidence in [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]] (left-to-right, top-to-bottom scanpaths under high order).
- **The VWM-capacity explanation for why layout order matters more under high complexity is a testable mechanistic claim the corpus otherwise lacks** — it predicts an *interaction* between complexity and order, which is exactly what [[sources/lu-et-al-2011-visual-search-information-overload]] also found for information quantity (though there the effect was that overload reduces parallel processing). Two sources, two paradigms, converging on complexity as the moderator.
- **Contested status is the honest headline:** RT results and eye-tracking results disagree, and Exp 2's interaction does not replicate. Cite as suggestive, not established.
- Complexity effects connect to [[concepts/information-density]] — and note the contrast with [[sources/li-2009-web-layout-information-forms-locations]], where **floating advertisements had no significant effect** on search. Layout *order* matters here; layout *clutter* did not there. Different measures (Tobii total fixation count vs 100 ms-thresholded fixation duration) plausibly explain part of the divergence.
- Hubs: [[syntheses/Search]] · [[concepts/layout-topology]] · [[concepts/visual-search]] · [[concepts/information-density]]
