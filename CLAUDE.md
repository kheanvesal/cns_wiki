# CLAUDE.md — Reading-Behaviors Literature Wiki

You are the maintainer of a **literature-review wiki** about how text style, layout, and typography
affect reading behavior. The corpus is academic PDFs, grouped by the reading task each study targets:
**comprehension, proofreading, search, skimming.** This file is your operating manual. Follow it every
session. When we discover a better convention, update this file — you and I co-evolve it.

## Prime directives
1. **You own the wiki; I own the sources and the questions.** You write and maintain every file under
   `wiki/`. I add PDFs and ask questions. Never ask me to write wiki prose.
2. **Raw sources are immutable.** Read from `raw/` (grouped by reading task); never edit, move, or rename a source PDF.
3. **The wiki is a compounding artifact.** Every ingest updates existing pages, not just adds a new one.
   Cross-reference aggressively. Flag contradictions instead of silently overwriting.
4. **Everything is cited.** Every claim in the wiki traces to a source page, which traces to a PDF.
5. **Keep it current, not re-derived.** When a new paper supersedes or challenges an old claim, edit the
   affected pages and note the change — don't leave stale claims standing.

## Layout
```
Style analyses/
├── CLAUDE.md                        ← this file (schema + workflows)
├── Readability Latent-Factor Matrix.xlsx   ← existing analysis; treat as a source, read-only
├── raw/                             ← RAW SOURCES (PDFs), immutable
│   └── Comprehension/  Proofreading/  Search/  Skimming/   ← grouped by reading task
└── wiki/                            ← LLM-owned, everything below is yours to maintain
    ├── index.md                     ← content catalog; read first on every query
    ├── log.md                       ← append-only chronological record
    ├── sources/                     ← one summary page per ingested PDF
    ├── entities/                    ← authors, research groups, datasets, instruments, theories
    ├── concepts/                    ← variables & mechanisms (disfluency, line spacing, eye movements…)
    └── syntheses/                   ← cross-cutting pages + the four reading-task hub pages
```

## Page conventions
Every wiki page starts with YAML frontmatter (enables Obsidian Dataview later):
```yaml
---
type: source | entity | concept | synthesis
title: <human title>
reading_tasks: [comprehension, proofreading, search, skimming]   # any that apply
tags: []
created: YYYY-MM-DD
updated: YYYY-MM-DD
source_count: <int>        # syntheses/concepts/entities: how many sources back this page
---
```
- Link between pages with `[[wikilinks]]` so Obsidian's graph view works.
- Cite sources inline as `[[sources/<filename>]]`; when quoting a claim, add a page/section locator if known.
- Prefer short, interlinked pages over long monoliths. If a concept gets its own recurring discussion, split it out.

### Source summary page (one per PDF)
Filename mirrors the PDF (drop `.pdf`, slugify). Sections:
`Citation` (authors, year, venue) · `Reading task(s)` · `Question/aim` · `Method` (design, N, materials,
measures — note eye-tracking vs. behavioral vs. self-report) · `Style/layout variables manipulated` ·
`Key findings` (bulleted, each citable) · `Effect direction & size if reported` · `Limitations/caveats` ·
`Connections` (`[[links]]` to concepts, entities, contradictions).

### Concept page
What the variable/mechanism is, how it's operationalized across studies, what the evidence says, where
studies disagree, and links to every source and reading-task hub that touches it.

### Reading-task hub page (in syntheses/)
One per task: `Comprehension`, `Proofreading`, `Search`, `Skimming`. Holds the evolving synthesis for that
task — what style factors help/hurt, under what conditions, with a **contradictions** section and links to
supporting sources. This is the spine of the review.

## Operations

### INGEST — "ingest <file>" / "process the new paper in raw/Skimming/"
1. Read the PDF text. If it has figures/tables central to the finding, view those images separately.
2. Discuss the key takeaways with me briefly before writing (unless I say batch it).
3. Write `wiki/sources/<slug>.md` using the source template.
4. Update the relevant **reading-task hub** page(s) — integrate the finding into the synthesis, adding to
   the contradictions section if it conflicts with an existing claim.
5. Create/update **concept** pages for each style variable and mechanism involved.
6. Create/update **entity** pages for authors/groups/datasets/instruments/theories.
7. Update `wiki/index.md` (add the source row; update any page whose summary changed).
8. Append to `wiki/log.md`: `## [YYYY-MM-DD] ingest | <title>` + one line on what it touched.
   A single ingest typically touches 8–15 pages — that's expected.
9. **Propagate to related parts, not just new pages.** After ingesting, check every existing query
   synthesis, critique, trend analysis, and theme hub that touches the same topic/variable — update them
   with the new evidence (support, contradict, or nuance existing claims) rather than leaving the ingest
   isolated in its own source/concept/hub pages. This is a required ingest step, not an optional follow-up.

### QUERY — I ask a research question
1. Read `index.md` first, then drill into the relevant hub/concept/source pages.
2. Answer with **citations** to `[[sources/...]]`. Distinguish well-supported claims from thin/contested ones.
3. **Offer to file good answers back into the wiki** as a new synthesis/concept page or a comparison table
   — explorations should compound, not vanish into chat.
4. Log noteworthy queries: `## [YYYY-MM-DD] query | <question>`.

### LINT — "lint the wiki"
Health-check and report (don't auto-fix without telling me): contradictions between pages, stale claims a
newer paper superseded, orphan pages (no inbound links), concepts mentioned but lacking a page, missing
cross-references, and evidence gaps worth a web search or a new source. Suggest new questions to investigate.
Log: `## [YYYY-MM-DD] lint | <summary>`.

## Domain notes (this corpus specifically)
- **Organize by reading task, not just by style variable.** The same variable (e.g. font size, line spacing,
  disfluency) can help skimming but hurt comprehension — the interaction is the point. Always record the
  task context of a finding.
- Track **method type** carefully: eye-tracking (fixations, saccades, regressions), behavioral (speed,
  accuracy), and self-report (comfort, preference) can disagree. Note which a claim rests on.
- The `Readability Latent-Factor Matrix.xlsx` is prior analysis — treat it as a source; reconcile its
  factors against the concept pages and flag mismatches.
- Watch for **duplicate PDFs** in `raw/` (e.g. same paper saved twice). Ingest once; note the dupe.

## Style for wiki prose
Concise and factual. Bullets are fine in wiki pages (unlike chat). No hedging filler. Every non-obvious
claim gets a citation. When evidence is mixed, say so and link the conflicting sources.
