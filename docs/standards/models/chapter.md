---
id: model-whv-chapter
standard_revision: 1
---

# WHV chapter model

This model supports the [chapter standard](../categories/chapters.md), based on the Hypatia dependencies in the [standards entrypoint](../README.md). Requirements belong to those standards; this model supplies a copyable structure.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Using this model

Copy the template to `docs/internal/planning/chapters/chapter-01-subject/README.md`. Replace its sequence number, subject, and title, and fill in known information. Use the same zero-padded chronological number in the folder name and document ID. When inserting or reordering chapters, renumber affected folders and IDs and update their links and any ID-prefixed assets together. Keep unresolved choices TBD and add the chapter to the travel plan's chronological index when created. Use Confirmed, Tentative, Ideas, and TBD for individual planning items.

The template's entry pin selects revision 1 of the chapter standard. The model itself follows the shared standard. Supporting pages inherit the chapter pin, retain their own IDs, notices, and revision tables, and link back to the chapter. Adjust relative links if files move. Document approval remains pending unless an explicit owner decision is recorded.

## Chapter template

```markdown
---
id: chapter-01-subject
standard_revision: 1
---

# Chapter — Subject

## Summary

Purpose and intended outcome: TBD.

Overall planning certainty: TBD. Document review and approval: pending.

Travel plan / itinerary index: TBD; link when created.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../../../LICENCE).

## Dates and continuity

| Item | Plan | Certainty / evidence |
| --- | --- | --- |
| Start / arrival | TBD | TBD |
| End / departure | TBD | TBD |
| Duration | TBD days; arrival-inclusive, departure-exclusive | TBD |
| Housing nights | TBD | TBD |
| Previous chapter | TBD; link or identify first chapter | TBD |
| Next chapter | TBD; link or identify final chapter | TBD |

Gaps, overlaps, overnight travel, and time zones: TBD.

## Expected stay

| Area | Expectation | Certainty / constraints |
| --- | --- | --- |
| Locations and bases | TBD; include purpose | TBD |
| Housing | TBD type, area, nights, and alternatives | TBD |
| Priority sightseeing and activities | TBD | TBD |
| Optional activities | TBD | Ideas |
| Everyday needs | TBD | TBD |
| Work or study | TBD | TBD |
| Administrative tasks | TBD | TBD |

## Budget

Reporting currency: TBD. Fixed planning exchange rate: **€1 = ¥160** (EUR × 160 = JPY; JPY ÷ 160 = EUR). Display converted EUR amounts to the nearest €10, rounding halfway values away from zero; retain unrounded values for calculations and round each total or range endpoint only at the end.

| Expense | Calculation / basis | Planned amount and currency | Certainty / source |
| --- | --- | --- | --- |
| Housing and fees | TBD nights × TBD rate; fees TBD | TBD | TBD |
| Food and everyday expenses | TBD days × TBD allowance | TBD | TBD |
| Local transport | TBD | TBD | TBD |
| Sightseeing and activities | TBD | TBD | TBD |
| Owned inter-chapter transfers | Transportation records below | TBD | TBD |
| Other costs | TBD | TBD | TBD |
| Contingency | TBD basis | TBD | TBD |

Planned expenditure total: TBD. Known subtotal, if useful: TBD; unknown amounts: TBD.

Refundable deposits and payment timing: TBD. Total cash needed including deposits: TBD.

Expected income, tracked separately: TBD.

Trip-wide costs and emergency reserve: TBD; link to overall recap and explain allocation or exclusion.

Transfer costs owned elsewhere and excluded here: TBD; link to owning record.

## Transportation

### Arrival

Previous chapter's authoritative outbound record: TBD; link and exclude its cost from this budget. For the first chapter, record and budget the initial journey here.

Origin, destination, date or window, time zones, mode, cost and currency, booking certainty, evidence, luggage, and timing constraints: TBD.

### Local movement

Routes or passes, dates, costs, certainty, evidence, luggage, and timing constraints: TBD.

### Departure and connection

This chapter owns the transfer to the next chapter, or the final return journey.

Origin, destination, next chapter / final return, date or window, time zones, mode, cost and currency, booking certainty, evidence, luggage, and timing constraints: TBD.

Overnight housing and shared-booking cost allocation: TBD.

## Preparation and open decisions

| Action or decision | Deadline | Dependency | State |
| --- | --- | --- | --- |
| TBD | TBD | TBD | TBD |

Review of dates, housing nights, arithmetic, transfer allocation, and itinerary recap: pending.

## Sources and assumptions

| Item | Source / evidence | Checked on | Assumption or limitation |
| --- | --- | --- | --- |
| TBD | TBD | TBD | TBD |

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | YYYY-MM-DD | Akane SHIMOKA | Initial draft chapter. |
```

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial reusable model with chronologically numbered chapter identifiers and the fixed €1 = ¥160 planning rate; EUR displays rounded to the nearest €10. |
