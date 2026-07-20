# Changelog

## 0.32.0 — 2026-07-20
Added an "Architecture" section to the root `README.md`: a single diagram showing how `constitutional-staging/`, `constitutional-foundation/`, `constitutional-discoveries/` and `constitutional-resolutions/` relate as a pipeline. Each directory's own README already described its relationship to its neighbours individually; there was no single place showing the whole flow at once.

- No constitutional judgement made, no constitutional document's wording changed. Purely a navigational addition describing existing, already-established structure.

## 0.31.0 — 2026-07-20
Staged fourteen constitutional definitions, principles and progressions submitted in a working session today, per explicit instruction to integrate them. Filed in `constitutional-staging/`, not `constitutional-discoveries/` or `constitutional-resolutions/`: the material has no prior corpus source to cite (ruling out Discoveries, which are citations to gaps already visible in existing text), and has not been reviewed or adopted (ruling out Resolutions, which the instruction also explicitly excluded). Staging is this repository's own designated holding area for exactly this situation.

- `constitutional-staging/2026-07-20-constitutional-working-session.md` — the fourteen items, verbatim, reformatted only into Markdown headings.
- `constitutional-staging/2026-07-20-constitutional-working-session.provenance.md` — provenance per the existing template, plus five specific points flagged for a future reviewer: overlap with open Discovery 001 (rights vs. ownership) via §4/§10; overlap with open Discovery 003 (undefined governance authority) via §5/§11/§12; independently-worded redefinitions of terms already integrated in the Foundation (Authorship, Rights, Custodianship Frameworks); wholly new terms with no Foundation counterpart; and the fact that all fourteen items form one interdependent system, not fourteen independent ones.
- `constitutional-discoveries/001-rights-vs-ownership-undefined.md` and `003-undefined-governance-authority-and-process.md` — each given a one-line dated note pointing to the new staged material, without altering either discovery's existing text or "open" status.
- `constitutional-staging/README.md` and root `README.md` updated to reflect the staged item.
- No constitutional judgement made: nothing was adopted, resolved, reconciled, or rewritten. No Constitutional Resolution was created.

## 0.30.0 — 2026-07-20
Closed a navigation dead-end: none of the 5 discovery records or the 1 resolution record linked back to their own directory index, so a reader arriving via a backlink from `constitutional-foundation/` had no way back up. Added a `[← Constitutional Discoveries](README.md)` / `[← Constitutional Resolutions](README.md)` footer to all 6 files.

- Verified every markdown link in the repository still resolves.
- No constitutional judgement made, no constitutional document's wording changed. (The 39 documents and provenance files in `constitutional-foundation/` were not touched by this pass — the `.md` documents are constitutional text and out of scope, and the `.provenance.md` files' existing lack of a same backlink is a separate, larger, pre-existing pattern not addressed here.)

## 0.29.0 — 2026-07-20
Navigation symmetry pass across the four top-level directory READMEs. `constitutional-discoveries/` had a "Relationship to other structures" section; the other three didn't, and `constitutional-foundation/README.md` linked out to Resolutions and Discoveries but never back to Staging, despite Staging's whole purpose being to feed it.

- `constitutional-foundation/README.md` — added a "Constitutional Staging" section; replaced the Discoveries section's inline example list (which would go stale every time a new discovery is added) with a pointer to the Discoveries index itself.
- `constitutional-resolutions/README.md` and `constitutional-staging/README.md` — added matching "Relationship to other structures" sections.
- Verified every markdown link in the repository (not a sample) resolves correctly, before and after.
- No constitutional judgement made, no constitutional document's wording changed.

## 0.28.0 — 2026-07-20
Two small editorial fixes found during a full audit pass: normalised two backlink sentences (`economic-participation-framework.provenance.md`, `dispute-resolution-framework.provenance.md`) to the same "Indexed as" phrasing used by the other fifteen; and added a factual-currency note to `creator-constitution.provenance.md`'s first unresolved question, which named four dependency documents as unintegrated — they have in fact all been integrated since v0.6.0. The note states this fact only; it explicitly does not decide whether it resolves the underlying interim-authority question, which remains open.

- No constitutional judgement made, no constitutional document's wording changed.

## 0.27.0 — 2026-07-20
Clarified `constitutional-discoveries/README.md`: Discovery 005's "first identified" date (v0.12.0) predates Discovery 004's (v0.23.0), since 005 was only catalogued today despite originating earlier in the integration sequence. Added a short note distinguishing the index's own append-only ordering (never renumbered) from the "First identified" column's separate, earlier timeline, so the apparent non-monotonic ordering doesn't read as an error.

- No constitutional judgement made, no constitutional document's wording changed. Editorial clarification only.

## 0.26.0 — 2026-07-20
Full audit of every `.provenance.md` file's "Unresolved/Remaining constitutional questions" section against the existing four Constitutional Discoveries, per the standing instruction to treat `constitutional-discoveries/` as canonical for future discoveries. Found one genuinely new, previously unindexed discovery, and three further reinforcing instances of an existing one.

- Added `constitutional-discoveries/005-legal-framework-altitude-duplication.md`: the Legal & Constitutional Framework's §4/§7 cover the same ground as the dedicated Rights and Dispute Resolution Frameworks at a shorter altitude — flagged in its provenance record (v0.12.0) as an undecided question (intentional layering vs. unreconciled duplication) and never indexed until now.
- Backlinked `legal-constitutional-framework.provenance.md` to Discovery 005.
- Backlinked three further provenance files to Discovery 003 (undefined governance authority and process), each of which had already noted an instance of the same gap without a cross-reference: `assurance-framework.provenance.md`, `operations-framework.provenance.md`, `technical-implementation-specification.provenance.md`.
- `constitutional-discoveries/README.md` and root `README.md` updated: five discoveries now indexed.
- Considered and deliberately did not index the Terminology Framework's "no authoritative glossary" observation as a new discovery: its own provenance record explicitly frames it as "not a new category of gap," the same principle-without-mechanism pattern already covered by Discovery 003, applied to a different domain — respecting that existing editorial judgement rather than overriding it.
- No constitutional judgement made: nothing was resolved, no constitutional document's wording was touched.

## 0.25.0 — 2026-07-20
Backlinked each `.provenance.md` file in `constitutional-foundation/` to the Constitutional Discovery record(s) it originally fed, completing the cross-reference in both directions (discoveries already linked to provenance; provenance now links back). Editorial/structural only: the substance of each provenance file's own commentary was left untouched, only a citation was appended.

- 13 provenance files updated: `creator-constitution`, `rights-framework`, `authorship-framework`, `custodianship-framework`, `economic-participation-framework`, `dispute-resolution-framework`, `technical-architecture`, `governance-charter`, `founding-partners-charter`, `governance-procedures-framework`, `amendment-framework`, `knowledge-framework`, `interpretation-framework`.
- No constitutional judgement made: no discovery was resolved, no wording of any constitutional document was changed.

## 0.24.0 — 2026-07-20
Added `constitutional-discoveries/` — a chronological index of constitutional questions, tensions and anomalies already noticed and recorded (in `.provenance.md` files and this Changelog) during the integration sequence, but never before collected in one place. Repository organisation only: no constitutional text was rewritten, no constitutional question was resolved, and no document in `constitutional-foundation/` or `constitutional-resolutions/` was modified.

- `constitutional-discoveries/README.md` and four discovery records, each citing and linking back to where the discovery was first made: rights vs. ownership (001, first identified integrating the Creator Constitution, v0.2.0), the Technical Architecture source duplication (002, v0.4.0), the undefined governance authority and process (003, first identified integrating the Governance Charter, v0.5.0), and the two source documents found incomplete (004, v0.23.0).
- Root `README.md`, `constitutional-foundation/README.md` and `constitutional-resolutions/README.md` updated to cross-reference the new directory.
- No constitutional judgement made: all four discoveries remain open.

## 0.23.0 — 2026-07-18
Integrated the Constitutional Transparency (32), Knowledge (33), Publication (34), Terminology (35), Implementation (37) and Interpretation (38) Frameworks, completing the entire 39-document reconstructed sequence.

- `constitutional-foundation/transparency-framework.md`, `knowledge-framework.md`, `publication-framework.md`, `terminology-framework.md`, `implementation-framework.md`, `interpretation-framework.md` and their `.provenance.md` companions.
- All dependencies fully satisfied. Two further source-document defects found and handled per the Technical Architecture precedent (deduplicate/transcribe-what-exists, fabricate nothing): the Knowledge Framework duplicates sections 2–5 and is missing sections 6–7, the Closing Statement and Publication Information entirely; the Interpretation Framework is missing sections 2–5 outright. Both confirmed against raw XML, not just plain-text extraction.
- Root `README.md` and `constitutional-foundation/README.md` updated to reflect that the full named corpus is now integrated.
- Source documents left unchanged. No previously integrated document modified.

## 0.22.0 — 2026-07-18
Integrated the Constitutional API & Integration (27), Compliance (28), Certification (29) and Custodianship (30) Frameworks, continuing autonomous constitutional integration.

- `constitutional-foundation/api-integration-framework.md`, `compliance-framework.md`, `certification-framework.md`, `custodianship-framework.md` and their `.provenance.md` companions.
- All dependencies fully satisfied. The Custodianship Framework repeats the "not ownership" disclaimer seen with rights and authorship, now applied to governance roles — reinforcing rather than resolving the unresolved rights-vs-ownership question. No custodian, custodial body, or succession procedure is named anywhere in the Foundation.
- Source documents left unchanged. No previously integrated document modified.

## 0.21.0 — 2026-07-18
Integrated the Constitutional Security (24), Privacy (25) and AI (26) Frameworks, continuing autonomous constitutional integration.

- `constitutional-foundation/security-framework.md`, `privacy-framework.md`, `ai-framework.md` and their `.provenance.md` companions.
- All dependencies fully satisfied. The AI Framework's source had three additional numbered duplicate copies, all diffed and confirmed text-identical.
- Source documents left unchanged. No previously integrated document modified.

## 0.20.0 — 2026-07-18
Integrated the Constitutional Recognition (21), Legacy (22) and Creative Compacts (23) Frameworks, continuing autonomous constitutional integration.

- `constitutional-foundation/recognition-framework.md`, `legacy-framework.md`, `creative-compacts-framework.md` and their `.provenance.md` companions.
- All dependencies fully satisfied. The Recognition Framework has six sections rather than the usual seven — verified as the source's actual structure, not a missing section.
- Source documents left unchanged. No previously integrated document modified.

## 0.19.0 — 2026-07-18
Integrated the Constitutional Collaboration (18), Rights (19) and Authorship (20) Frameworks, continuing autonomous constitutional integration.

- `constitutional-foundation/collaboration-framework.md`, `rights-framework.md`, `authorship-framework.md` and their `.provenance.md` companions.
- All dependencies fully satisfied. Notable finding: the dedicated Rights Framework, the most likely place in the corpus to resolve the Creator Constitution's rights-vs-ownership tension, does not resolve it — it never mentions ownership. The Authorship Framework repeats the same unresolved distinction.
- Source documents left unchanged. No previously integrated document modified.

## 0.18.0 — 2026-07-18
Integrated the Constitutional Identity (15), Data (16) and Provenance (17) Frameworks, continuing autonomous constitutional integration.

- `constitutional-foundation/identity-framework.md`, `data-framework.md`, `provenance-framework.md` and their `.provenance.md` companions.
- All dependencies fully satisfied; no new constitutional issues found. Source documents left unchanged. No previously integrated document modified.

## 0.17.0 — 2026-07-18
Integrated the Constitutional Innovation Framework (position 13) and Constitutional Trust Framework (position 14), continuing autonomous constitutional integration.

- `constitutional-foundation/innovation-framework.md` and `.provenance.md`.
- `constitutional-foundation/trust-framework.md` and `.provenance.md`.
- Both dependencies fully satisfied; no new constitutional issues found. Source documents left unchanged. No previously integrated document modified.

## 0.16.0 — 2026-07-18
Integrated the Constitutional Assurance Framework (position 11) and Constitutional Interoperability Framework (position 12), continuing autonomous constitutional integration.

- `constitutional-foundation/assurance-framework.md` and `.provenance.md`.
- `constitutional-foundation/interoperability-framework.md` and `.provenance.md`.
- Both dependencies fully satisfied; no new constitutional issues found. Source documents left unchanged. No previously integrated document modified.

## 0.15.0 — 2026-07-18
Integrated the Constitutional Operations Framework, continuing autonomous constitutional integration.

- `constitutional-foundation/operations-framework.md` — transcribed from its source `.docx`.
- `constitutional-foundation/operations-framework.provenance.md` — provenance record; dependency fully satisfied, no new constitutional issues found.
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.14.0 — 2026-07-18
Integrated the Constitutional Standards Framework, continuing autonomous constitutional integration.

- `constitutional-foundation/standards-framework.md` — transcribed from its source `.docx`.
- `constitutional-foundation/standards-framework.provenance.md` — provenance record; dependency fully satisfied, no new constitutional issues found.
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.13.0 — 2026-07-18
Integrated the Economic Participation Framework, continuing autonomous constitutional integration.

- `constitutional-foundation/economic-participation-framework.md` — transcribed from its source `.docx`.
- `constitutional-foundation/economic-participation-framework.provenance.md` — provenance record; dependency fully satisfied, no new constitutional issues found.
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.12.0 — 2026-07-18
Integrated the Legal & Constitutional Framework, continuing autonomous constitutional integration.

- `constitutional-foundation/legal-constitutional-framework.md` — transcribed from its source `.docx`; a missing section number (auto-numbering field lost in extraction) was restored for consistency.
- `constitutional-foundation/legal-constitutional-framework.provenance.md` — provenance record; notes this document's rights and dispute-resolution sections cover the same ground as dedicated frameworks elsewhere in the corpus, without contradiction.
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.11.0 — 2026-07-18
Integrated the Technical Implementation Specification, continuing autonomous constitutional integration.

- `constitutional-foundation/technical-implementation-specification.md` — transcribed from its source `.docx`.
- `constitutional-foundation/technical-implementation-specification.provenance.md` — provenance record, including a methodological finding: cross-referencing this session's integrated documents' own "Constitutional Provenance" lists reveals a reconstructable 39-document authorship order for the whole corpus, used from here on to select what to integrate next.
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.10.0 — 2026-07-18
Integrated the Constitutional Dispute Resolution Framework, continuing autonomous constitutional integration.

- `constitutional-foundation/dispute-resolution-framework.md` — transcribed from its source `.docx`.
- `constitutional-foundation/dispute-resolution-framework.provenance.md` — provenance record; confirms the recurring undefined-mechanism gap (no forum or panel named), and notes this framework explicitly disclaims creating new rights, meaning it cannot itself resolve the Creator Constitution's rights-vs-ownership ambiguity.
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.9.0 — 2026-07-18
Integrated the Constitutional Amendment Framework, continuing autonomous constitutional integration.

- `constitutional-foundation/amendment-framework.md` — transcribed from its source `.docx`.
- `constitutional-foundation/amendment-framework.provenance.md` — provenance record; confirms the same undefined-mechanism gap found in the Governance Procedures Framework (amendment criteria are stated, but no proposer, approving body, or ratification step is named).
- Source document left unchanged. No other document integrated. No previously integrated document modified.

## 0.8.0 — 2026-07-18
Integrated the Constitutional Governance Procedures Framework, per the prior Constitutional Review's recommendation.

- `constitutional-foundation/governance-procedures-framework.md` — transcribed from its source `.docx`.
- `constitutional-foundation/governance-procedures-framework.provenance.md` — provenance record, including a documented finding that this document's own stated dependency (38 named documents) is only 5/38 satisfied by the current Foundation, and that it does not itself define a governance body, decision-making entity, amendment procedure or dispute-resolution mechanism despite being selected to address that gap.
- Source document left unchanged at `Constitutional files development in progress No 46/`. No other document integrated. No previously integrated document modified.

## 0.7.0 — 2026-07-18
Recorded Constitutional Resolution 001, linked to the Constitutional Foundation.

- New `constitutional-resolutions/` — constitutional rulings recorded directly rather than integrated from source material.
- `constitutional-resolutions/001-constitution-founded-on-enduring-principles.md` — the resolution, recorded verbatim, with provenance and a link to the Foundation.
- `constitutional-foundation/README.md` and root `README.md` updated to reference the new folder. No existing constitutional document was modified. No document integrated.

## 0.6.0 — 2026-07-18
Integrated the Founding Partners Charter — completing the constitutional backbone the Creator Constitution originally named (Executive Briefing, Technical Architecture, Governance Charter, Founding Partners Charter).

- `constitutional-foundation/founding-partners-charter.md` — the Founding Partners Charter, transcribed from its source `.docx`.
- `constitutional-foundation/founding-partners-charter.provenance.md` — provenance record, dependency verification, and constitutional judgements made during integration.
- Source document left unchanged at `Constitutional files development in progress No 46/`. No other document integrated.

## 0.5.0 — 2026-07-18
Integrated the Governance Charter — the next constitutional dependency within the remaining backbone, verified as depending only on the already-integrated Executive Briefing and Technical Architecture.

- `constitutional-foundation/governance-charter.md` — the Governance Charter, transcribed from its source `.docx`.
- `constitutional-foundation/governance-charter.provenance.md` — provenance record, dependency verification, and constitutional judgements made during integration.
- Source document left unchanged at `Constitutional files development in progress No 46/`. No other document integrated. The Founding Partners Charter, which depends on this document, remains outside the Foundation.

## 0.4.0 — 2026-07-18
Integrated the Technical Architecture — the next constitutional dependency, verified as depending only on the already-integrated Executive Briefing.

- `constitutional-foundation/technical-architecture.md` — the Technical Architecture, transcribed from its source `.docx`.
- `constitutional-foundation/technical-architecture.provenance.md` — provenance record, dependency verification, and constitutional judgements made during integration, including a documented duplication found in the source (sections 5–7 appeared twice; the later, differently-formatted occurrence was kept, both are quoted in the provenance record).
- Source document (and its duplicate copy) left unchanged at `Constitutional files development in progress No 46/`. No other document integrated.

## 0.3.0 — 2026-07-18
Integrated the Executive Briefing — selected as the highest-priority remaining constitutional dependency, being the root document the Creator Constitution, Technical Architecture, Governance Charter and Founding Partners Charter all derive from.

- `constitutional-foundation/executive-briefing.md` — the Executive Briefing, transcribed faithfully from its source `.docx`.
- `constitutional-foundation/executive-briefing.provenance.md` — provenance record, dependency selection rationale, and constitutional judgements made during integration.
- Source document left unchanged at `Constitutional files development in progress No 46/`. No other document integrated.

## 0.2.0 — 2026-07-18
Integrated the Creator Constitution — the first document in the Constitutional Foundation.

- `constitutional-foundation/creator-constitution.md` — the Creator Constitution, transcribed faithfully from its source `.docx`.
- `constitutional-foundation/creator-constitution.provenance.md` — provenance record and constitutional judgements made during integration.
- Source document left unchanged at `Constitutional files development in progress No 46/`. No other document integrated.

## 0.1.0 — 2026-07-18
Repository initialised.

- `constitutional-foundation/` created — the primary knowledge structure for the integrated constitutional record. Empty; no content integrated.
- `constitutional-staging/` created — holding area for Constitutional Knowledge awaiting integration, with a provenance record template. Empty; nothing staged.
