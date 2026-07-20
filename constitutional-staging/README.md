# Constitutional Staging

Holding area for Constitutional Knowledge awaiting integration into [`constitutional-foundation/`](../constitutional-foundation/README.md).

## Purpose

Material lands here first, with its provenance recorded, so that nothing reaches the Constitutional Foundation without a traceable origin.

Where submitted material distinguishes doctrine (definitions, principles) from organisational or process observations about itself, that distinction is preserved by staging them as separate files rather than merging them — see the 2026-07-20 items below for the pattern.

A complete constitutional draft — a whole, self-contained candidate constitution, as opposed to a working-session fragment — is staged in [`constitutional-drafts/`](constitutional-drafts/README.md), a subdirectory with its own versioned index. See that subdirectory's README for why it is organised separately; the staging rule itself is unchanged.

## Provenance

Every item staged here must be accompanied by a provenance record — see [`PROVENANCE_TEMPLATE.md`](PROVENANCE_TEMPLATE.md) — capturing at minimum:
- Original source (file name, location, or origin)
- Date staged
- Who or what introduced it
- Any notes on its state (draft, reviewed, translated, etc.)

## Naming convention

Each staged item is a `YYYY-MM-DD-<slug>.md` file paired with a `YYYY-MM-DD-<slug>.provenance.md` file built from [`PROVENANCE_TEMPLATE.md`](PROVENANCE_TEMPLATE.md). The date is the date staged, not the date of any earlier origin. Where more than one item is staged on the same date, append a distinguishing suffix to the slug rather than reusing it.

Where one submission is split across multiple files (e.g. to separate doctrine from an organisational observation, per Purpose above), the files may share a single provenance record rather than duplicating identical origin information — the shared record says so explicitly and each file links to it.

## Index

| Item | Staged | Status |
|---|---|---|
| [2026-07-20 — Constitutional Working Session](2026-07-20-constitutional-working-session.md) | 2026-07-20 | Staged — not reviewed |
| [2026-07-20 — Constitutional Working Session (Part 2)](2026-07-20-constitutional-discoveries-part2.md) | 2026-07-20 | Staged — not reviewed |
| [2026-07-20 — Architecture and Development Observations](2026-07-20-architecture-and-development-observations.md) | 2026-07-20 | Staged — not reviewed; self-described as organisational, not doctrinal |

See also [`UNDEFINED-TERMS.md`](UNDEFINED-TERMS.md) — terms named in staged material with no definition of their own anywhere in this repository — and [`constitutional-drafts/`](constitutional-drafts/README.md), the versioned index for complete constitutional drafts. Working Draft 1 passed through there in full (received, verified, integrated) and has since moved to [`constitution/`](../constitution/README.md); the entry that remains in `constitutional-drafts/` is a historical stub pointing to its new location.

## Relationship to other structures

- [`constitutional-foundation/`](../constitutional-foundation/README.md) — where staged material moves once reviewed and integrated. Six Foundation provenance records (Authorship, Rights, Custodianship, Governance Charter, Governance Procedures, Amendment) carry a reciprocal note where staged material reuses their names. As of the Working Draft 1 integration, the Foundation's own role is now explicitly the constitutional research and discovery record, distinct from the operative draft in `constitution/`.
- [`constitutional-drafts/`](constitutional-drafts/README.md) — this directory's own subdirectory for complete constitutional drafts, kept separate from the dated fragments indexed above because a complete draft is versioned and internally complete rather than a one-off dated submission.
- [`constitution/`](../constitution/README.md) — where a complete draft moves once fully received here and integrated. Not this directory's concern once that happens; see `constitutional-drafts/README.md` for the pattern.
