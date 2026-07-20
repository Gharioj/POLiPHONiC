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

A draft's provenance record should **not** assert how the draft relates to the already-integrated Constitutional Foundation beyond what has been explicitly settled by instruction — see "Where an integrated draft goes" below for what was settled for Working Draft 1 specifically. Anything beyond that (e.g. whether particular Foundation documents are superseded in substance by particular articles) remains for a reviewer, not for whoever stages a future draft.

## Index

| Draft | Staged | Status | Supersedes |
|---|---|---|---|
| [Working Draft 1](working-draft-1.md) | 2026-07-20 | **Integrated.** Moved to [`constitution/working-draft-1.md`](../../constitution/working-draft-1.md); this entry is a historical stub, not the current text. | none |

**Status vocabulary used in this index**, in the order an entry is expected to pass through them: *Scaffolded* (location, filename and metadata reserved; no content) → *Staged* (manuscript received and transcribed verbatim, provenance recorded) → *Integrated* (moved to [`constitution/`](../../constitution/README.md), the authoritative-draft location — not `constitutional-foundation/`, which holds the research and discovery record instead; see below).

## Where an integrated draft goes

Working Draft 1 established the pattern: once a complete draft's manuscript is fully received here and its structural integrity verified, it is moved to [`constitution/`](../../constitution/README.md) — a location distinct from `constitutional-foundation/` — and this directory keeps a stub pointing to its new location, not a duplicate copy. This was settled by explicit instruction accompanying Working Draft 1's integration: `constitutional-foundation/` is "the constitutional research and discovery record," preserved as-is; `constitution/` holds the operative draft "future constitutional revisions should evolve from." A future Working Draft 2 is expected to follow the same path.

## Relationship to other structures

- [`constitutional-staging/`](../README.md) — the parent directory. This subdirectory follows the same staging → review → integration rule; it is organised separately only because of the versioned, complete nature of what it holds.
- [`constitution/`](../../constitution/README.md) — where a fully-received, verified draft is moved on integration. Working Draft 1 no longer lives here; see its stub file for the pointer.
- [`constitutional-foundation/`](../../constitutional-foundation/README.md) — the constitutional research and discovery record a draft is assembled from. Not the destination for an integrated draft; not altered by any integration performed here.
- [`constitutional-discoveries/`](../../constitutional-discoveries/README.md) — a complete draft may speak to one or more open discoveries, the way earlier staged fragments have. Any such connection should be noted in the draft's provenance record, per the pattern already used for the two working sessions staged in the parent directory and for Working Draft 1, without altering the discovery's own text or status.

---

[← Constitutional Staging](../README.md)
