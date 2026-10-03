# Index

Content catalog for the reading-behaviors wiki. **Read this first when answering a query**, then drill into the linked pages. Corpus: **105 unique papers** (112 source pages incl. duplicate markers), grouped by reading task, plus the prior `Readability Latent-Factor Matrix.xlsx`.

Status legend: pages exist unless a concept is marked _(stub-needed)_.

**Latest maintenance:** 2026-10-02 — **third pass: completed the `raw/Add more paper/` ingest (30 unique works).** Added 18 source pages (screen-vs-paper comprehension cluster, legibility reviews, search/layout cluster, Porte 2001 proofreading, Lege 2019, Janoušková 2022, Arya 2023). Inventory reconciled by SHA-256: 35 files → **30 unique works** (2 exact baseline duplicates, 2 within-batch duplicates, 1 cross-format duplicate). Propagated into 8 concepts + all 4 hubs + both matrices + [[syntheses/when-measures-disagree]] + [[syntheses/legibility-measurement-standard]]. **One prior claim was corrected**: screen metacognitive miscalibration is no longer supported. Full record in `../CHANGELOG.md`.
**Previous passes 2026-10-02:** second pass ingested [[sources/tarasov-legibility-of-textbooks-2015]] and filed [[syntheses/legibility-measurement-standard]]; first pass ingested 11 papers, 12 concepts, 13 entities.
**Earlier:** [[lint-2026-07-26]] (health-check + backlog + suggested queries).
**Visual reference:** `assets/text-style-specimens.html` (typographic) + `assets/layout-pattern-specimens.html` (page/screen layout, incl. AI-generated layout) + `assets/genai-content-specimens.html` (Gen-AI content layer: simplification, summarization/compression, personalization, prompt strategy) — paired before/after specimens.

## Filed analyses (query syntheses)
- [[syntheses/does-style-improve-comprehension]] — does any style variable improve comprehension (not just speed)? Comparison table + mechanism.
- [[syntheses/evidence-based-default-screen-layout]] — practical safe-default layout with confidence tags + per-task shifts.
- [[syntheses/skimming-vs-scanning-vs-search]] — how layout supports differ across the three fast-reading tasks.
- [[syntheses/when-measures-disagree]] — eye-tracking vs behavioral vs self-report; what to trust for which claim.
- [[syntheses/reading-goal-x-text-style-matrix]] — every style variable × all four goals, with effect direction + confidence.
- [[syntheses/reading-goal-x-controlling-latent-factors]] — latent-factor abstraction: which of the 12 V/L factors *control* each goal (coverage ≠ control).
- [[syntheses/reading-goals-purpose-depth-map]] — purpose × depth map of the four goals, with scope gaps.
- [[syntheses/research-attention-over-time]] — text-style vs layout vs linguistic focus across eras (1963–2025).
- [[syntheses/gen-ai-and-reading]] — **theme hub** for LLM/Gen-AI reading papers; maps to the corpus's own gaps.

## Reading-task hubs (the spine)
_Frame + critique: [[syntheses/reading-goals-purpose-depth-map]] (purpose × depth, with scope gaps) · [[concepts/reading-goals-critique]] (the four are a continuum + tasks; 56% of sources cross-filed)._

- [[syntheses/Comprehension]] — style/layout effects on deep understanding (37 sources).
- [[syntheses/Proofreading]] — style/layout/medium effects on error detection (18 sources).
- [[syntheses/Search]] — layout/structure effects on locating information (18 sources).
- [[syntheses/Skimming]] — style/layout effects on fast selective reading (44 sources).

## Concepts (built)
_Core definition: [[concepts/readability]] — corpus-grounded definition + the study's target-document scope._
_Organizing distinction: [[concepts/text-style-vs-layout]] — glyph-level styling (threshold) · spatial/structural layout (control) · bridge variables (spacing, emphasis, cpl)._

- [[concepts/latent-factor-matrix]] — reconciles the xlsx V1–V6 / L1–L6 scheme; holds the corpus gap-list.
- [[concepts/latent-factor-definitions]] — definition + operationalization + example for each of the 12 factors.
- [[concepts/latent-factor-matrix-critique]] — validity review of that scheme (non-orthogonality, mention-vs-manipulation, gaps).
- [[concepts/text-style-vs-layout]] — the glyph-level (threshold) vs spatial/structural (control) distinction + bridge variables.
- [[concepts/disfluency]] — "desirable difficulty"; **contested; cost more robust than benefit**, and 3 of 4 negatives show cost *without* benefit.
- [[concepts/method-type-divergence]] — behavioral vs eye-tracking vs self-report disagree.
- [[concepts/screen-vs-paper]] — pooled paper advantage (g = −.21) for comprehension, **null for speed**; five named open disputes (age, screen type, depth, genre, calibration).
- [[concepts/line-length]] · [[concepts/characters-per-line]] — four non-commensurate units; proofreading peak at **≈45 cpl** (ω² = .42).
- [[concepts/line-spacing]] — affects proofreading/eye-movements/comfort more than comprehension.
- [[concepts/font-size]] — aids speed/legibility, not comprehension per se.
- [[concepts/font-type-typeface]] · [[concepts/serif-vs-sans]] · [[concepts/expertise-familiarity]] — typeface effects weak once controlled; **familiarity buys preference, not speed or recall**.
- [[concepts/legibility]] — distinct from comprehension.
- [[concepts/reading-purpose-and-goal]] — master moderator (goal × style).
- [[concepts/skimming-strategy]] · [[concepts/satisficing-foraging]] · [[concepts/skim-comprehension-tradeoff]] · [[concepts/main-points-vs-detail]].
- [[concepts/eye-tracking-measures]] · [[concepts/headings-signaling]] · [[concepts/selective-attention]] · [[concepts/signaling]] · [[concepts/text-structure]].
- [[concepts/reading-speed]] · [[concepts/reading-comfort-preference]] · [[concepts/metacognitive-calibration]] · [[concepts/scrolling-vs-paging]] · [[concepts/interaction-style]].
- [[concepts/scanning]] · [[concepts/reading-strategies]] · [[concepts/error-detection]] · [[concepts/desirable-difficulty]] · [[concepts/visual-search]] · [[concepts/web-layout]].

### Added 2026-10-02 (typography/adaptation/dyslexia batch)
- [[concepts/individual-differences-in-readability]] — **within-person variance > between-font variance**; objective calibration works, preference doesn't.
- [[concepts/dyslexia-font-recommendations]] — recommendation vs. individualization; three non-replicating typeface sets.
- [[concepts/italic-and-slant]] — the one converging style finding; group- and measure-dependent.
- [[concepts/preference-versus-effectiveness]] — 41% read worst in their favorite font; familiarity null.
- [[concepts/adaptive-and-personalized-typography]] — context- vs. person-adaptive; domain-dependent, not monotone.
- [[concepts/simulated-readers]] — what simulation can/cannot settle + the human patterns it must reproduce.
- [[concepts/layout-and-line-breaks]] — line breaks as structural cues; content-type-dependent.
- [[concepts/rhythm-rhyme-and-prosody]] — meter/rhythm in silent reading; subvocalization evidence.
- [[concepts/eog-and-physiological-signals]] — EOG vs. video eye tracking; channel asymmetry.
- [[concepts/text-color-and-visual-salience]] — thin; exploratory only.
- [[concepts/multimodal-and-audio-support]] — TTS rate/pitch personalization.
- [[concepts/resource-rationality]] — resource constraints as a modeling stance.
- [[syntheses/legibility-measurement-standard]] — **the protocol** (x-height, leading fractions, ISO 3664:2009, 0.4 m) and what adopting it would change.

_(All referenced concepts now have pages — **96 concept pages, 0 dangling links** as of 2026-10-02. Browse `concepts/` or Obsidian's graph view for the full set.)_

## Entities (built)
- [[entities/alan-chan-cityu-group]] — CityU HK Chinese-proofreading display-factor program.
- [[entities/duggan-payne]] — skim reading as satisficing/foraging.
- [[entities/mary-c-dyson]] — screen line length / cpl.
- [[entities/robert-lorch]] — headings & signaling (SARA).
- [[entities/jean-francois-rouet]] — reading goals / situated comprehension.
- [[entities/miles-tinker]] — foundational print legibility.
- [[entities/ole-lund]] — legibility methodology critique.
- [[entities/sylvia-vitello]] — Cambridge proofreading reviews.
- _stub-needed:_ richard-mayer · paul-van-den-broek · cristina-conati · gary-marchionini · peter-ingwersen · RESOLV-task-model.

### Added 2026-10-02
- [[entities/dyslexianet]] — 4-layer CNN on EOG scalograms; strongest accuracy + fastest training; validation caveat.
- [[entities/seleggo]] — objective performance-based parameter selection (visual) + subjective voice choice.
- [[entities/act-r-and-resource-rational-models]] · [[entities/bayesian-knowledge-tracing]] — the two rival simulated-reader frameworks.
- [[entities/wikibooks]] — material source for the simulated-education ontologies.
- [[entities/erciyes-university]] · [[entities/irccs-e-medea]] · [[entities/university-of-freiburg]] — EOG/dyslexia (TR), personalization (IT), poetry rhythm (DE).
- [[entities/biopac-eog]] · [[entities/eyelink]] — acquisition instruments (note: not interchangeable).
- [[entities/text-to-speech-tts]] — the auditory channel; rate 0.8 / pitch 0.6.
- [[entities/virtual-readability-lab]] · [[entities/readability-matters]] — academic + advocacy poles of the framework paper.
- [[entities/ural-federal-university]] — Tarasov group (printing arts); the only corpus source proposing a formal typographic **measurement standard**.

## Sources — Comprehension
- [[sources/kintsch-1998-comprehension]] — CI model; surface→textbase→situation model (theory anchor).
- [[sources/fpsyg-12-712901]] — meta-analysis; deeper comprehension levels are rarer.
- [[sources/journal-of-educational-psychology-1999]] — reading purpose shapes online inference, not offline scores.
- [[sources/britt-et-al-dp-2022-r1]] — comprehension as situated, goal-driven activity.
- [[sources/ej1079769]] — 12pt faster than 10pt; type/spacing null for comprehension (EFL print).
- [[sources/layout-on-screen]] — Dyson review; cpl is the critical line-length variable.
- [[sources/ej1486502]] — structure-aligned graphic organizers aid comprehension (T-Chart > Venn, d=0.56).
- [[sources/ssrn-5678368]] — Type and Tale; Bayesian nulls; segmentation+indentation helps.
- [[sources/18_63]] — concept-mapping/paragraph structure in EFL.
- [[sources/3320435-3320447]] — reading ability × processing text+visualizations (eye-tracking).
- [[sources/interletter-line-spacing-reading-speed-comprehension]] — spacing null for speed/comprehension, differs in comfort.
- [[sources/binkley-identifier-style-effort-comprehension-2012]] — camelCase vs underscore in code reading.
- [[sources/martin-calpena-web-comprehension-2022]] — web layout elements predict comprehension difficulty (ML).
- [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]] — **pooled screen-vs-paper meta-analysis**: comprehension g = −.21, speed null, no significant moderator. (Added 2026-10-02.)
- [[sources/halamish-elbaz-2020-childrens-comprehension-metacomprehension]] — comprehension ↑ on paper, speed null, metacomprehension null. (Added 2026-10-02.)
- [[sources/chen-et-al-2014-paper-screen-tablet-familiarity]] — paper > computer, not tablet; shallow-only effect; familiarity → deep comprehension. (Added 2026-10-02.)
- [[sources/mangen-walgermo-bronnick-2013-paper-screen-comprehension]] — no genre × medium interaction; both media tested on screen. (Added 2026-10-02.)
- [[sources/florit-2025-first-grade-comprehension-monitoring]] — no medium effect in first graders; tablet > paper on main point. (Added 2026-10-02.)
- [[sources/breso-grancha-2022-digital-print-easy-texts]] — print much slower than digital; **statistically unusable**. (Added 2026-10-02.)
- [[sources/tajuddin-mohamad-paper-versus-screen-university]] — grey literature, **refuted by its own p = .72**. (Added 2026-10-02.)
- [[sources/lege-2019-typography-efl-eye-tracking]] — cueing ↑ recall, aggregate fixations null; **21-cue bundle**. (Added 2026-10-02.)
- [[sources/arya-2023-assessment-methods-readability-legibility]] — PRISMA, 49 studies; method taxonomy; formulas miss digital typography. Cross-cutting. (Added 2026-10-02.)
- [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] — PRISMA; familiarity null for speed and recall. Cross-cutting. (Added 2026-10-02.)
- [[sources/nanavati-bias-2005-optimal-line-length]] — origin of 45–75 cpl; its own bounds inside its own null. Cross-cutting. (Added 2026-10-02.)

### Added 2026-10-02 (typography/adaptation/dyslexia batch, 11 papers)
- [[sources/accelerating-adult-readers-typeface]] — 51% within-person font speed range; preferred ≠ fastest for 82%; familiarity null.
- [[sources/readability-research-an-interdisciplinary-approach]] — multi-disciplinary framework; **no single correct format**; pleasure/preference gap. (Cross-task.)
- [[sources/validating-personalized-visual-auditory-parameters-dyslexia]] — objective per-child parameters beat standard (errors 2.69→1.63); no font >20%; size predicts group, spacing doesn't.
- [[sources/font-type-screen-readability-dyslexia]] — TACCESS 2016; recommended Helvetica/CMU/Arial; **italic penalty absent within dyslexia** (p=.120).
- [[sources/good-fonts-for-dyslexia]] — ASSETS 2013; category claim robust on fixation, **null on reading time** (p=.09); 16/66 pairwise significant.
- [[sources/dyslexianet-eog-deep-learning-dyslexia-detection]] — EOG+CNN; dyslexia≫TDC at p<.0001 on 4 measures; typeface findings exploratory; 99.97% has a leakage caveat.
- [[sources/situfont-adaptive-mobile-typography-svi]] — context-adaptive mobile typography; goodput ↑, workload ↓, **comprehension flat**.
- [[sources/rhythmic-subvocalization-poetry-eye-tracking]] — poem vs prose layout × metrical vs rhyme anomaly interaction; subvocalization evidence.
- [[sources/chinese-typography-eye-tracking-vertical-horizontal]] — vertical > horizontal Chinese posters (recall t=3.569, p=0.001); gender interactions.
- [[sources/simulation-based-optimization-augmented-reading]] — resource-rational simulated reader for design search; **no human data**. (Cross-task.)
- [[sources/adaptive-personalization-educational-readings-simulated]] — simulated learners; CS ↑, chemistry inconclusive, **biology neutral-to-negative**.

### Added 2026-10-02 (second pass)
- [[sources/tarasov-legibility-of-textbooks-2015]] — **century-scale print review.** Serifs/columns evenly split; line length & size "highly dispersed" (≈100–120 mm, ≈12 pt); no typeface effect at all; typography is "more sensitive" to **speed than to comprehension/recall**; diagnoses the field's contradictions as **"absence of a unified approach"** and proposes x-height in mm + leading-as-fraction + ISO 3664:2009 + 0.4 m viewing distance. Cross-cutting (all 4 tasks).

### Added 2026-10-02 (third pass — 18 papers completing the `raw/Add more paper/` ingest)

**Screen vs. paper — the corpus's largest cluster**
- [[sources/kong-seo-zhai-2018-screen-paper-meta-analysis]] — **the pooled estimate.** 17 studies: comprehension g = −.21, 95% CI [−.38, −.03], p = .02 (I² = 73%); **speed null** (g = .48, p = .11, I² = 93%). No moderator reaches significance; screen-type moderator null (b = .22, p = .41).
- [[sources/halamish-elbaz-2020-childrens-comprehension-metacomprehension]] — comprehension d = .41, p = .036; **speed p = .729**; metacomprehension numerically higher on screen but **null** (p = .177) — the source that undercut the miscalibration claim. d = .41 sits at the study's own power floor.
- [[sources/chen-et-al-2014-paper-screen-tablet-familiarity]] — **paper > computer (p = .004) but not tablet (p = .214)**; effect on **shallow** comprehension only (deep: p = .169); **device familiarity** affects *deep* comprehension (F = 5.89, p = .008). Both media took the test on screen.
- [[sources/mangen-walgermo-bronnick-2013-paper-screen-comprehension]] — no genre × medium interaction (p = .707). **Design confound: both groups tested on screen.**
- [[sources/florit-2025-first-grade-comprehension-monitoring]] — N = 58 first graders: **no medium main effect** on any comprehension level (ps > .15); **tablet > paper** on main-point/descriptive. Monitoring tracked comprehension regardless of medium.
- [[sources/breso-grancha-2022-digital-print-easy-texts]] — print **much slower** than digital (r = .91, p < .001). **Impossible significance/CI combinations — direction only, unusable quantitatively.**
- [[sources/tajuddin-mohamad-paper-versus-screen-university]] — grey literature, undated, un-peer-reviewed; claims digital superiority but its own tables give **p = .72**. **Retained as a documented reporting failure, not as evidence.**

**Legibility reviews + two primary studies**
- [[sources/arya-2023-assessment-methods-readability-legibility]] — **PRISMA systematic review, 49 studies** (2015–2023). Three method families (formula/eye-tracking/subjective); formulas **do not capture digital typography**; two cohorts with multi-criteria dyslexia support; no per-study risk-of-bias instrument. Cross-cutting.
- [[sources/ho-sang-petrarca-2025-beyond-typeface-value]] — **PRISMA review** of typeface legibility/beauty. **Familiarity null for recall and speed** despite being preferred; familiarity as a *suggested*, not tested, moderator; slant definitions vary across included studies.
- [[sources/nanavati-bias-2005-optimal-line-length]] — origin of the 45–75 cpl range; leading ≥1/30 line length. **Narrative, not systematic; reports "no significant difference" at 35/55/75/95 cpl — its own bounds sit inside its own null**; CRT-era screen evidence.
- [[sources/lege-2019-typography-efl-eye-tracking]] — typographic cueing → posttest 8.78 vs 5.68 (p < .001), **overall fixations null**, AOI 6 fixated 100% vs 62.07% (p = .0021). **Redirection, not recruitment — but 21 changes bundled, so no individual cue is identified.**
- [[sources/janouskova-2022-font-readability-moses-illusion]] — **failed replication + equivalence testing.** Hard font → accuracy ↓ (p = .039), error detection unchanged (p = .569, negligible). **Disfluency cost without benefit.** Familiarity uncontrolled (Arial vs Allura).

**Search / layout cluster**
- [[sources/li-2009-web-layout-information-forms-locations]] — more fields → fixations ↑ (p = .007), durations ↓ (p < .001), time ↑ (p = .001), **total fixation time unchanged** (p = .085).
- [[sources/lu-et-al-2011-visual-search-information-overload]] — more results → fixations ↑ (p < .001) **and** durations ↑ (p = .014); **mid-range reversals** (4<10, 60>40); **three search clusters differ in speed more than layouts do**; ρ = 0.586 with L2 proficiency.
- [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] — congruity ↑ search (p < .001), ↓ distraction (p < .001); complexity ratings don't predict performance. **⚠️ Impossible likelihood ratios; "replicated interaction" absent from the table.**
- [[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] — Arabic L1 / English graphs: **script familiarity dominates reading direction**; search speed tracks L2 proficiency (ρ = 0.586, p = .01).
- [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]] — **more headers → fewer fixations (b = −0.92)**; correlational, 53 readers × 12 homepages.

**Proofreading**
- [[sources/porte-2001-typographical-error-salience-l2]] — **the corpus's largest proofreading effect: ω² = .42, F = 15.293, p < .001**, line length alone, all else fixed. **Inverted U peaking at ≈45 cpl** (8.80/15), declining at 35 (P = .031). Grand mean **7.67/15 (~51%)** on students' own recurring errors. n = 15/cell, recognition only, salience never measured.

## Sources — Proofreading
- [[sources/chan-2014-line-length-spacing-proofreading]] — line spacing/number drive proofreading + scrolling (Chinese).
- [[sources/chan-2011-optimum-interface-chinese-proofreading]] — optimum interface; comparison vs noncomparison.
- [[sources/chan-ng-display-factors-chinese-proofreading]] — display factors × performance/preference (manuscript).
- [[sources/huang-2017-line-spacing-simplified-chinese]] — eye-tracking line spacing (Simplified Chinese).
- [[sources/2534-handheld-whitespace-reading]] — white space/margins on handheld (Huang & Li 2017).
- [[sources/mouthaan-vitello-2022-text-feature-effects]] — review: text features × proofreading success.
- [[sources/vitello-2022-screen-vs-paper]] — review: proofreading screen vs paper.
- [[sources/hyatt-et-al-2017-proofreading-writing-science]] — pedagogical proofreading guide.
- [[sources/160800-snyder-1978-proofreading-typewriting]] — proofreading instruction dissertation (= `out.pdf`).
- [[sources/kirby-style-strategy-skill-reading]] — reader style/strategy vs skill (theory; terminology note).
- [[sources/7085c1aa-book-review]] — book review (Peggy Smith, *Letter Perfect*); low relevance.
- [[sources/out-scanned-preview]] — **duplicate** of Snyder 1978 (preview scan).
- [[sources/porte-2001-typographical-error-salience-l2]] — line length alone, **ω² = .42**; inverted U peaking ≈45 cpl; ~51% detection ceiling. (Added 2026-10-02.)
- [[sources/janouskova-2022-font-readability-moses-illusion]] — disfluency → accuracy ↓, error detection unchanged (equivalence-tested). (Added 2026-10-02.)

## Sources — Search
- [[sources/fisher-1975-reading-visual-search]] — search vs reading; word shape/boundary (foundational).
- [[sources/tarling-2009-page-layout-visual-search]] — dense faster but sparse preferred.
- [[sources/liang-2013-infographics-layout-search-eyetracking]] — linear≈radial simple; radial>linear for comparison.
- [[sources/zuo-2023-target-layout-graphic-search-eyetracking]] — icon graphic type neutral for familiar icons.
- [[sources/capra-marchionini-structure-interaction-search]] — structure × interaction style × task type.
- [[sources/papaeconomou-relevance-judgments-learning-style]] — relevance criteria × learning style.
- [[sources/choo-detlor-turnbull-1999-web-browsing-searching]] — integrated browsing↔searching model.
- [[sources/thatcher-2006-cognitive-search-strategies]] — 12 cognitive search strategies by task.
- [[sources/pang-2014-online-health-info-seeking]] — online health search approaches.
- [[sources/rouet-2002-search-tasks-comprehension]] — search tasks reshape comprehension (bridge page).
- [[sources/li-2009-web-layout-information-forms-locations]] — field count ↑ → fixations ↑, durations ↓, time ↑; total fixation time flat. (Added 2026-10-02.)
- [[sources/lu-et-al-2011-visual-search-information-overload]] — result count ↑ → both fixation metrics ↑; **three non-negotiable search clusters**; mid-range reversals. (Added 2026-10-02.)
- [[sources/zhang-et-al-2024-layout-order-dashboard-complexity]] — congruity ↑ search, ↓ distraction; complexity ratings don't predict performance; **reporting defects**. (Added 2026-10-02.)
- [[sources/alsaffar-2017-visual-behaviour-searching-preliminary]] — script familiarity dominates direction in cross-script search. (Added 2026-10-02.)
- [[sources/scaltritti-2019-typographic-variables-webpage-eye-movements]] — more headers → fewer fixations (b = −0.92). (Added 2026-10-02.)

## Sources — Gen-AI / LLM (theme: [[syntheses/gen-ai-and-reading]])
- [[sources/kreijkes-2026-llm-notetaking-comprehension]] — RCT: note-taking beats LLM-alone for retention; students prefer LLM.
- [[sources/rolle-2025-gpt-tools-comprehension]] — GPT tools help low performers, harm high performers.
- [[sources/ai-reading-support-bloom-2025]] — prompt behaviour; longitudinal drift to passive reading.
- [[sources/mcnamara-2025-genai-text-personalization]] — LLMs adapt cohesion/level to reader profiles (NLP-validated).
- [[sources/chen-2024-textlap-layout-planning]] — LLM generates layouts from text (adaptive-layout enabler).
- [[sources/decoding-reading-goals-eye-movements-2024]] — decode reading goal (seek vs comprehend) from gaze in real time.
- [[sources/guo-2025-llm-plain-language-summaries]] — LLM summaries rate as good as human but comprehend worse; auto-metrics fail.
- [[sources/hedlin-2025-prompting-readability-chatgpt]] — ChatGPT simplification; prompt strategy matters (Meta best; Standard can worsen).
- [[sources/pascoal-2026-llm-readability-student-comprehension]] — metric-guided simplification improves readability without hurting learning (N=37).

## Sources — Skimming
- [[sources/duggan-payne-2009-text-skimming]] — foraging under time pressure (foundational).
- [[sources/duggan-payne-2011-skim-satisficing]] — skim by satisficing (eye-tracking).
- [[sources/fitzsimmons-2014-skim-reading-web]] — skimming as adaptive web strategy.
- [[sources/soltan-2026-skimming-clinical-info-eyetracking]] — medical students skim clinical text.
- [[sources/dyson-haselgrove-2000-speed-patterns-screen]] — speed–accuracy tradeoff; scrolling patterns.
- [[sources/dyson-haselgrove-2001-speed-linelength-screen]] — ~55 cpl optimal; speed × line length.
- [[sources/hyona-lorch-kaakinen-2002-reading-to-summarize]] — reader strategy typology (eye fixations).
- [[sources/reading-goal-task-eye-fixation-patterns]] — Hyönä & Kaakinen 2011; goal/task → global eye-movement adjustment (OCR-resolved).
- [[sources/lemarie-lorch-perywoodley-2012-headings]] — SARA framework of headings/signaling.
- [[sources/functional-headings-selective-attention]] — functional vs content headings.
- [[sources/beymer-font-size-type-online-reading]] — font size shifts gaze; type weak.
- [[sources/richardson-legibility-serif-sans-serif]] — serif/sans advantage weak (paper & screen).
- [[sources/lund-1999-knowledge-construction-typography]] — legibility methodology critique.
- [[sources/tinker-1963-legibility-of-print]] — classic legibility optima.
- [[sources/bringhurst-elements-of-typographic-style]] — craft norms (image-only; needs OCR).
- [[sources/mayer-fiorella-intro-multimedia-learning]] — CTML; cognitive load / signaling.
- [[sources/clinton-2019-paper-vs-screens-meta]] — meta-analysis paper vs screens.
- [[sources/delgado-salmeron-2021-inattentive-onscreen-reading]] — screen inattention under time pressure.
- [[sources/hemminger-marcial-2012-scrolling-pagination]] — scrolling vs pagination × screen size.
- [[sources/chen-multislate-active-reading]] — multi-slate active reading environment.
- [[sources/diemand-yauman-oppenheimer-fortune-favors-bold]] — disfluency aids retention (**pro**).
- [[sources/dykes-sans-forgetica-readability]] — Sans Forgetica skepticism (**con**).
- [[sources/font-disfluency-online-learning-highschool]] — disfluency slows reading, weak retention (**con**).
- [[sources/abdullah-2018-reading-speed-hybrid-learning]] — hybrid delivery × reading speed/comprehension.
- [[sources/tamsi-skimming-scanning-teaching-narrative]] — skimming vs scanning pedagogy.
- [[sources/todorova-2024-cognitive-processes-reading]] — FL reading-comprehension framework.
- [[sources/edmonds-2009-reading-interventions-synthesis]] — reading interventions for struggling readers.
- [[sources/molich-nielsen-1990-hci-dialogue]] — usability heuristics (peripheral; LINT re-file).
- [[sources/reading-in-a-second-language-book]] — L2 reading; expeditious vs careful (preview).

## Cross-cutting themes to explore (query candidates)
Disfluency debate · preference-vs-performance (method divergence) · serif/sans myth · screen shallowing · cpl optimum · goal × style interactions · Chinese-vs-alphabetic generalization · single-axis vs interaction studies (matrix gap).

## ★ Priority follow-ups queued by the 2026-10-02 ingest
1. **Reproduce Porte (2001).** ω² = .42 is the corpus's largest proofreading effect, from n = 15/cell, one text, one error set, published 2001, never independently replicated. Highest-value single study in this queue.
2. **Isolate one cue.** Lege's 21-bundle is the corpus's best structural comprehension result and it cannot name a device. A factorial cue study (heading size vs. bold vs. colour vs. baseline shift) would resolve [[concepts/signaling]].
3. **Separate arrangement from quantity in search.** Every density/volume cell is confounded; one factorial design at constant element count would fix [[concepts/visual-search]] and the V1/V5 coding problem in [[syntheses/reading-goal-x-controlling-latent-factors]].
4. **Test the calibration claim properly.** It is the one prior wiki claim this ingest had to retract. Needs an adequately powered design.
5. **Screen type as a pre-specified moderator.** Kong's null may be an averaging artifact; Chen et al. show the split within one study.
6. **A comprehension test independent of reading medium.** Mangen's confound has stood since 2013.
7. **Add a non-monotone marker (e.g. `◐ᇰ`) to the latent-factor control code.** Porte's inverted U and Lu's reversals cannot currently be expressed. Flagged in [[syntheses/reading-goal-x-controlling-latent-factors]], **not applied** — needs your decision.
