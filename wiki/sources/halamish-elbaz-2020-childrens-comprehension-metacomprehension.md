---
type: source
title: "Halamish & Elbaz (2020) — children's comprehension & metacomprehension, screen vs paper"
reading_tasks: [comprehension]
tags: [source, screen-vs-paper, children, metacomprehension, calibration, primary-school]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Halamish & Elbaz (2020) — children's comprehension & metacomprehension, screen vs paper

## Citation
Halamish, V., & Elbaz, E. (2020). Children's reading comprehension and metacomprehension on screen versus on paper. *Computers & Education*, 145, 1–11. https://doi.org/10.1016/j.compedu.2019.103737

## Reading task(s)
**comprehension** (primary), plus **metacomprehension** as a second outcome.

## Question / aim
(1) Does medium affect children's reading comprehension? (2) Does it affect metacomprehension judgments? (3) Do children prefer paper or screen, and does preference shift after task experience? (4–6) Is the medium effect moderated by medium preference, computer usage habits, or reading skills?

## Method
- **Design:** Within-participants (medium × text), paired-sample t-tests, two-way repeated-measures ANOVA, chi-squared tests, correlations. Pre-registered power sensitivity via G\*Power 3.1.9.2.
- **N:** **38** fifth graders, M_age = 10.95 (SD .31), **22 girls**. All in the normal range on a standardized single-word reading test, so none were excluded. Medium counterbalanced: paper for two texts, screen for two others.
- **Materials:** Four short texts (two per medium); standard **13-pt** font (explicitly contrasted with Dahan Golan et al.'s 15-pt screen presentation). Baseline single-word reading test and a 303-word expository comprehension test, **both on paper**.
- **Measures:** BEHAVIORAL — comprehension 0–1, initial reading time in seconds. SELF-REPORT — metacomprehension 1–5, medium preference pre/post, perceived relative performance, computer usage habits. **No eye-tracking.**

## Style/layout variables manipulated
Reading medium (paper vs screen) and text assignment; font size held at 13 pt as a control.

## Key findings
- **Paper significantly outperformed screen on comprehension:** M = .62 (SD .23) vs .52 (SD .27), **t(37) = 2.17, p = .036** (two-tailed), **Cohen's d = .41**.
- **Reading speed did not differ:** 42 s vs 43 s, **t(37) = .35, p = .729**, d = .03 — the paper advantage came "without a cost in reading time."
- **The positive result sits exactly at the design's power floor.** Sensitivity analysis (α = .05, power .80, N = 38) could detect only **d ≥ .41 one-tailed / d ≥ .47 two-tailed**. The observed d = .41 equals the minimum detectable *one-tailed* effect, while the headline test is two-tailed where the threshold is .47.
- **Metacomprehension did not shift:** numerically higher on screen (4.42 vs 4.29) but null, t(37) = 1.38, p = .177, d = .21.
- ANOVA: significant main effect of **measure** (F(1,37) = 48.30, p < .001, η²p = .57 — the authors flag this as hard to interpret given incompatible scales); **main effect of medium null** (F = 1.89, p = .177, η²p = .05); **medium × measure interaction significant** (F = 6.23, p = .017, η²p = .14).
- Preference: pre-task screen 58% vs paper 42%, **χ²(1) = .95, p = .330**, null. Post-task "easiest medium" null, χ²(2) = 1.63, p = .442. Post-task "performed better" χ²(2) = 6.37, p = .041.
- **The medium effect was unrelated to medium preference** (r = .10, p = .545), to computer usage, or to reading skills.

## Effect direction & size if reported
Comprehension: paper > screen, d = .41, p = .036 — *at the power floor*. Speed: null, p = .729. Metacomprehension: null, p = .177 (numerically screen >). Preference: no significant difference either direction.

## Limitations/caveats
- **Small (N = 38), single grade, and underpowered** — the design could only detect d ≥ .47 two-tailed, above the effect actually found. The headline result should be treated as *at the detection limit*, not as a clean demonstration.
- **Medium is confounded with text:** each child read *different* texts in each medium.
- Metacomprehension and comprehension used **incompatible scales** (1–5 vs 0–1), which the authors concede makes the measure main effect uninterpretable.
- Self-reported preference is unreliable in children and internally contradictory here.
- **Reporting errors:** two different post-task questions ("performed better" and "future preference") both report the identical χ²(2) = 6.37, p = .041 with an identical 24/24/52 split — either a duplication error or miscoded items. The Results state 58% preferred screen while the Discussion says "the majority preferred reading on paper."

## Connections
- **The cleanest primary-study replication of the Kong pattern**: comprehension significant, speed null — see [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]]. Its null speed is *consistent with* Kong's non-significant pooled speed effect rather than contradicting it.
- **The strongest evidence in the corpus against the shallowing account of screen inferiority.** If screen reading degraded comprehension through shallower processing, metacomprehension calibration should have shifted with it. It did not (p = .177) — children could not detect their own comprehension loss. See [[concepts/metacognitive-calibration]] and [[concepts/skim-comprehension-tradeoff]].
- **Preference does not predict the medium effect here** (r = .10, p = .545) — an independent primary-study case for [[concepts/preference-versus-effectiveness]], this time in children.
- Thin representation caveat: this is one of only 4 K–12 studies in Kong's 17-study corpus, and Kong found no significant moderation by school level.
- Hubs: [[syntheses/Comprehension]] · [[concepts/screen-vs-paper]] · [[concepts/metacognitive-calibration]]
