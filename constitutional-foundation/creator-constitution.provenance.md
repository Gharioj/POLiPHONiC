---
title: Provenance & Integration Record — POLiPHONiC Creator Constitution
integrates: creator-constitution.md
integrated: 2026-07-18
---

# Provenance & Integration Record: Creator Constitution

## Source

- Original file: `Constitutional files development in progress No 46/POLiPHONiC_Creator_Constitution_Constitutional_Infrastructure_for.docx`
- Original format: Microsoft Word (.docx)
- The original file was left unchanged at its source location; nothing was moved, renamed, or edited.

## Extraction method

No .docx-to-text converter (pandoc, LibreOffice, python-docx) was available in this environment. Text was recovered by unzipping the .docx as OOXML, then stripping XML tags from `word/document.xml`, splitting on paragraph boundaries. This yields the document's text faithfully but **discards formatting** (bold/italic emphasis, any tables, footnotes, or embedded images, if present). The extracted text was not cross-checked against a rendered view of the original file, since no rendering tool was available — see Unresolved Questions.

## Constitutional judgements made during integration

1. **Format chosen: Markdown, preserving the source's own structure.** The seven numbered articles and their repeating Constitutional Principle / Objective / Design / Outcome sub-structure were kept exactly as authored — no article was reordered, merged, split, or renamed.
2. **Wording preserved verbatim.** No sentence was paraphrased, condensed, or corrected. Bullet lists in the source ("Creators have the constitutional right to...", "Creators shall...") were rendered as Markdown lists rather than prose, since that was the source's own structure — a formatting choice, not a content change.
3. **Publication Information retained but separated.** The closing publication block (edition, language, classification, copyright, domains) was kept as part of the integrated record, under its own heading, rather than discarded — it is source metadata, not constitutional substance, so it was not merged into the constitutional articles above it.
4. **No cross-referenced document was consulted or integrated.** The source text itself states this Constitution "is derived from the constitutional principles established within the Executive Briefing, the Technical Architecture, the Governance Charter and the Founding Partners Charter." None of those four documents have been integrated. This Constitution is recorded in the Foundation on its own terms, as the single approved Constitutional Intent — its stated dependency on those four documents is preserved as written, not resolved or removed.
5. **No tension in the source text was smoothed over.** The Provenance section states "this Constitution does not establish creative ownership," while Article 3 establishes creators' rights including "transparent economic participation" and "enduring constitutional legacy." Both statements are transcribed exactly as written; reconciling what "rights without ownership" means constitutionally is not something this integration resolves.

## Unresolved constitutional questions

- The Constitution declares its own authority as derived from four other documents (Executive Briefing, Technical Architecture, Governance Charter, Founding Partners Charter), none of which were yet in the Constitutional Foundation at the time this question was first recorded. Whether the Creator Constitution stood as authoritative in the interim, or whether one of those four should have been integrated first to ground it, was not decided here. *Factual update, not a resolution:* as of v0.6.0, all four named documents are now integrated into the Foundation, closing the dependency gap this question describes — whether that also settles the underlying interim-authority question is not decided here either.
- The relationship between "rights" (Article 3) and the explicit disclaimer that the Constitution "does not establish creative ownership" (Provenance section) is stated but not defined — a future integration or a human ruling may need to clarify how recognition, rights, and ownership are constitutionally distinguished. Indexed as [Constitutional Discovery 001](../constitutional-discoveries/001-rights-vs-ownership-undefined.md).
- Fidelity caveat: because extraction stripped all formatting, any emphasis, tables, or embedded material in the original .docx (if present) is not reflected in `creator-constitution.md`. A human comparison against the original file, opened normally, has not been done.
