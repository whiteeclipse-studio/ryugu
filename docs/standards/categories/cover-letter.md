---
id: std-whv-cover-letter
standard_revision: 1
---

# WHV cover letter standard

## Purpose and scope

The cover letter explains the applicant's personal reasons for undertaking a Working Holiday in Japan and how the intended stay supports those aims. It accompanies the travel plan in the application dossier.

This draft category extends the Hypatia shared documentation and governance standards bound in the [standards entrypoint](../README.md). Revision 1 uses revision 1 of [PUBLICATION](../PUBLICATION.md) and the [travel plan standard](./travel-plan.md). These are Ryugu authoring requirements; the applicable consulate's exact requirements remain to be verified. Review and formal adoption remain pending.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Requirement terminology

Uppercase requirement keywords follow IETF **BCP 14**, as defined by [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and clarified by [RFC 8174](https://www.rfc-editor.org/rfc/rfc8174). Their BCP 14 meanings apply only when written entirely in uppercase.

## Location and identification

The canonical English source MUST reside at `docs/internal/application/cover-letter/README.md`, with a project-unique stable ID and `standard_revision: 1` when following this category's revision 1. This category also governs supporting pages within that directory. Supporting pages MUST link back to the entrypoint and inherit its standard pin; each retains its own ID, notice, and revision history. Translations MUST follow Hypatia's mirrored-tree and source-reference rules.

## Required content

The entrypoint MUST include these sections in order. Missing personal information or unresolved choices MUST remain TBD while drafting.

| Section | Required content |
| --- | --- |
| **Summary** | Intended recipient, purpose, drafting language, and readiness. |
| **Copyright and licence** | Shared notice and relative link to the root licence. |
| **Letter** | Complete letter text, separated from authoring notes. |
| **Sources and open questions** | Personal input, travel-plan references, unresolved facts, and official consular instructions with check dates when available. |
| **Publication** | Required PDF, language, generation and review status, and format questions under PUBLICATION. |
| **Revisions** | Shared numbered revision history. |

## Letter content and consistency

The letter MUST identify the applicant, intended recipient, and date, and include a salutation, introduction, personal motivations for Japan and the Working Holiday stay, a concise explanation of intended experiences, and a closing with the applicant's name. Any required signature MUST follow verified consular instructions.

The letter MUST use the applicant's stated motivations and circumstances. Personal history, qualifications, commitments, and intentions MUST NOT be invented. Unconfirmed details MUST remain unresolved in the draft; a submission-ready letter MUST contain no drafting placeholders.

Travel periods, destinations, activities, and any financial figures mentioned MUST agree with the travel plan and chapter sources. Approximate plans MUST NOT be presented as confirmed bookings. Any EUR/JPY conversions MUST use **€1 = ¥160**. Converted EUR amounts MUST be displayed rounded to the nearest €10, with exact halfway values rounded away from zero (for example, €625 becomes €630). Calculations MUST retain unrounded values and round each displayed total or range endpoint only after calculation; displayed rounded line items may therefore differ from the rounded total. The letter SHOULD remain concise and personal; it MAY summarize the itinerary rather than repeat the chapter recap.

## Publication and maintenance

The letter MUST be generated as the PDF registered in [PUBLICATION](../PUBLICATION.md#consular-cover-letter-pdf). Only the **Letter** content and its presentation elements belong in that output; source metadata, internal notes, revision tables, and publication records MUST NOT be included as letter text.

Submission language, length, layout, required fields, and signature requirements MUST be verified against the responsible consulate's current official instructions before readiness is claimed. No particular language, page count, or layout is established by this draft. An additional submission-language source MUST follow Hypatia's translation rules and remain consistent with the canonical English source.

Changes to the letter, its translation, relevant travel-plan facts, or consular requirements MUST trigger review and mark affected PDFs stale. Review MUST check factual accuracy with the applicant, travel-plan consistency, language, completeness, and the rendered output. Generation records and approval follow PUBLICATION and Hypatia governance.

## Reusable model

The [cover letter model](../models/cover-letter.md) provides a copyable template and authoring guidance. It adds no requirements to this standard.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial draft cover-letter category for personal motivations, travel-plan consistency, and consular PDF publication, with a reusable model; EUR displays rounded to the nearest €10. |
