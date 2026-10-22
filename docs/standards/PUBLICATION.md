---
id: std-publication
standard_revision: 1
---

# Publication standard and output register
## Purpose and scope

This file is the authoritative register of all files Ryugu is required to produce. Each required output has its source, destination, format, prerequisites, and verification requirements recorded here. New required outputs are added to this register when their standards are defined.

This draft extends the Hypatia shared documentation and governance standards bound in the [standards entrypoint](./README.md). Generated files are derived outputs; authoritative authored sources remain under `docs`. Publication here means producing a deliverable; it does not authorize public hosting or submission to a consulate.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../LICENCE).

## Requirement terminology

Uppercase requirement keywords follow IETF **BCP 14**, as defined by [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and clarified by [RFC 8174](https://www.rfc-editor.org/rfc/rfc8174). Their BCP 14 meanings apply only when written entirely in uppercase.

## Required output register

| Output ID                | Required file, relative to the project root | Format                                | Authoritative sources                             |
| ------------------------ | ------------------------------------------- | ------------------------------------- | ------------------------------------------------- |
| `whv-consular-programme` | `public/documents/whv-programme.pdf`        | PDF in the applicable consular format | Consolidated recap and its traced chapter sources |
| `whv-consular-cover-letter` | `public/documents/whv-cover-letter.pdf` | PDF in the applicable consular format | Canonical cover-letter source and any verified submission-language translation |

### Consular chapter recap PDF

All chapter data MUST be recapped in a PDF following the format required by the consulate responsible for the application. The published recap MUST preserve the itinerary, budgets, certainty, and material qualifications represented in the travel plan, subject to the official form's fields and permitted supporting pages. Required information MUST NOT be silently dropped to fit a layout. Any conflict between complete coverage and the official format MUST be resolved and recorded before submission readiness is claimed.

Before implementing or finalizing the PDF format, the publication record MUST identify:

- The responsible embassy or consulate and application jurisdiction.
- The current official instructions and any required form or template, with direct source URLs and verification dates.
- Required language, fields, date and currency conventions, page or file limits, and signature requirements, where specified; unspecified details MUST be identified as such.
- How travel plan and chapter fields map to the required format, including any permitted continuation pages.

The responsible consular office, official sources, template, language, and layout requirements are currently TBD. No specific consular format has yet been verified. The fixed project planning rate remains **€1 = ¥160**; any incompatible official instruction MUST be recorded and resolved before the output is marked ready, rather than silently changing chapter assumptions.

### Consular cover letter PDF

The cover letter MUST be generated as `public/documents/whv-cover-letter.pdf` from the source defined in the [cover-letter category](./categories/cover-letter.md). The PDF MUST reproduce the letter content in the verified submission language, excluding internal metadata, notes, revision history, and publication records. The source letter has not yet been drafted; no PDF has been generated.

Before finalizing this output, the publication record MUST identify the responsible consular office, current official instructions with direct URLs and verification dates, and any specified language, length, layout, required fields, and signature requirements. Unspecified requirements MUST be identified as such. Those details are currently TBD; the filename above is Ryugu's output convention.

Verification MUST check the applicant's stated motivations and personal facts, travel-plan consistency, absence of unresolved placeholders, faithful translation where applicable, and conformity to verified official instructions. The rendered PDF MUST be inspected for legibility, clipping, pagination, and any required signature space.

### Generation and verification record

Each generated output MUST have a record in its source entrypoint's **Publication** section: the travel plan for the chapter recap PDF, and the cover-letter entrypoint for the letter PDF. The record MUST identify its output ID and path, generation date, source IDs and revisions, and a recoverable source snapshot. A fixed Git reference MAY supply that snapshot when available; pending uncommitted drafts MUST be identified explicitly and their source state preserved with the generation record.

The record MUST distinguish **not generated**, **draft**, **stale**, and **ready for submission**. A generated file MUST be marked stale when its source values or applicable format requirements change. It MUST be regenerated and rechecked before it is treated as current.

Verification MUST cover source completeness and exact agreement with source values. For itinerary and budget content, it MUST also cover date continuity, single counting of expenses and transfers, **€1 = ¥160** conversions with EUR displays rounded to the nearest €10 (halfway values away from zero, totals calculated before rounding), and preserved TBD or tentative labels. Each output MUST pass its specific checks above. The rendered PDF MUST also be inspected for clipping, legibility, pagination, and conformity to the verified official format. Incomplete content or unresolved mandatory form requirements MUST prevent a ready-for-submission designation.

Executed checks and remaining issues MUST be recorded separately from planned checks. Readiness does not establish owner approval, a booking, or evidence of submission. Review, approval, licensing, and access follow Hypatia governance.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial required-output register for the consular chapter recap and cover-letter PDFs, with generation and verification rules including EUR rounding to the nearest €10. |
