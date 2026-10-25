---
id: model-whv-chapter
standard_revision: 1
---

# WHV chapter model

This model supports the [chapter standard](../categories/chapters.md), based on the Hypatia dependencies in the [standards entrypoint](../README.md).

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Using this model

Copy the template to `docs/internal/chapters/chapter-NN-subject.md`. Replace the chapter number, subject, title, and placeholders with known information, keeping the filename stem and document ID aligned. The template follows revision 1 of the chapter category; the model itself follows revision 1 of the shared documentation standard.

The category also allows `docs/internal/chapters/chapter-NN-subject/README.md`. For that layout, adjust relative links: the root licence is `../../../../LICENCE` and the travel plan is `../../travel-plan/README.md`. The template below assumes the standalone-file layout.

Keep the required sections in their prescribed order. Mark unknown information TBD and explain why any inapplicable content does not apply. Use the accommodation table for successive stays. In chapters covering multiple cities, repeat the city subsection under Activities for each city; work and sightseeing can then be described separately within each. For a single-city chapter, the city heading may be omitted.

For the first chapter, Arrival describes the initial journey to Japan. For the last chapter, Departure and connection describes the return journey to Strasbourg. Keep transport descriptions in Transportation and their fare calculations in Budget.

Itemise costs under the three Budget subsections and account for food, other expenses, and contingency as well. Distinguish allowances, supplier quotes, and booked prices. Keep deposits separate from expenditure, count each cost once, and leave the chapter recap table at the end of Budget. Replace the template's calculation guidance with the actual calculation or an explicit TBD.

Review dates, accommodation coverage, connections, activities, calculations, and shared costs against the category. Keep the preparation list and sources current, and update affected adjacent chapters and the travel-plan recap when plans change. The model supplies no actual dates, destinations, prices, or reservations and adds no requirements beyond the category.

## Chapter template

```markdown
---
id: chapter-01-subject
standard_revision: 1
---

# Chapter 01 — Subject

## Summary

Purpose: TBD. Intended outcome: TBD.

Start date: TBD. End date: TBD. Duration: TBD; state the counting convention.

Part of the [travel plan](../travel-plan/README.md).

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Expected stay

| Arrival date | Departure date | Location | Accommodation type | Property / provider | Nights |
| --- | --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD | TBD |

Relevant housing preferences: TBD.

Accommodation gaps, overlaps, and nights spent travelling: TBD.

## Transportation

### Arrival

Previous chapter: TBD; link or identify this as the first chapter.

| Origin | Destination | Intended date / window | Mode | Preferences / constraints |
| --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD |

### Local movement

| Route / movement | Mode / pass | Intended date / period | Preferences / constraints |
| --- | --- | --- | --- |
| TBD | TBD | TBD | TBD |

### Departure and connection

Next chapter: TBD; link or identify this as the final chapter.

| Origin | Destination | Intended date / window | Mode | Preferences / constraints |
| --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD |

Connection to adjacent chapters and accommodation during overnight journeys: TBD.

## Activities

### TBD city

#### Sightseeing

| Activity | Intended date / period | Notes |
| --- | --- | --- |
| TBD | TBD | TBD |

#### Work

| Activity | Intended period / schedule | Notes |
| --- | --- | --- |
| TBD | TBD | TBD |

#### Other activities

TBD.

## Budget

Fixed planning exchange rate: **€1 = ¥160**. Displayed EUR amounts SHOULD use two or three significant digits, according to the precision appropriate to the estimate. Retain unrounded values for calculations and round only displayed amounts and totals.

Unknown amounts remain TBD. Identify incomplete subtotals as partial and list the missing costs.

### Expected stay

| Expense / stay | Calculation basis | JPY | EUR | Price basis / source |
| --- | --- | --- | --- | --- |
| Accommodation | TBD nights × TBD nightly rate, or TBD monthly billing basis | TBD | TBD | TBD |
| Accommodation fees | TBD | TBD | TBD | TBD |

### Transportation

Inbound transfer cost owned by the previous chapter and excluded here: TBD; link to its budget. For the first chapter, include the initial journey to Japan here instead.

This chapter budgets its outbound transfer to the next chapter. For the final chapter, include the return journey to Strasbourg.

| Expense / journey | Calculation basis | JPY | EUR | Price basis / source |
| --- | --- | --- | --- | --- |
| Local movement and transfers between bases | TBD | TBD | TBD | TBD |
| Outbound transfer / final return | TBD | TBD | TBD | TBD |
| Initial journey, if this is the first chapter | TBD | TBD | TBD | TBD |

### Activities

| City / activity | Calculation basis | JPY | EUR | Price basis / source |
| --- | --- | --- | --- | --- |
| TBD | TBD | TBD | TBD | TBD |

### Food and other expenses

| Expense | Calculation basis | JPY | EUR | Price basis / source |
| --- | --- | --- | --- | --- |
| Food | TBD days × TBD daily allowance, or TBD monthly allowance | TBD | TBD | TBD |
| Other expenses | TBD | TBD | TBD | TBD |

### Contingency

| Expense | Calculation basis | JPY | EUR | Price basis / source |
| --- | --- | --- | --- | --- |
| Contingency | TBD | TBD | TBD | TBD |

Shared costs or costs covered by an allowance or pass: TBD; identify where each is counted and exclude duplicates.

Refundable deposits: TBD; record separately from expenditure. Cash-needed calculation: TBD; include refundable deposits.

### Chapter recap

| Category / cash requirement | JPY | EUR | Coverage / calculation |
| --- | --- | --- | --- |
| Expected stay | TBD | TBD | TBD |
| Transportation | TBD | TBD | TBD |
| Activities | TBD | TBD | TBD |
| Food and other expenses | TBD | TBD | TBD |
| Contingency | TBD | TBD | TBD |
| **Planned expenditure total** | **TBD** | **TBD** | Sum of expenditure rows before rounding; remains TBD if costs are missing |
| Known partial subtotal, if the total is incomplete | TBD | TBD | TBD; identify the missing costs |
| Refundable deposits, excluded from expenditure | TBD | TBD | TBD |
| **Cash needed** | **TBD** | **TBD** | TBD; include expenditure and refundable deposits without counting the partial subtotal again |

## Preparation and open decisions

| Remaining action / open decision | Target date / booking window / deadline | Dependencies | State |
| --- | --- | --- | --- |
| Select or research missing activities | TBD | TBD | TBD |
| Arrange accommodation reservations | TBD | TBD | TBD |
| Arrange transportation reservations | TBD | TBD | TBD |
| Arrange activity reservations | TBD | TBD | TBD |
| Complete missing budget estimates | TBD | TBD | TBD |
| Complete practical arrangements and resolve other decisions | TBD | TBD | TBD |

## Sources and assumptions

| Item | Source / evidence | Checked on | Assumption / unresolved detail |
| --- | --- | --- | --- |
| TBD | TBD | TBD | TBD |

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | YYYY-MM-DD | Akane SHIMOKA | Initial draft chapter. |
```

## Revisions

| Revision | Date       | Author        | Description                                                                                                                           |
| -------- | ---------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 1        | 2026-10-19 | Akane SHIMOKA | Initial model. 2026-10-25: Rebuilt from the current chapter category, including section order, accommodation periods, city activities, itemised budget subsections, significant-digit EUR displays, chapter recap, and outstanding preparation. |
