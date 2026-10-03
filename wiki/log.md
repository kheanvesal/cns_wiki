# Log

Append-only, chronological record of everything done to the wiki. Newest at the bottom.
Each entry starts with `## [YYYY-MM-DD] <op> | <title>` so it's greppable:
`grep "^## \[" log.md | tail -5`

Ops: `ingest`, `query`, `lint`, `setup`.

---

## [2026-07-26] setup | Wiki initialized
Scaffolded `wiki/` (sources, entities, concepts, syntheses), `index.md`, `log.md`, and `CLAUDE.md`.
Scope: literature review of reading-behavior research (academic PDFs).
Raw sources already present, grouped by reading task under `raw/`: `Comprehension/`, `Proofreading/`, `Search/`, `Skimming/`. Plus `Readability Latent-Factor Matrix.xlsx` at root.
No papers ingested yet.

## [2026-07-26] setup | Moved sources into raw/
Relocated the four reading-task folders under `raw/`; updated CLAUDE.md layout and path references.

## [2026-07-26] ingest | Comprehension folder (13 papers)
Wrote 13 source pages + built [[syntheses/Comprehension]]. Theory anchor Kintsch 1998. Key patterns: size aids speed not comprehension; structure-aligned formatting helps; disfluency contested.

## [2026-07-26] ingest | Proofreading folder (12 unique papers)
Wrote 12 source pages + built [[syntheses/Proofreading]]. Dupes: 666539 (×2), 978-3-642==Developing. `out.pdf` unresolved at ingest (later found = Snyder 1978). Chan/CityU Chinese cluster dominates layout evidence. Entity [[entities/alan-chan-cityu-group]], [[entities/sylvia-vitello]].

## [2026-07-26] ingest | Search folder (10 unique papers)
Wrote 10 source pages + built [[syntheses/Search]]. Dupe: 1255175 (×2). Fisher 1975 foundational (search vs reading). Bridge to comprehension via Rouet 2002. Entity [[entities/jean-francois-rouet]].

## [2026-07-26] ingest | Skimming folder (29 unique papers)
Wrote 29 source pages + built [[syntheses/Skimming]]. Collapsed dupes: Duggan&Payne 2009 (×3 files), 2011 (×2), Abdullah hybrid (×2), Individual-differences (×2), Lemarié headings (×3 incl. discours/Understanding). Bringhurst image-only (needs OCR); reading-goal file extraction corrupted. Core: satisficing/foraging; disfluency debate; serif/sans weak; screen shallowing. Entities [[entities/duggan-payne]], [[entities/mary-c-dyson]], [[entities/robert-lorch]], [[entities/miles-tinker]], [[entities/ole-lund]].

## [2026-07-26] ingest | Concept + entity layer, index, matrix reconcile
Built 17 concept pages (incl. [[concepts/latent-factor-matrix]]) and 8 entity pages; rebuilt [[index]]. Reconciled `Readability Latent-Factor Matrix.xlsx`: V1–V6/L1–L6 map cleanly to concept pages; matrix resolved `out.pdf`=Snyder 1978 dupe (→ 63 unique papers) and gave cleaner citations (2534=Huang&Li 2017; Kirby 1988; 7085c1aa=review of Smith *Letter Perfect*). Corpus is visual-heavy, linguistics-light; matrix gap-list captured for LINT. Known backlog: ~60 long-tail concept stubs + 6 entity stubs listed in index.

## [2026-07-26] ingest | OCR fixes (Hyönä & Kaakinen 2011; Bringhurst)
OCR recovered the corrupted reading-goal PDF → Hyönä & Kaakinen (2011), *Studies of Psychology and Behavior* 9(1):24–34; updated source page + index + Skimming hub. OCR confirmed Bringhurst *Elements of Typographic Style* identity.

## [2026-07-26] lint | First health-check → [[lint-2026-07-26]]
0 source orphans; all 64 source links resolve. Created 12 high-frequency concept pages (reading-speed, text-structure, scrolling-vs-paging, reading-comfort-preference, main-points-vs-detail, scanning, reading-strategies, metacognitive-calibration, interaction-style, error-detection, selective-attention, desirable-difficulty) → 29 concept pages total. Documented 4 live contradictions, data-quality flags (Molich&Nielsen + book-review peripheral; out.pdf=Snyder dupe), ~28 remaining concept stubs + 6 entity stubs, matrix-derived evidence gaps, and 4 suggested queries. Report: [[lint-2026-07-26]].

## [2026-07-26] ingest | Backlog cleared — all stubs written
Created the remaining 51 concept pages and 6 entity pages (Mayer, van den Broek, Conati, Marchionini, Ingwersen, RESOLV). Re-lint confirms **0 dangling links** across sources(64)/concepts(80)/entities(14)/syntheses(4) = 165 pages. Wiki graph is now fully connected; remaining work is depth + new sourcing, not coverage.

## [2026-07-26] query | Does any style variable improve comprehension (not just speed)?
Filed answer as [[syntheses/does-style-improve-comprehension]] (comparison table over 12 style variables + mechanism). Verdict: structure/load variables (line length, headings/signaling, structure-aligned organizers, text–graphic integration) help; legibility/aesthetic variables (font size, typeface, spacing, disfluency) mostly don't. Linked from [[syntheses/Comprehension]] and [[index]].

## [2026-07-26] query | What would an evidence-based default screen layout look like?
Filed [[syntheses/evidence-based-default-screen-layout]] — recommendations table (line length, size, typeface, spacing, case, headings, whitespace, text+graphics, navigation, attention) with confidence tags + per-task shifts (comprehension/skimming/search/proofreading) + generalization caveats. Linked from [[index]].

## [2026-07-26] query | Skimming vs scanning vs search — how do layout supports differ?
Filed [[syntheses/skimming-vs-scanning-vs-search]] (cross-hub). Organizing distinction: is the target known + specific vs. gist. Skimming→importance signposting; scanning→target discriminability + predictable placement + density; search→navigable structure + mode support. Common denominator = clear structural signposting. Linked from [[syntheses/Skimming]], [[syntheses/Search]], [[index]].

## [2026-07-26] query | Where do eye-tracking and behavioral outcomes disagree?
Filed [[syntheses/when-measures-disagree]] (deepens [[concepts/method-type-divergence]]). Catalogued 6 disagreements + 1 convergence; taxonomy (process≠product, preference≠performance, feeling≠knowing); decision rule for what to trust per claim. Linked from the concept page and [[index]]. This closes the 4 lint-suggested queries.

## [2026-07-26] query | What text styles are used for each reading goal?
Filed [[syntheses/reading-goal-x-text-style-matrix]] — full variable × goal grid (visual, structural, medium) with ↑/↓/=/~ and confidence tags. Patterns: comprehension←structure; proofreading←spacing/geometry (Chinese-only); search/skimming←salience/density/navigation. Linked from [[index]] and all four hubs.

## [2026-07-26] query | Transform: Reading-Goal × controlling latent factors
Filed [[syntheses/reading-goal-x-controlling-latent-factors]] — abstracted the style-variable matrix up to the 12 V/L latent factors; computed per-folder factor engagement from the xlsx and combined with source effect-directions to rate each factor Controlling/Modulating/Weak/Untested per goal. Control signatures: Comprehension→L3+L5+V5; Proofreading→V1; Search→V6+V5+V3+V1; Skimming→V3+V4+V5 (L4 compression = untested driver). Central finding: **coverage≠control** — V2 glyph legibility is over-studied but rarely controlling (threshold, not ceiling). Cross-linked with [[syntheses/reading-goal-x-text-style-matrix]] and [[concepts/latent-factor-matrix]].

## [2026-07-26] lint/query | Validity review of the latent-factor scheme
Filed [[concepts/latent-factor-matrix-critique]]. Computed pairwise correlations of the 12 dims across 63 papers: V5↔L5 +0.66 (double-counted structure), L-block collapses (L1-L2 +0.64, L2-L3 +0.60), V3↔V5 +0.63, V4↔V6 +0.34; 20/63 papers have no High-coded dim. Findings: "latent factors" is a misnomer (rational taxonomy, not factor-analytic); non-orthogonal axes; H/M/L conflates manipulation with mention; construct drift (screen/paper miscoded as V4-temporal; camelCase as L1; reader-ability as V3); missing Medium/Color/Interactivity axes. Propagated mention-vs-manipulation caveat to [[concepts/latent-factor-matrix]] and [[syntheses/reading-goal-x-controlling-latent-factors]].

## [2026-07-26] asset | Text-style specimen sheet
Generated a before/after visual specimen of 11 visually-demonstrable text-style variables (font size, serif/sans, disfluency, line/letter spacing, cpl, case, emphasis, density, headings, segmentation), each tagged with its wiki verdict. Saved self-contained (light/dark) at `assets/text-style-specimens.html`; linked from [[index]] and [[syntheses/reading-goal-x-text-style-matrix]]. Non-static variables (medium, pacing, scroll/paginate, navigation) noted as not shown.

## [2026-07-26] asset | Layout-pattern specimen sheet
Generated schematic wireframe before/afters of 8 page/screen layout patterns (columns/measure, headings, margins, density, text–graphic integration, linear vs radial topology, scroll vs pagination, flat vs tiered navigation), each tagged with its wiki verdict. Saved self-contained (light/dark) at `assets/layout-pattern-specimens.html`; paired with the text-style sheet and linked from [[index]] and [[syntheses/reading-goal-x-text-style-matrix]].

## [2026-07-26] update | Revised controlling-latent matrix per critique
Acted on [[concepts/latent-factor-matrix-critique]]: recomputed engagement on manipulated-IV-only (High-coded studies; mentions excluded) — shrinks V3/V4/V6 situational shades and confirms L4 = 0 manipulations; V2 stays most-manipulated yet ○ (sharpens coverage≠control). Merged V5⊕L5 into one text-structure row (r=+0.66); added L-block non-independence note. Updated signatures, central finding, caveats in [[syntheses/reading-goal-x-controlling-latent-factors]]. Control ratings (●◐○) unchanged (derive from effect directions, not coding).

## [2026-07-26] concept | Text-style vs layout distinction
Filed [[concepts/text-style-vs-layout]] — analytical (not filing) split: glyph-level text style = threshold; spatial/structural layout = control; bridge variables (line/letter spacing, emphasis, cpl) span both and host the interaction gaps. Kept reading-task hubs as primary organization; no source re-filing. Framing links added to both matrices and the concept index.

## [2026-07-26] concept | Latent-factor definitions glossary
Filed [[concepts/latent-factor-definitions]] — definition + operationalization + corpus/illustrative example for all 12 factors (V1–V6, L1–L6), grouped by text-style/layout, with critique-aware notes (V4≠medium, L1 orthographic caveat, L2/L4 gaps, V5⊕L5 merge). Linked from the control matrix, [[concepts/latent-factor-matrix]], and [[index]].

## [2026-07-26] lint/query | Review of the four reading goals
Analysed source `reading_tasks`: 56% of 64 sources cross-file >1 goal; comprehension+skimming=25 (a continuum), search+skimming=11. Findings: the four mix reading *modes* (comprehension/skimming, a depth continuum) with *tasks* (proofreading/search); Search overloaded (visual-search + information-seeking); incomplete vs the corpus's cited Rouet/Choo taxonomy (missing learning, pleasure, scanning, glanceable). Filed [[concepts/reading-goals-critique]] + [[syntheses/reading-goals-purpose-depth-map]] (purpose × depth, GAP cells = pleasure, careful-evaluative, learning). Kept four hubs as spine; linked from [[index]] and [[concepts/reading-purpose-and-goal]].

## [2026-07-26] query | Research-attention trend over time
Crossed publication year (60/63 papers, 1963–2025) with the text-style/layout/linguistic buckets; bucketed into 4 eras, normalized per paper. Trend: text style flat+low throughout (settled early); layout dominant, peaks 2005–2014 (screen/HCI wave); linguistic bimodal (1990s comprehension-theory peak → HCI-decade collapse → post-2015 recovery). Attention tracks technology waves more than what controls outcomes. Filed [[syntheses/research-attention-over-time]] (with chart); linked from [[index]] and [[concepts/latent-factor-matrix]]. Caveat: weighted-engagement = attention (inflation per critique); coarse buckets.

## [2026-07-26] ingest | Gen-AI / LLM papers (new theme)
Web-searched for missing + Gen-AI reading papers (corpus had zero). Created `raw/GenAI-LLM/` + manifest; ingested 6 open-access papers as source pages: Kreijkes 2026 (LLM vs note-taking RCT — Vitello co-author), Rolle 2025 (GPT tools × ability), AI-reading-support 2025 (Bloom prompts / passive drift), McNamara 2025 (GenAI text personalization), Chen 2024 (TextLap layout generation), Decoding Reading Goals 2024 (gaze→goal). Filed theme hub [[syntheses/gen-ai-and-reading]] mapping them to the corpus's own gaps (L4 compression, adaptive layout, linguistic axes, reading-goals). Cross-findings: shallowing redux, preference≠performance, ability-moderated effects. Updated Comprehension + Skimming hubs, index (new Gen-AI source section), latent-factor-matrix gap notes, purpose-depth map. 2 candidates blocked (PMC recaptcha, ScienceDirect paywall) + 5 more listed in manifest. PDFs to be added to raw/GenAI-LLM/ manually.

## [2026-07-26] update | Propagated Gen-AI sources into all analyses
Wove the 6 new sources into every affected analysis: [[syntheses/reading-goal-x-controlling-latent-factors]] (L4 moving untested→emerging), [[syntheses/when-measures-disagree]] (+ LLM preference≠retention row), [[syntheses/does-style-improve-comprehension]] (content as new lever; over-easing hurts), [[syntheses/evidence-based-default-screen-layout]] (adaptive now buildable but unproven; AI-summary caution), [[concepts/reading-goals-critique]] (goals decodable = regimes), [[syntheses/research-attention-over-time]] (Gen-AI wave addendum), [[syntheses/skimming-vs-scanning-vs-search]] (AI summary = machine skimming), [[syntheses/reading-goal-x-text-style-matrix]] + [[concepts/latent-factor-definitions]] (L4 now manipulable), [[concepts/method-type-divergence]] + [[concepts/text-style-vs-layout]] (added content as a third layer: content→layout→text-style).

## [2026-07-26] query | Define readability + target documents
Upgraded [[concepts/readability]] from stub to the corpus's core definition: readability = degree to which a *given reader*, *given goal*, *given medium* can efficiently extract needed info from a document — relational (not intrinsic), multi-level (legibility→situation model), measure-dependent. Distinguished from legibility / formulas / comprehension; ranked determinants (content > layout > text style). Added a **target-documents scope** section: mostly educated-adult/student, digital/print expository-instructional text, English/alphabetic + Chinese cluster; out-of-scope = pleasure/literary, children, non-Latin scripts, professional genres. Linked from [[index]] as core definition.

## [2026-07-27] asset | Gen-AI content-layer specimen sheet + layout catch-up
Reviewed the two existing specimen sheets against the current KB and found them stale: both were built before the Gen-AI ingest, so the corpus's third "content" layer ([[concepts/text-style-vs-layout]]) had no visual. Added `assets/genai-content-specimens.html` — 4 worked before/after passages: simplification (helps/neutral, [[sources/pascoal-2026-llm-readability-student-comprehension]]), summarization/compression (can hurt, [[sources/guo-2025-llm-plain-language-summaries]], [[sources/rolle-2025-gpt-tools-comprehension]], [[sources/kreijkes-2026-llm-notetaking-comprehension]]), personalization ([[sources/mcnamara-2025-genai-text-personalization]]), prompt strategy ([[sources/hedlin-2025-prompting-readability-chatgpt]]). Also added an "adaptive/AI-generated layout" wireframe panel to `layout-pattern-specimens.html` ([[sources/chen-2024-textlap-layout-planning]], tagged buildable/unproven). Re-linked all three sheets from [[index]], [[syntheses/reading-goal-x-text-style-matrix]], [[concepts/text-style-vs-layout]], and [[syntheses/gen-ai-and-reading]].

## [2026-07-26] ingest | Gen-AI batch 2 (3 new papers from raw/GenAI-LLM/)
User added PDFs. Ingested 3 unique (4 files; Pascoal stored twice): Guo et al. 2025 (LLM plain-language summaries — rate as good as human but comprehend worse; auto-metrics fail), Hedlin et al. 2025 (ChatGPT simplification prompting — Meta best, Standard can worsen), Pascoal et al. 2026 (metric-guided simplification improves readability without hurting learning, N=37 reader study). Key new distinction folded into [[syntheses/gen-ai-and-reading]]: **simplification (rewrite, content preserved) helps/neutral vs summarization/compression (content removed) can hurt** — resolves an ambiguity in the batch-1 findings. Updated hub (source_count 6→9, sources regrouped), index, manifest. Reinforces preference≠performance + metric≠behavior.

## [2026-10-02] ingest | Typography, adaptation/personalization, dyslexia accessibility, rhythm batch (11 papers)
Ingested 11 papers and propagated across the wiki (36 pages written/edited).
**Sources (11):** `situfont-adaptive-mobile-typography-svi` (CHI '26) · `chinese-typography-eye-tracking-vertical-horizontal` (Sci Rep 2024) · `accelerating-adult-readers-typeface` (CHI '20 EA) · `readability-research-an-interdisciplinary-approach` (arXiv 2021) · `simulation-based-optimization-augmented-reading` (arXiv 2026) · `adaptive-personalization-educational-readings-simulated` (arXiv 2026) · `font-type-screen-readability-dyslexia` (TACCESS 2016) · `good-fonts-for-dyslexia` (ASSETS 2013) · `validating-personalized-visual-auditory-parameters-dyslexia` (MTI 2024) · `dyslexianet-eog-deep-learning-dyslexia-detection` (JEMR 2025) · `rhythmic-subvocalization-poetry-eye-tracking` (JEMR 2021).
**Concepts (12 new):** `individual-differences-in-readability` · `dyslexia-font-recommendations` · `italic-and-slant` · `preference-versus-effectiveness` · `adaptive-and-personalized-typography` · `simulated-readers` · `layout-and-line-breaks` · `rhythm-rhyme-and-prosody` · `eog-and-physiological-signals` · `text-color-and-visual-salience` · `multimodal-and-audio-support` · `resource-rationality`.
**Entities (13 new):** `dyslexianet` · `seleggo` · `act-r-and-resource-rational-models` · `bayesian-knowledge-tracing` · `wikibooks` · `erciyes-university` · `irccs-e-medea` · `university-of-freiburg` · `biopac-eog` · `eyelink` · `text-to-speech-tts` · `virtual-readability-lab` · `readability-matters`.
**Hubs updated:** `syntheses/Comprehension` (13→24 sources; new moderator, null, and contradiction sections) · `syntheses/Skimming` (29→33 sources; adaptive-pruning and reflow-cost tensions). `index.md` rebuilt with a dated batch section.
**Contradictions logged:**
1. *Dyslexia font recommendation vs. individualization* — Rello & Baeza-Yates name Helvetica/CMU/Arial; Lorusso et al. find no font selected by >20% of 49 atypical readers and explicitly decline to rank. Three non-replicating typeface sets across English/Turkish/Italian.
2. *Adaptation is not uniformly beneficial* — Woo et al.: CS ↑, chemistry inconclusive, biology neutral-to-negative (n=3 domains, simulated). SituFont improves goodput but leaves comprehension flat, and its own limitations note unintended activation turns adaptation into an interruption.
3. *Speed vs. fixation duration* — typeface effects robust on fixation, marginal/absent on reading time (only 16/66 pairwise significant in ASSETS 2013; italic penalty absent within dyslexia in TACCESS 2016). Recorded as a general flag on "more legible" claims.
4. *Preference ≠ effectiveness* — 41% scored lowest comprehension in their preferred font; 80% wrongly believed otherwise.
**Notable caveats captured:** DyslexiaNet's 99.97% accuracy is segment-level with likely participant leakage (3,000 windows from 36 children, non-grouped 5-fold CV) — must not be read as diagnostic accuracy. Lorusso's speed medians are identical (2.85 vs 2.85) despite a significant signed-rank result. All personalization evidence uses one-tailed tests.
**New gaps flagged for future searches:** isolate slant/serifness/x-height factorially; line-length × line-breaks in prose; color as an isolated factor (incl. WCAG risk); TTS effects separable from visual decoding; simulator-vs-human fidelity; predictor of an individual's optimal format.

## [2026-10-02] ingest | Tarasov et al. 2015 — Legibility of textbooks (catch-up ingest + reframing pass)
Second pass on the same day. Found `raw/Add more paper/tarasov2015.pdf` **un-ingested** — it is one of the four named comparison papers for this batch, so its absence was a real gap, not an oversight of priority.
**Source:** `tarasov-legibility-of-textbooks-2015` — Tarasov, Sergeeva & Filimonova (2015), *Procedia - Social and Behavioral Sciences* 174, 1300-1308, doi:10.1016/j.sbspro.2015.01.751. Narrative review of ~a century of print legibility work; cross-cutting (all four tasks).
**Why it matters more than a normal review:** it *diagnoses* the contradictions this wiki has been logging rather than adding one. Serifs "almost equal numbers of studies showed advantages and disadvantages"; columns likewise; line length and font size "highly dispersed" (mean ~100-120 mm, ~12 pt "without specification of typeface"); **no typeface differed on speed, comprehension, or recall** so "no special type font is suggested to use in print and everyone is free to choose it themselves." Root cause named: **"an absence of a unified approach… the principal reason of such contradictory results obtained"** — uncontrolled lighting, uncontrolled paper substrate, incompatible measuring units.
**New:** `entities/ural-federal-university` · `syntheses/legibility-measurement-standard` (the protocol: x-height in mm as the only typeface measure, leading as a fraction of x-height, ISO 3664:2009 lighting, 0.4 m viewing distance, full stimulus spec).
**Propagated into 9 concepts:** `methodology-critique` (promoted to the corpus's root-cause diagnosis; source_count 1→2) · `font-size` · `line-length` · `line-spacing` (leading→return-sweep mechanism) · `columns` · `serif-vs-sans` · `expertise-familiarity` · `method-type-divergence` (typography moves speed more than understanding) · `dyslexia-font-recommendations` (+ `italic-and-slant`, `preference-versus-effectiveness`; counts corrected 5→7, 6→7).
**Propagated into all 4 hubs:** Comprehension 24→25, Proofreading 12→13, Search 10→11, Skimming 33→34 sources.
**New tensions registered:**
1. *The typeface question may be unanswerable, not open.* Under Tarasov's diagnosis the serif/typeface conflicts are uninterpretable without a shared measurement standard — so they are **not yet properly tested** rather than awaiting one more study.
2. *Cross-script non-transfer is predicted, not anomalous.* "Guidelines cannot be simply applied to non-English script" — which predicts in advance that the English/Turkish/Italian dyslexia sets would disagree. They do.
3. *Familiarity: asserted by the review, refuted by the only direct test.* Tarasov makes familiarity the load-bearing residual of the field; Wallace et al. tested it and found nothing (`r=0.042` speed, `r=0.033` comprehension).
4. *Italic has never been meta-analyzed.* Tarasov has **no italic/slant coverage at all**, so the corpus's most convergent style finding has never been synthesesed by a source that counts studies.
**Housekeeping:** corrected a stale `source_count` (5→7) and a lowercase `[[syntheses/Comprehension]]` link (case-inconsistent with the capitalised hub slugs). Verified 0 U+FFFD in all 226 pages — apparent mojibake was a PowerShell console codepage artifact, not file damage. Re-ran link check: **226 pages, 0 dangling wikilinks.**
**Backlog still open:** ~30 further PDFs in `raw/Add more paper/` remain un-ingested (see index). Dupe flagged: `2604.16744v2 - Copy.pdf` duplicates `2604.16744v2.pdf`.

## [2026-10-02] ingest | `raw/Add more paper/` completion pass — 18 sources, 30 unique works total
Third pass. **Closes the backlog** recorded above: every unique work in `raw/Add more paper/` is now represented in the wiki.

**Inventory reconciliation (SHA-256, script output saved to `raw_inventory.json` at repo root):** 112 PDFs total = 77 baseline + 35 under `raw/Add more paper/`. The 35 files resolve to **33 hash groups**, of which **2 are exact baseline duplicates** and **2 are within-batch duplicates**, and **1 group is a cross-format duplicate** (same work, two renderings) → **30 unique new works**.
Duplicates recorded: `Comprehension/soleimani2012.pdf` = baseline `raw/Comprehension/EJ1079769.pdf`; `Skimming/12909_2025_Article_8412.pdf` = baseline same-hash file; `General/2604.16744v2.pdf` = `General/2604.16744v2 - Copy.pdf`; `General/janouskova2022.pdf` = `raw/Proofreading/janouskova2022 (1).pdf`; `General/41598_2024_Article_64964.pdf` and `General/vision-04-00018-v2.pdf` are the same Chen, Yang & Wang (2024) paper (DOI 10.1038/s41598-024-64964-y) — the `41598` rendering kept as canonical.
Two image-only PDFs (Beyond (Type)Face Value; Optimal Line Length) were OCR'd with `rapidocr-onnxruntime` after text extraction yielded nothing.

**Sources added (18):**
Screen/paper cluster — `kong-seo-zhai-2018-screen-paper-meta-analysis` · `halamish-elbaz-2020-childrens-comprehension-metacomprehension` · `chen-et-al-2014-paper-screen-tablet-familiarity` · `mangen-walgermo-bronnick-2013-paper-screen-comprehension` · `florit-2025-first-grade-comprehension-monitoring` · `breso-grancha-2022-digital-print-easy-texts` · `tajuddin-mohamad-paper-versus-screen-university`.
Legibility reviews + primaries — `arya-2023-assessment-methods-readability-legibility` · `ho-sang-petrarca-2025-beyond-typeface-value` · `nanavati-bias-2005-optimal-line-length` · `lege-2019-typography-efl-eye-tracking` · `janouskova-2022-font-readability-moses-illusion`.
Search/layout — `li-2009-web-layout-information-forms-locations` · `lu-et-al-2011-visual-search-information-overload` · `zhang-et-al-2024-layout-order-dashboard-complexity` · `alsaffar-2017-visual-behaviour-searching-preliminary` · `scaltritti-2019-typographic-variables-webpage-eye-movements`.
Proofreading — `porte-2001-typographical-error-salience-l2`.

**Concepts updated (8):** `screen-vs-paper` (6→12 sources; rewritten — pooled estimate plus five named open disputes) · `line-length` (6→9; four-unit comparison table) · `visual-search` (3→9; rewritten) · `error-detection` (4→6; rewritten) · `signaling` (2→3; rewritten) · `disfluency` (5→6; added the cost-without-benefit dissociation) · `expertise-familiarity` (4→7) · `method-type-divergence` (10→20).
**Scope boundaries added to 4 pre-existing pages** (`italic-and-slant`, `preference-versus-effectiveness`, `layout-and-line-breaks`, `individual-differences-in-readability`) to stop overlap with the new pages rather than deleting or merging content.

**Syntheses updated (6):** `Comprehension` (25→37 sources) · `Proofreading` (13→18) · `Search` (11→18) · `Skimming` (34→44) · `reading-goal-x-text-style-matrix` (30→41; new "cells changed" table) · `reading-goal-x-controlling-latent-factors` (30→41) · `when-measures-disagree` (10→21) · `legibility-measurement-standard` (2→7).
**The 12 canonical latent factors and their definitions were NOT changed.** Only control ratings (◐→● for V1/proofreading, V3 engagement ░→▒ for comprehension) and caveats were updated.

**Correction to a pre-existing claim (flagged, not silently overwritten):** the wiki asserted that screen reading produces **metacognitive miscalibration** (from `clinton-2019-paper-vs-screens-meta`). Halamish & Elbaz found metacomprehension **numerically higher on screen but null** (p = .177, d = .21) and Florit et al. found first graders monitored comprehension accurately across media. **No study in this corpus now shows metacognitive confidence diverging from performance by medium.** The claim is retracted as a finding and re-filed as an untested mechanism in `screen-vs-paper`, `when-measures-disagree`, and both the Comprehension and Skimming hubs.

**Contradictions and caveats logged:**
1. *Pooled speed result is null but self-disqualified.* Kong's speed moderators are all excluded in the paper's own Table 5b (df < 4, "should not be trusted"), while Bresó-Grancha reports print **much slower** than digital (r = .91) with impossible significance/CI combinations. "Digital is faster" is **unestablished**, not settled.
2. *The screen advantage may be shallow-only.* Chen et al.: effect on shallow comprehension, null on deep (F = 1.81, p = .169); device familiarity affected *deep* comprehension instead (F = 5.89, p = .008).
3. *Screen type splits within a single study.* Paper > computer (p = .004) but not tablet (p = .214) — which is what produces the pooled screen-type null (b = .22, p = .41).
4. *Age.* Florit et al.: **no medium effect at all** in first graders, with tablet > paper on main-point questions. Kong's Year trend (b = .26, **p = .09**) is non-significant and must never be cited as evidence of change.
5. *Disfluency cost without benefit.* Janoušková: accuracy fell (p = .039) while the reflective outcome did not move (p = .569, **negligible by equivalence testing** — the only such use in this corpus). Three of four disfluency negatives now show cost without benefit.
6. *Familiarity is refuted as the typeface explanation.* Ho Sang & Petrarca: familiar faces preferred, **no speed advantage, no recall benefit**. Directly contradicts Tarasov's residual claim.
7. *Redirection, not recruitment.* Lege: large recall effect (p < .001) with **unchanged aggregate fixation**, significant only at AOI level (100% vs 62.07%, p = .0021). **But 21 cues were bundled**, so no individual cue is identified.
8. *Quantity is never separated from arrangement.* Li, Lu and Zhang all vary element count; none manipulates arrangement at constant count. Now the corpus's most-cited methodological gap, and it blocks V1/V5 attribution in the latent-factor coding.
9. *Individual clusters outrank layouts.* Lu et al.'s three search profiles differ in reading speed **more than the layouts do** ("non-negotiable").
10. *Documented reporting failures retained as such:* `tajuddin-...` (grey lit, own p = .72), `breso-grancha-...` (impossible CI/significance combos), `zhang-et-al-...` (impossible likelihood ratios; "replicated interaction" absent from the table).
11. *Line-length units proliferated.* Now four quantities for one construct, two in the same unit (cpl) that still cannot be reconciled because Porte gives no typeface/x-height specification — **the units problem is not solved by agreeing on characters.**
12. *Coding-schema limitation flagged, not applied.* The ◐/●/○ latent-factor code cannot express "controlling with an interior optimum" (Porte's inverted U, Lu's reversals). Recommended a non-monotone marker; **left unchanged pending decision**.

**Housekeeping:** stripped UTF-8 BOMs from the 4 task hubs; normalized 43 lowercase task-hub wikilinks and repaired 11 over-broad prefix replacements; strict case-sensitive link check now **244 pages, 2,808 links, 0 broken, 0 orphans, 0 BOM**.

**Open lint finding (pre-existing, not auto-fixed):** 81 baseline pages deviate from the current frontmatter schema — ~75 source pages lack `source_count`, and 5 concept/synthesis pages carry `source_count: 0`. All are baseline content; left untouched rather than mass-rewritten. Needs a decision.

**Still open:** replicate Porte (2001) (ω² = .42, never replicated); isolate a single cue from Lege's 21-bundle; factorially separate arrangement from quantity in search; power the calibration test properly; add a non-monotone marker to the control code; decide the fate of `raw_inventory.json`; resolve the 81 baseline frontmatter deviations.
