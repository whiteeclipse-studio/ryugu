---
id: model-whv-travel-plan
standard_revision: 1
---

# WHV travel plan model

This model supports the [travel plan standard](../categories/travel-plan.md) and [PUBLICATION](../PUBLICATION.md), based on the Hypatia dependencies in the [standards entrypoint](../README.md). Requirements belong to those standards; this model provides authoring guidance and a copyable template.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Using this model

Use the template at `docs/internal/planning/README.md`. Update an existing source in place rather than replacing its decisions or revision history. Replace the subject ID and title, date and other placeholders, and guidance with actual content. Retain unresolved content as TBD during drafting and explicitly explain inapplicable items.

The template pin selects revision 1 of its category standard. This model itself follows the shared documentation standard, revision 1. Supporting pages inherit the entry pin, retain their own IDs, notices, and revision tables, and link back to the entrypoint. Adjust relative links if files move. Translations follow Hypatia's mirrored-tree and source-reference rules. These templates supply no actual personal statements, prices, reservations, or consular format; review and approval remain pending.

Populate recaps from the authoritative chapters, preserving all substantive values and certainty labels. Repeat the indicated structures for every chapter and include all supporting source IDs and revisions. Changes belong in owning chapters before their recaps; trip-wide values are identified separately.

## Template

```markdown
---
id: travel-plan-subject
standard_revision: 1
---

# WHV travel plan — Subject

## Summary

Overall travel period: TBD. Purpose: TBD. Planning certainty: TBD.

Completeness: TBD; identify missing chapters and values. Review and approval: pending.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Chronological chapter index

Use one linked row per chapter in chronological order. Preserve approximate dates and certainty labels. Duration uses arrival-inclusive, departure-exclusive boundaries unless stated otherwise.

| Chapter ID and linked title | Date range | Duration | Locations | Certainty | Expenditure total and currency |
| --- | --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD | TBD |

## Unplanned intervals

Gaps, overlaps, approximate boundaries, missing chapters, initial journey, and final return: TBD.

## Expected stay recap

Repeat the following for each chapter, linking its authoritative source and retaining every distinct value and material qualification. Add rows or linked supporting pages as needed.

Chapter ID and source: TBD.

| Area | Recap | Certainty / constraints / source |
| --- | --- | --- |
| Bases and purpose | TBD | TBD |
| Housing type, area, nights, and alternatives | TBD | TBD |
| Priority sightseeing and activities | TBD | TBD |
| Optional activities | TBD | TBD |
| Everyday needs | TBD | TBD |
| Work or study | TBD | TBD |
| Administrative expectations | TBD | TBD |

## Budget recap

Reporting currency: TBD. Fixed planning exchange rate: **€1 = ¥160** (EUR × 160 = JPY; JPY ÷ 160 = EUR). Display converted EUR amounts to the nearest €10, rounding halfway values away from zero; retain unrounded values for calculations and round each total or range endpoint only at the end.

Repeat these rows for each chapter with links to its budget. Keep source calculations, currencies, certainty, evidence, and missing inputs visible.

| Chapter / source | Expense category | Calculation / assumptions | Amount and currency | Certainty / evidence |
| --- | --- | --- | --- | --- |
| TBD | Housing and fees | TBD | TBD | TBD |
| TBD | Food and everyday expenses | TBD | TBD | TBD |
| TBD | Local transport | TBD | TBD | TBD |
| TBD | Sightseeing and activities | TBD | TBD | TBD |
| TBD | Owned inter-chapter transfers | TBD | TBD | TBD |
| TBD | Other costs | TBD | TBD | TBD |
| TBD | Contingency | TBD | TBD | TBD |

Per-chapter expenditure totals, partial subtotals, unknown inputs, refundable deposits, payment timing, cash needed, separately tracked expected income, and shared-cost allocations or exclusions: TBD; recap each chapter individually.

Category totals across chapters: TBD. Unallocated trip-wide expenditure: TBD. Emergency reserve: TBD. Shared costs already allocated to chapters and excluded from additional trip-wide expenditure: TBD.

Trip expenditure total: TBD. Known subtotal, if useful: TBD; missing inputs: TBD. Unknown amounts are not zero.

Total refundable deposits: TBD. Total cash needed: TBD; explain inclusion of expenditure, contingency, reserve, deposits, payment timing, and any separately tracked income.

## Transportation recap

Repeat for the initial journey, every chapter's local movement and departure, and final return. Link inbound transfers to their departing chapter's owning record; count each cost once.

| Journey / linked source | Origin and destination | Date or window / time zones | Mode | Cost and currency / owner | Certainty / evidence | Luggage, timing, overnight housing, and shared-booking constraints |
| --- | --- | --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD | TBD | TBD |

## Preparation and open decisions

Include every outstanding chapter action and decision, plus explicitly owned trip-wide items.

| Chapter / source or trip-wide item | Action or decision | Deadline | Dependency | State |
| --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD |

Recap review of continuity, housing nights, arithmetic, transfer ownership, and unknown values: pending.

## Publication

Required output: `whv-consular-programme`, at `public/documents/whv-programme.pdf`. See [PUBLICATION](../../standards/PUBLICATION.md#consular-chapter-recap-pdf).

State: not generated. Generation date: TBD. Source IDs, revisions, and recoverable snapshot: TBD; identify pending drafts explicitly.

Responsible consular office and jurisdiction: TBD. Official instructions and form URLs, verification dates, required language, fields, date/currency conventions, page or file limits, and signatures: TBD. Chapter-to-form mapping and any permitted supporting pages: TBD.

Completed checks and evidence: none recorded. Remaining issues: TBD. Official-format and rendered-PDF checks: pending. No submission readiness or approval is established.

## Sources and assumptions

| Chapter or supporting source ID | Document revision | Source link / snapshot | Checked on | Assumptions / limitations |
| --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD |

Shared assumptions, evidence references, and trip-wide source ownership: TBD. Source completeness and consistency review: pending.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | YYYY-MM-DD | Akane SHIMOKA | Initial draft travel plan recap. |
```

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial reusable travel plan model with category sections and publication tracking; EUR displays rounded to the nearest €10. |
