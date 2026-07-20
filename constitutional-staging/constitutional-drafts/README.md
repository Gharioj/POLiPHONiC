# Constitutional Drafts

A subdirectory of [`constitutional-staging/`](../README.md) for complete constitutional drafts — whole, self-contained candidate constitutions submitted as a single coherent document — as distinct from the individual working-session fragments (definitions, principles, observations) indexed directly in the parent staging directory.

Nothing in this subdirectory changes the staging rule stated in the parent README: material lands here first, with its provenance recorded, so that nothing reaches [`constitutional-foundation/`](../../constitutional-foundation/README.md) without a traceable origin and a deliberate review.

## Why a separate subdirectory

A complete constitutional draft is a different kind of object from the working-session fragments already staged (see the parent index):

- **It is versioned in its own right.** "Working Draft 1" implies a lineage — a Draft 2, Draft 3, and so on are expected to follow. The parent directory's flat `YYYY-MM-DD-<slug>.md` index has no way to express "this draft supersedes that one"; a sequential per-draft index here does.
- **It is internally complete**, not a set of loose items. It is reviewed and indexed as one document, not decomposed into per-item entries the way the fourteen-item working session was.

This is an organisational distinction only. It does not exempt anything staged here from review, does not make a draft more or less authoritative than any other staged item, and does not by itself relate a draft to the Constitutional Foundation in any way — see below.

## Naming convention

Each staged draft is a `working-draft-<N>.md` file paired with a `working-draft-<N>.provenance.md` file built from [`../PROVENANCE_TEMPLATE.md`](../PROVENANCE_TEMPLATE.md). In addition to that template's required fields, a draft's provenance record should state which earlier draft, if any, it supersedes.

A draft's provenance record should **not** assert how the draft relates to the already-integrated Constitutional Foundation — whether it replaces, complements, consolidates, or must be reconciled document-by-document with the 39 documents already integrated there is an open architectural question for a reviewer to settle at integration time, not something to be decided by whoever stages it.

## Index

| Draft | Staged | Status | Supersedes |
|---|---|---|---|
| [Working Draft 1](working-draft-1.md) | not yet — scaffolded 2026-07-20 | **Scaffolded.** Placeholder file and provenance record exist; no constitutional content has been supplied. | none |

**Status vocabulary used in this index**, in the order an entry is expected to pass through them: *Scaffolded* (location, filename and metadata reserved; no content) → *Staged* (manuscript received and transcribed verbatim, provenance recorded — the same meaning "Staged" carries in the parent directory's index) → *Reviewed* / *Integrated* (moved into [`constitutional-foundation/`](../../constitutional-foundation/README.md), a distinct later act like every other integration recorded in `CHANGELOG.md`).

## Receiving the manuscript

[`working-draft-1.md`](working-draft-1.md) and [`working-draft-1.provenance.md`](working-draft-1.provenance.md) already exist at their permanent filenames and location. When "POLiPHONiC Constitution — Working Draft 1" is actually delivered, it should be **written into the existing placeholder file in place** — replacing the placeholder notice with a verbatim transcription — and the provenance file replaced with a real record per the template in its own "When the manuscript is supplied" section. No new file, rename, or further restructuring of this directory should be needed for Working Draft 1 itself; only the Index row above and this section's status need updating, plus the usual `CHANGELOG.md` entry.

## Relationship to other structures

- [`constitutional-staging/`](../README.md) — the parent directory. This subdirectory follows the same staging → review → integration rule; it is organised separately only because of the versioned, complete nature of what it holds.
- [`constitutional-foundation/`](../../constitutional-foundation/README.md) — where a draft moves, in whole or in part, only once reviewed. Nothing staged here has been reviewed. How a complete draft's material maps onto a Foundation currently organised as 39 separate framework documents is not decided by this directory's existence.
- [`constitutional-discoveries/`](../../constitutional-discoveries/README.md) — a complete draft may speak to one or more open discoveries, the way earlier staged fragments have. Any such connection should be noted in the draft's provenance record, per the pattern already used for the two working sessions staged in the parent directory, without altering the discovery's own text or status.

---

[← Constitutional Staging](../README.md)
