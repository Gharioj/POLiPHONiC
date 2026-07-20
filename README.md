# POLiPHONiC

## Status

**Constitutional Phase 1 is concluded:**
- **Working Draft 1 — Complete.** Integrated at [`constitution/working-draft-1.md`](constitution/working-draft-1.md), received in eight sequential manuscript sections, 2026-07-20.
- **Editorial Review — Complete.** Banked at [`constitution/working-draft-1-editorial-review.md`](constitution/working-draft-1-editorial-review.md) as the editorial baseline for Working Draft 2 — 5 objective editorial issues, 6 constitutional coherence issues, every recommendation preserved exactly as produced, none implemented.
- **Working Draft 2 — Not Started.** Awaiting further instruction from the constitutional architects.

All 39 documents named in the corpus's own "Constitutional Provenance" chain remain fully integrated and preserved in `constitutional-foundation/`, now understood as the constitutional research and discovery record the operative draft was assembled from, not the operative text itself. One Constitutional Resolution has been recorded. Five Constitutional Discoveries are open — two (001, 003) now carry notes on where Working Draft 1 speaks to them, without resolving either. Three fragments remain staged awaiting review in `constitutional-staging/`. See `CHANGELOG.md` for the full integration history.

## Structure

- [`constitution/`](constitution/README.md) — the authoritative, operative constitutional text. Currently Working Draft 1.
- [`constitutional-foundation/`](constitutional-foundation/README.md) — the constitutional research and discovery record: 39 integrated source documents, preserved unmodified, that the operative draft was assembled from and departs from.
- [`constitutional-staging/`](constitutional-staging/README.md) — constitutional knowledge awaiting integration, held here with its provenance recorded, prior to review. Includes [`constitutional-drafts/`](constitutional-staging/constitutional-drafts/README.md), the reception point for future complete constitutional drafts.
- [`constitutional-discoveries/`](constitutional-discoveries/README.md) — constitutional questions, tensions and anomalies noticed as they emerged during constitutional development, recorded in chronological order.
- [`constitutional-resolutions/`](constitutional-resolutions/README.md) — constitutional rulings recorded directly, linked to the Foundation without modifying it.

## Architecture

How the five directories relate, end to end:

```
constitutional-staging/              ──review──>   constitutional-foundation/
 (new material, provenance                          (reviewed, integrated,
  recorded, awaiting review)                       constitutional research
      │                                             and discovery record)
      │ constitutional-drafts/                              │
      │ (complete draft manuscripts,                        │
      │  received and verified)                             │
      ▼                                                      │
  ──integration──>  constitution/                            │
                     (the operative constitutional            │
                      draft — currently Working Draft 1)      │
                                                              │
                                        integration/review surfaces tensions
                                                              ▼
                                                   constitutional-discoveries/
                                                   (questions & anomalies noticed,
                                                    chronological, unresolved)
                                                              │
                                                   deliberate human judgement
                                                              ▼
                                                   constitutional-resolutions/
                                                   (constitutional judgements
                                                    formally adopted)
```

Material never skips a step: nothing reaches the Foundation without first being staged with provenance; a complete draft is integrated into `constitution/` only after being fully received and verified in `constitutional-staging/constitutional-drafts/`; nothing becomes a Resolution merely by being discovered, staged, or integrated. Each directory's own README describes its relationship to the others in more detail.

## Phase

**Constitutional Phase 1 — concluded.** The Foundation's Constitutional Knowledge Integration is complete; separately, "POLiPHONiC Constitution — Working Draft 1" was received as eight sequential manuscript sections from the constitutional architects on 2026-07-20 and integrated at [`constitution/working-draft-1.md`](constitution/working-draft-1.md). Its [provenance record](constitution/working-draft-1.provenance.md) documents the manuscript exactly as received, including several unresolved structural anomalies (article-numbering gaps at 1–30 and 37–49, an unheaded opening fragment, three inconsistent structural labelling schemes, and two pairs of duplicate article titles) — none corrected, all flagged for the constitutional architects.

A full Constitutional Editorial Review of Working Draft 1 followed, and is banked at [`constitution/working-draft-1-editorial-review.md`](constitution/working-draft-1-editorial-review.md) as the **editorial baseline for Working Draft 2**: 5 objective editorial issues and 6 constitutional coherence issues, each cited and explained with a recommended minimum action. Every recommendation is preserved exactly as produced; none has been implemented, and no constitutional decision was made in producing the review.

Several unresolved constitutional questions remain — indexed chronologically in [`constitutional-discoveries/`](constitutional-discoveries/README.md) (rights vs. ownership, the undefined governance body/process, a source duplication, two source documents found genuinely incomplete, and an unreconciled altitude duplication between the Legal & Constitutional Framework and two dedicated frameworks). Working Draft 1 speaks to two of these (001, 003) without resolving either — these await a Constitutional Resolution or further constitutional judgement, not further mechanical integration.

**Working Draft 2 has not started.** The repository is prepared to receive it via the same path Working Draft 1 took — staged and assembled in [`constitutional-staging/constitutional-drafts/`](constitutional-staging/constitutional-drafts/README.md), then integrated into [`constitution/`](constitution/README.md) with a provenance record stating what it supersedes — but no file, section, or content for it exists, and no further constitutional work proceeds until the constitutional architects give further instruction.
