---
type: source
title: "Kong, Seo & Zhai (2018) — screen vs paper meta-analysis"
reading_tasks: [comprehension]
tags: [source, meta-analysis, screen-vs-paper, medium, comprehension, reading-speed]
created: 2026-10-02
updated: 2026-10-02
source_count: 1
---

# Kong, Seo & Zhai (2018) — screen vs paper meta-analysis

## Citation
Kong, Y., Seo, Y. S., & Zhai, L. (2018). Comparison of reading performance on screen and on paper: A meta-analysis. *Computers & Education*, 123, 138–149. https://doi.org/10.1016/j.compedu.2018.05.005

## Reading task(s)
**comprehension** (primary). The included literature spans several task types, but the pooled outcomes are comprehension scores and reading speed.

## Question / aim
Quantify the mean difference in reading comprehension and reading speed between screen and paper, and test whether that difference is moderated by publication year, country, or on-screen medium type.

## Method
- **Design:** **Robust Variance Estimation (RVE) meta-analysis** with robust-variance meta-regression (`robumeta`), α = .05. RVE chosen because of many correlated effect sizes per study; small-sample corrections via Tipton & Zhipeng (`formula = d~1, var.eff.size = v, rho = .80, small = TRUE`). Sensitivity analysis across ρ = 0 → 1.00 reported and robust.
- **N:** **17 studies** (16 journal articles + 1 dissertation); **47 effect sizes** for comprehension, **19 effect sizes** for speed. Total participant pool not stated as a single N.
- **Corpus composition:** 6 US, 4 Scandinavian, 4 rest-of-Europe, 2 Israel, 1 South Korea. 9 studies pre-2013. Screen type: computer in 14, portable readers in 5. Populations: 11 post-secondary, 4 K–12, 1 job-level, 1 mixed-age. Text types: 10 expository, 3 narrative, 4 unspecified. Text length where reported ≈300–2,000 words.
- **Measures:** comprehension test/quiz scores and reading speed as standardized mean differences. No eye-tracking, no self-report in the synthesis.

## Style/layout variables manipulated
None manipulated — **moderated**. Medium (screen vs paper), screen type (computer vs other), text type (expository vs narrative), publication year (collapsed at a 2013 cut), country.

## Key findings
- **Comprehension favors paper significantly:** screen−paper **g = −.21, 95% CI [−.38, −.03], p = .02**, τ² = .11, **I² = 73.23%**.
- **Speed does not differ:** screen−paper **g = .48, 95% CI [−.15, 1.11], p = .11**, τ² = .85, **I² = 93.36%**.
- **The dissociation is the paper's central claim:** comprehension is reliably worse on screen; speed is not reliably different.
- **No comprehension moderator reached significance.** Year b = .26–.27 (p = .09–.10); Country b = .06 (p = .80); screen Type b = .22, CI [−.42, .86] (p = .41).
- **Every speed moderator is disqualified by the authors' own rule.** Table 5b note 2: "degrees of freedom for the moderators shown in Models 2 and 3 are less than 4," against note 1's standing caveat that results with df < 4 "should not be trusted." Speed Type df = **1.96**.
- **The "diminishing trajectory" highlight is not supported:** it rests on the non-significant Year coefficient (b = .26, p = .09).
- **Moderators excluded as unusable:** gender, grade, sample size, sampling method, research design — all failed RVE subgroup requirements. So the meta-analysis is silent on the variables most central to the field's disputes.

## Effect direction & size if reported
| Outcome | Pooled effect (screen − paper) | Heterogeneity | Usable? |
|---|---|---|---|
| Comprehension | g = −.21, CI [−.38, −.03], p = .02 | I² = 73.23% | Yes, but no moderator explains it |
| Reading speed | g = .48, CI [−.15, 1.11], p = .11 | I² = 93.36% | No — df < 4 voids all moderators |

## Limitations/caveats
- **Only 17 studies**, and the speed outcome rests on **8 studies / 19 effect sizes** — thin for RVE, as the authors concede.
- **High heterogeneity in both outcomes** (73% and 93%); pooled point estimates conceal substantial between-study variation, and **no moderator accounts for any of it**.
- **Reporting errors in the source:** Table 5a Model 1 prints an intercept of `+.35` with CI `[−.57, −.13]` — the estimate lies outside its own interval; the earlier intercept table gives −.44, which *is* inside the interval, so `+.35` is a sign typo. The entire "df" column is non-integer (6.58, 13.29, 2.99, 1.96, …) and therefore mislabeled. Table 5a reports `k = 16` for comprehension where the text says 17. **No Cochran's Q is reported** — only residual τ² — so per-moderator heterogeneity cannot be recovered from this paper.
- Moderator coding agreement 82–100%; no formal risk-of-bias instrument applied to included studies.
- Predates the 2020s screen literature in this corpus entirely.

## Connections
- **The anchor for [[concepts/screen-vs-paper]]**, and the quantitative version of the speed-vs-comprehension split independently stated by [[sources/tarasov-legibility-of-textbooks-2015]] ("speed is more sensitive to typographical factors than comprehension"). [[sources/halamish-elbaz-2020-childrens-comprehension-metacomprehension]] replicates exactly this pattern at the primary-study level: comprehension significant, speed null.
- Pooled `g = −.21` matches the primary estimate in [[sources/mangen-walgermo-bronnick-2013-paper-screen-comprehension]] (`b = −.216`) closely enough that Mangen is plausibly load-bearing for the pooled figure — but note the **non-significant screen-type moderator** means Mangen's *computer-screen* condition is averaged with tablet and e-reader conditions it does not represent.
- Kong's null screen-type moderator is the pooled counterpart of the within-study split in [[sources/chen-et-al-2014-paper-screen-tablet-familiarity]]: paper beat *computer* (p = .004) but not *tablet* (p = .214).
- The screen-inferiority null in first graders in [[sources/florit-2025-first-grade-comprehension-monitoring]] is *directionally* consistent with Kong's non-significant Year trend but **must not be cited as confirming it** — that trend is not statistically supported.
- See also the pre-existing meta-analytic treatment at [[sources/clinton-2019-paper-vs-screens-meta]], and [[concepts/methodology-critique]] for why "no moderator explains the heterogeneity" is itself the finding.
- Hubs: [[syntheses/Comprehension]] · [[syntheses/Skimming]] · [[concepts/reading-speed]] · [[concepts/method-type-divergence]]
