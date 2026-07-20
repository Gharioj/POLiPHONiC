# POLiPHONiC

## Status

All 39 documents named in the corpus's own "Constitutional Provenance" chain are integrated into `constitutional-foundation/`. One Constitutional Resolution has been recorded. Five Constitutional Discoveries are open. Three items are staged awaiting review. A placeholder manuscript for the first complete constitutional draft is scaffolded at [`constitutional-staging/constitutional-drafts/working-draft-1.md`](constitutional-staging/constitutional-drafts/working-draft-1.md), reserved for "POLiPHONiC Constitution — Working Draft 1"; it contains no constitutional content, pending delivery by the constitutional architects. See `CHANGELOG.md` for the full integration history.

## Structure

- [`constitutional-foundation/`](constitutional-foundation/README.md) — the integrated constitutional record. The primary knowledge structure for POLiPHONiC, populated only once material has been reviewed and integrated.
- [`constitutional-staging/`](constitutional-staging/README.md) — constitutional knowledge awaiting integration, held here with its provenance recorded, prior to review.
- [`constitutional-discoveries/`](constitutional-discoveries/README.md) — constitutional questions, tensions and anomalies noticed as they emerged during constitutional development, recorded in chronological order.
- [`constitutional-resolutions/`](constitutional-resolutions/README.md) — constitutional rulings recorded directly, linked to the Foundation without modifying it.

## Architecture

How the four directories relate, end to end:

```
constitutional-staging/  ──review, integration──>  constitutional-foundation/
 (new material, provenance                          (reviewed, integrated,
  recorded, awaiting review)                         authoritative record)
                                                              │
                                                   integration surfaces tensions
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

Material never skips a step: nothing reaches the Foundation without first being staged with provenance; nothing becomes a Resolution merely by being discovered or staged. Each directory's own README describes its relationship to the others in more detail.

## Phase

Constitutional Knowledge Integration of the named corpus is complete. Several unresolved constitutional questions remain — now indexed chronologically in [`constitutional-discoveries/`](constitutional-discoveries/README.md) (rights vs. ownership, the undefined governance body/process, a source duplication, two source documents found genuinely incomplete, and an unreconciled altitude duplication between the Legal & Constitutional Framework and two dedicated frameworks) — these await a Constitutional Resolution or further constitutional judgement, not further mechanical integration.

Separately, the repository has been prepared to receive a first complete constitutional draft ("Working Draft 1"), expected from the constitutional architects. This preparation is now two steps deep: a reception point ([`constitutional-staging/constitutional-drafts/`](constitutional-staging/constitutional-drafts/README.md)) exists, and within it a placeholder manuscript ([`working-draft-1.md`](constitutional-staging/constitutional-drafts/working-draft-1.md)) reserves the file's permanent name and location, ready to receive the manuscript in place once delivered. No draft content has been supplied or staged. How such a draft — a single, complete, versioned document — relates to a Foundation currently organised as 39 separate framework documents is an open architectural question, deliberately left undecided until an actual draft exists to review.
