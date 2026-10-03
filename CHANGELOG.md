# Changelog — Wiki Maintenance Record

Every modification to `wiki/` is recorded here, newest first. Narrative detail (contradictions, caveats, propagation paths) lives in `wiki/log.md`; this file is the scannable index of *what changed and why*.

**Scope:** the wiki is additive. Existing claims are corrected only when new evidence directly contradicts them, and the correction is always flagged on the page itself as well as here. The canonical 12 latent factors (V1–V6, L1–L6) and their definitions are treated as fixed unless the maintainer explicitly approves a change.

---

## 2026-10-02 — `raw/Add more paper/` completion pass

**Outcome:** all **30 unique works** in `raw/Add more paper/` are now represented. 112 PDFs total (77 baseline + 35 new); the 35 resolve to 30 unique works after SHA-256 reconciliation.

### Added — 18 source pages
| Cluster | Source pages |
|---|---|
| Screen vs. paper | `kong-seo-zhai-2018-screen-paper-meta-analysis`, `halamish-elbaz-2020-childrens-comprehension-metacomprehension`, `chen-et-al-2014-paper-screen-tablet-familiarity`, `mangen-walgermo-bronnick-2013-paper-screen-comprehension`, `florit-2025-first-grade-comprehension-monitoring`, `breso-grancha-2022-digital-print-easy-texts`, `tajuddin-mohamad-paper-versus-screen-university` |
| Legibility reviews + primaries | `arya-2023-assessment-methods-readability-legibility`, `ho-sang-petrarca-2025-beyond-typeface-value`, `nanavati-bias-2005-optimal-line-length`, `lege-2019-typography-efl-eye-tracking`, `janouskova-2022-font-readability-moses-illusion` |
| Search / layout | `li-2009-web-layout-information-forms-locations`, `lu-et-al-2011-visual-search-information-overload`, `zhang-et-al-2024-layout-order-dashboard-complexity`, `alsaffar-2017-visual-behaviour-searching-preliminary`, `scaltritti-2019-typographic-variables-webpage-eye-movements` |
| Proofreading | `porte-2001-typographical-error-salience-l2` |

### Modified — concepts (8)
| Page | Change |
|---|---|
| `concepts/screen-vs-paper.md` | **Rewritten.** 6→12 sources. Pooled estimate + five named open disputes (age, screen type, depth, genre, calibration) |
| `concepts/visual-search.md` | **Rewritten.** 3→9. Volume cost, non-monotonicity, individual clusters, congruity, script confound |
| `concepts/error-detection.md` | **Rewritten.** 4→6. Porte's ω²=.42, the ~51% ceiling, Janoušková's dissociation, "salience never measured" |
| `concepts/signaling.md` | **Rewritten.** 2→3. Lege's redirection result + the 21-cue bundle caveat |
| `concepts/line-length.md` | 6→9. Four-unit comparison table; ≈45 cpl proofreading peak |
| `concepts/disfluency.md` | 5→6. Cost-without-benefit dissociation; legibility/familiarity confound named |
| `concepts/expertise-familiarity.md` | 4→7. Ho Sang & Petrarca refutes familiarity as the typeface explanation |
| `concepts/method-type-divergence.md` | 10→20. Six new instances + Arya's independent three-family taxonomy |

**Also:** scope boundaries added to 4 pre-existing pages (`italic-and-slant`, `preference-versus-effectiveness`, `layout-and-line-breaks`, `individual-differences-in-readability`) to stop overlap with new pages instead of deleting content.

### Modified — syntheses (8)
| Page | Change |
|---|---|
| `syntheses/Comprehension.md` | 25→37 sources. Pooled medium estimate; Lege hierarchy result; 6 new contradictions |
| `syntheses/Proofreading.md` | 13→18. Porte promoted to hub anchor; Janoušková counter-instance; bundled-cue caveat |
| `syntheses/Search.md` | 11→18. Information-volume section; "less is more" refuted 4 ways |
| `syntheses/Skimming.md` | 34→44. Medium section qualified; disfluency prediction sharpened |
| `syntheses/reading-goal-x-text-style-matrix.md` | 30→41. New typeface-familiarity row; "cells changed" table |
| `syntheses/reading-goal-x-controlling-latent-factors.md` | 30→41. **V1/proofreading ◐→●**, V3 engagement ░→▒. Factor set unchanged |
| `syntheses/when-measures-disagree.md` | 10→21. 6 new rows; **one row corrected**; fourth disagreement type added |
| `syntheses/legibility-measurement-standard.md` | 2→7. Independent corroboration; fourth unit problem; remedy-insufficiency caveat |

### Corrected — one pre-existing claim
> **Retracted:** "screen reading produces metacognitive miscalibration."
> **Was asserted by** `clinton-2019-paper-vs-screens-meta` and repeated on `screen-vs-paper`, `when-measures-disagree`, and the Comprehension and Skimming hubs.
> **Contradicted by** `halamish-elbaz-2020-childrens-comprehension-metacomprehension` (metacomprehension numerically higher on screen, **null**: p = .177, d = .21) and `florit-2025-first-grade-comprehension-monitoring` (monitoring tracked comprehension regardless of medium).
> **Now:** re-filed as an *untested mechanism* on all four affected pages, with the retraction stated inline rather than silently deleted.

### Housekeeping
- Stripped UTF-8 BOMs from the 4 task hubs.
- Normalized 43 lowercase task-hub wikilinks; repaired 11 over-broad prefix replacements.
- Strict case-sensitive validation: **244 pages, 2,808 links, 0 broken, 0 orphans, 0 BOM.**
- OCR'd two image-only PDFs (`rapidocr-onnxruntime`): Beyond (Type)Face Value; Optimal Line Length.

### Generated, not yet placed
- `raw_inventory.json` (repo root) — SHA-256 manifest of all 112 PDFs. **Retention unresolved**; not part of the `wiki/` schema.

### Open — needs maintainer decision
1. **81 pre-existing baseline pages** deviate from the current frontmatter schema (~75 source pages lack `source_count`; 5 concept/synthesis pages carry `source_count: 0`). Left untouched rather than mass-rewritten.
2. **Non-monotone control marker** (`◐ᇰ`) for the latent-factor code, needed for Porte's inverted U and Lu's reversals. Recommended, **not applied**.
3. Fate of `raw_inventory.json`.

---

## 2026-10-02 — Tarasov et al. 2015 catch-up ingest

- **Added:** `sources/tarasov-legibility-of-textbooks-2015`, `entities/ural-federal-university`, `syntheses/legibility-measurement-standard`.
- **Modified:** 9 concepts (incl. `methodology-critique` promoted to root-cause diagnosis), all 4 hubs.
- **Why it mattered:** diagnosed the field's contradictions as a **measurement failure** ("an absence of a unified approach… the principal reason of such contradictory results obtained") and proposed a concrete protocol — x-height in mm, leading as a fraction of x-height, ISO 3664:2009, 0.4 m viewing distance.
- **Registered:** the typeface question may be *unanswerable* rather than open; cross-script non-transfer is predicted by the review; familiarity is asserted by Tarasov but refuted by the only direct test.

## 2026-10-02 — Typography / adaptation / dyslexia batch (11 papers)

- **Added:** 11 source pages, 12 concept pages, 13 entity pages.
- **Modified:** Comprehension (13→24 sources), Skimming (29→33), `index.md`, manifest.
- **Registered:** dyslexia font recommendation vs. individualization; adaptation is not uniformly beneficial; speed vs. fixation duration; preference ≠ effectiveness.
- **Caveats captured:** DyslexiaNet's 99.97% has a participant-leakage caveat and must not be read as diagnostic accuracy; Lorusso's identical speed medians; all personalization evidence uses one-tailed tests.

## [earlier] — Gen-AI batch

- **Added:** Guo 2025, Hedlin 2025, Pascoal 2026, plus the `syntheses/gen-ai-and-reading` theme hub.
- **Key distinction folded in:** **simplification** (rewrite, content preserved) helps/neutral vs. **summarization/compression** (content removed) can hurt.
