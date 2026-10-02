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
