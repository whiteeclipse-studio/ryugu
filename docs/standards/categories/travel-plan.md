---
id: std-whv-travel-plan
standard_revision: 1
---
# WHV travel plan standard
## Purpose and scope

The travel plan recaps the complete Working Holiday plan from the chapters in one place. It brings together dates, locations, housing, activities, budgets, transportation, preparation, and unresolved decisions without becoming a separate source of chapter decisions.

This draft category extends the Hypatia shared documentation and governance standards bound in the [standards entrypoint](../README.md).

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Requirement terminology

Uppercase requirement keywords follow IETF **BCP 14**, as defined by [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and clarified by [RFC 8174](https://www.rfc-editor.org/rfc/rfc8174). Their BCP 14 meanings apply only when written entirely in uppercase.

## Location and identification

The single travel plan entrypoint MUST be `docs/internal/travel-plan/README.md`. Additional files MAY be added in the `docs/internal/travel-plan` directory.

## Required content

The travel plan MUST contain the following sections in order. Unknown content MUST be marked TBD. Inapplicable content MUST state that it does not apply and why.

| Section | Required content |
| --- | --- |
| **Summary** | Overall travel period, purpose, and main planning intentions. |
| **Copyright and licence** | Shared notice and link to the root licence. |
| **Chronological chapter index** | Chapters in order, with links, dates, durations, and locations. |
| **Budget allowance** | Expected income, savings available for allocation to the trip, and trip-wide and monthly spending allowances with their calculation basis. |
| **Planning recap** | Consolidated accommodation, transportation, main activities, and monthly expenditure estimates. |
| **Revisions** | Shared numbered revision history. |

### Chronological Chapter Index

The Chronological Chapter Index section MUST list every chapter in a table, in chronological order. Each row MUST include the chapter number and title linked to its source document, its start and end dates, its duration, and its main locations.

The index MUST remain consistent with the chapter sources, preserving tentative dates and marking unknown values TBD. Any gaps or overlaps between chapters MUST be identified.

### Budget allowance

The Budget allowance section MUST include both the expected income during the travel period and the total amount of savings that may be allocated to the trip. Income and savings MUST be presented separately.

The section MUST state the trip-wide and monthly spending allowances and explain how they are supported by the expected income and available savings. These allowances MUST be distinguished from the expected expenditure presented in Planning recap.

### Planning recap

The Planning recap section MUST provide simple summaries covering the entire Working Holiday stay through the following subsections:

- **Expected stay**: a chronological recap of all planned accommodation periods, with their locations, accommodation types, and intended arrival and departure dates.
- **Transportation**: a recap of all planned transportation, including the initial journey to Japan, travel between chapters and bases, local movement, and the final return journey. The recap MUST summarise routes, modes, and intended dates or travel windows where applicable.
- **Main activities**: a recap of the major activities planned throughout the WHV, including sightseeing and work, with their relevant locations and intended periods where known.
- **Month-by-month budget**

The Month-by-month budget MUST present expected expenditure derived from the chapters so it can be compared with the spending allowances.

## Source ownership

Chapter documents MUST remain authoritative for their dates, accommodation, transportation, activities, and expenditure estimates. The travel plan MUST summarise that information consistently and link to its source chapters. Changes MUST be made in the owning source before updating the recap.

The travel plan MUST identify the financial sources supporting its expected income, available savings, and spending allowances, including any supporting spreadsheet.

Published PDFs MUST be derived from the travel plan and its linked sources. They MUST be regenerated when changes affect their content.

## Publication

The travel plan MUST produce a PDF using the [official programme form supplied by the Japanese embassy in Paris](https://www.fr.emb-japan.go.jp/files/100824215.pdf), as linked from the embassy's [Working Holiday instructions](https://www.fr.emb-japan.go.jp/itpr_fr/v0002b.html). The PDF MUST retain the form's required fields and table structure, using additional pages as necessary.

The PDF MUST cover the entire stay and include:

- Applicant identity fields.
- Travel periods, cities or regions, accommodation types, and expected monthly rent.
- Detailed planned activities and expenditure, including daily living, transportation, and meals.
- Where applicable, weekly study hours and costs, and weekly working hours, expected earnings, and job-search plans.

The PDF SHOULD include a consolidated budget recap at the end. Before submission, it MUST be checked for completeness, consistency with its sources, legibility, and conformity with the embassy's current form and instructions. Missing required information MUST be resolved before the PDF is considered ready for submission.

Documentation uploads, including publication of the generated PDF, MUST follow Hypatia's documentation upload rules. The exact generation and upload pipeline is outside the scope of this document.

## Reusable model

No model is provided for this category.

## Revisions

| Revision | Date       | Author        | Description   |
| -------- | ---------- | ------------- | ------------- |
| 1        | 2026-10-25 | Akane SHIMOKA | Initial draft |
