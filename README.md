# POLiPHONiC

## Status

All 39 documents named in the corpus's own "Constitutional Provenance" chain are integrated into `constitutional-foundation/`. One Constitutional Resolution has been recorded. Five Constitutional Discoveries are open. Two items are staged awaiting review. See `CHANGELOG.md` for the full integration history.

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
