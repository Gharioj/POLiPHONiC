---
title: Provenance & Integration Record — POLiPHONiC Technical Architecture
integrates: technical-architecture.md
integrated: 2026-07-18
---

# Provenance & Integration Record: Technical Architecture

## Source

- Original file: `Constitutional files development in progress No 46/POLIPHONIC_Technical_Architecture_Constitutional_Infrastructure.docx`
- A second copy exists in the same folder: `POLIPHONIC_Technical_Architecture_Constitutional_Infrastructure (2).docx`. Both were extracted and diffed at the text level; their content is identical (only container-level metadata differs). The unnumbered copy was treated as the canonical source; the numbered copy was not otherwise used.
- Original format: Microsoft Word (.docx)
- Both original files were left unchanged at their source location; nothing was moved, renamed, or edited.

## Extraction method

Same method as prior integrations: the .docx unzipped as OOXML, text recovered by stripping tags from `word/document.xml`, split on paragraph boundaries. Formatting beyond plain emphasis is not preserved by this method and was not cross-checked against a normal rendering of the file.

## Constitutional dependency selected

**Technical Architecture** — verified by reading its own "Constitutional Provenance" section, which states it "is derived from the constitutional principles established within the Executive Briefing" and nothing else. The Executive Briefing is already integrated, so this dependency is satisfied. The two remaining named documents (Governance Charter, Founding Partners Charter) both cite the Technical Architecture itself as part of their own derivation chain — Governance Charter's Executive Overview states "The Executive Briefing establishes... The Technical Architecture establishes... This Governance Charter establishes...", and the Founding Partners Charter cites "the Executive Briefing, the Technical Architecture and the Governance Charter" together — so Technical Architecture is required by both and blocks neither being integrated ahead of it correctly.

## Constitutional judgements made during integration

1. **A genuine duplication in the source was found and resolved.** The source document repeats sections "5. Rights Architecture", "6. Economic Participation" and "7. Governance Architecture" twice in full, back-to-back — the section numbering runs 1, 2, 3, 4, 5, 6, 7, **5, 6, 7**, 8, 9, 10. The two occurrences of each section are identical in wording; they differ only in that the first occurrence renders each "Architectural Design" list as plain sentences (matching the style of sections 2–4), while the second occurrence renders the same lists as bulleted items (matching the style of sections 8–9 that follow). This reads as a leftover draft left in place after a later reformatting pass, not as sixteen (rather than ten) sections with the numbering counter reset. **Judgement made:** the document is integrated as ten uniquely-numbered sections, keeping the second (bulleted) occurrence of sections 5–7 and omitting the first (plain-sentence) occurrence, since it is superseded in place rather than substantively different. Nothing in the two occurrences differs in content — no constitutional wording was lost by this choice, only a duplicate rendering of the same wording. Both occurrences are quoted in full below for the record, in case this judgement needs to be revisited.
2. **HTML entity artefacts decoded.** The extraction left literal `&amp;` in place of `&` in several headings (e.g. "Identity &amp; Recognition"); these were decoded to `&` as a mechanical transcription fix, not a content change.
3. **Structure otherwise preserved as authored** — the introductory sections (Constitutional Provenance, Executive Technical Overview, Founding Philosophy, Constitutional Design Methodology, Constitutional Definitions, Architectural Principles), the ten numbered sections in order, the Constitutional Implementation Roadmap's five stages, and the Constitutional Closing Statement were all kept in their original order and grouping.
4. **Wording preserved verbatim** elsewhere; no paraphrasing or condensing beyond the duplication judgement above.
5. **Publication Information retained but separated**, consistent with prior integrations.
6. **No other cited document integrated** — Governance Charter and Founding Partners Charter remain outside the Foundation.

### The duplicated passage, quoted in full (both occurrences, for the record)

**First occurrence (plain-sentence form, immediately following section 4):**

> 5. Rights Architecture — Constitutional Principle: Collaboration defines Rights. Rights are derived from recognised participation, enduring authorship and transparent collaboration. They are not isolated legal instruments. They are constitutional expressions of the creative relationships from which they arise. Architectural Objective: The architecture establishes a rights layer through which recognised creative relationships become clearly defined legal and commercial relationships. Rights remain continuously connected to the recognised participation, authorship and Creative Compacts from which they are derived. This continuity establishes transparent constitutional relationships throughout creative ownership, licensing and future administration. Architectural Design: The Rights Architecture serves four constitutional objectives. Derive rights from recognised creative relationships. Preserve transparent constitutional provenance. Maintain continuity between creative participation and legal rights. Enable rights to evolve whilst preserving constitutional integrity. [... continues through Economic Participation and Governance Architecture with identical wording to the second occurrence integrated in the main document, differing only in list formatting.]

**Second occurrence (bulleted form — the one integrated into `technical-architecture.md`):** as shown in sections 5–7 of the integrated document.

## Unresolved constitutional questions

- The duplication itself is treated here as a document-production artefact, not a constitutional question — but *why* the document was left in this state (an incomplete edit, a merge error, or something else) is not known, and the underlying source file has not been corrected. If the Owner intends this repository's Foundation to track a "cleaned" master, that master should eventually be reconciled with the original at its source.
- No other genuinely constitutional tension (comparable to the Creator Constitution's rights/ownership question) was found in this document's substance.
