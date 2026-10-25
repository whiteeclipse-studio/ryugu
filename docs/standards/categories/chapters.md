---
id: std-whv-chapters
standard_revision: 1
---
# WHV chapter standard
## Purpose and scope

A chapter describes a bounded period of the Working Holiday stay: where to be, what to arrange or experience, how much to budget, and how to reach and leave it. Chapters divide the trip into manageable planning units. A chapter may cover one base, several destinations, or a purpose such as arrival, settling in, work, or exploration.

This draft category extends the Hypatia shared documentation and governance standards bound in the [Ryugu standards entrypoint](../README.md). Their mandatory requirements continue to apply.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Requirement terminology

Uppercase requirement keywords follow IETF **BCP 14**, as defined by [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and clarified by [RFC 8174](https://www.rfc-editor.org/rfc/rfc8174). Their BCP 14 meanings apply only when written entirely in uppercase; lowercase forms retain their ordinary English meanings.

## Location and identification

Each chapter's entrypoiny MUST be located at `docs/internal/chapters/<id>.md`, or at `docs/internal/chapters/<id>/README.md`. The filename stem MUST equal the document's project-unique lowercase kebab-case ID in the form `chapter-NN-subject`, such as `chapter-01-tokyo`. `NN` MUST be a zero-padded chronological sequence starting at `01`, so filename sorting matches the itinerary.

Ryugu chapter identifiers encode chronological order. Inserting or reordering chapters MUST update affected numbers, matching filenames, all links, and any ID-prefixed assets together. Other changes SHOULD preserve identifiers unless the user requests a rename.

## Required content

The chapter file MUST contain these sections in order and retain its planning details in that file. Unknown content MUST be marked TBD. Inapplicable content MUST state that it does not apply and why.

| Section                            | Required content                                                                         |
| ---------------------------------- | ---------------------------------------------------------------------------------------- |
| **Summary**                        | Purpose, start and end dates, and intended outcome.                                      |
| **Copyright and licence**          | Shared notice and relative link to the root licence.                                     |
| **Expected stay**                  | Accommodation periods and relevant housing preferences.                                  |
| **Transportation**                 | Arrival, local movement, and departure toward the next chapter or final return.          |
| **Activities**                     | Suite of activities scheduled during the chapter. Such as sightseeing, work, and others. |
| **Budget**                         | Cost subsections, calculation assumptions, contingency, cash needed, and a chapter recap table. |
| **Preparation and open decisions** | Actions, dependencies, deadlines, and unresolved choices.                                |
| **Sources and assumptions**        | Evidence and assumptions behind dates, costs, housing, activities, and routes.           |
| **Revisions**                      | Shared numbered revision history.                                                        |

### Expected stay

The Expected stay section MUST list the intended accommodation periods in chronological order. Each period MUST identify its location, accommodation type, and intended arrival and departure dates.

The property or accommodation provider SHOULD be named when known. Unresolved details MUST remain TBD.

The section SHOULD describe relevant housing preferences where appropriate, such as a private room, preferred neighbourhood, or required facilities.

Gaps or overlapping accommodation periods MUST be explained, including nights spent travelling.

### Transportation

The Transportation section MUST describe arrival, movement within the chapter, and departure toward the next chapter or final return. The first chapter MUST include the initial journey to Japan, and the last chapter MUST include the return trip back to Strasbourg.

Arrival, transfers between bases, and departure MUST identify the origin, destination, intended mode of transport, and intended date or travel window. Local movement MAY be summarised through the expected modes, routes, or passes rather than listing every journey.

Relevant transport preferences and constraints SHOULD be described where appropriate, such as luggage requirements, accessibility needs, or timing constraints.

Connections between chapters MUST be consistent with the adjacent chapters. Overnight journeys MUST be reconciled with the accommodation periods in Expected stay.

Transport costs and their calculations MUST be recorded in the Budget section.

### Activities

The Activities section MUST describe the activities, planned or proposed, during the chapter, such as sightseeing, work, or other commitments.

When a chapter covers multiple cities, its Activities section MUST use a subsection for each city. Activities in a city MUST appear within that city's subsection.

The section SHOULD distinguish work from sightseeing activities through separate subheadings or clearly labelled groups. In chapters covering multiple cities, this distinction SHOULD be made within each city's subsection where appropriate.

### Budget

The Budget section MUST include separate subsections titled **Expected stay**, **Transportation**, and **Activities**. Each subsection MUST itemise the costs associated with its corresponding chapter section. Additional subsections MAY be used for other expenses.

The budget MUST account for accommodation, food, transportation, activities, other expenses, and contingency. Each expense MUST be counted once, including costs shared across activities or covered by an allowance or pass.

Each estimate MUST identify its currency and calculation basis, such as nights multiplied by a nightly rate. Allowances, supplier quotes, and booked prices MUST be distinguished. Unknown costs MUST remain TBD; incomplete subtotals MUST be labelled as partial.

The departing chapter MUST budget the transfer to the next chapter; the receiving chapter MUST exclude that same cost. The first chapter MUST budget the initial journey to Japan, and the last chapter MUST budget the return journey to Strasbourg.

Refundable deposits MUST be distinguished from expenditure and included when calculating cash needed.

All EUR/JPY conversions MUST use the fixed planning exchange rate **€1 = ¥160**. Displayed EUR amounts SHOULD use two or three significant digits, according to the precision appropriate to the estimate. Calculations MUST retain unrounded values; rounding MUST apply only to displayed amounts and totals. For example, ¥2,600 may be displayed as €16, and ¥267,000 as €1,670.

The Budget section MUST end with a recap table covering the entire chapter. The table MUST show each cost subsection's subtotal, any remaining expense categories and contingency, and the chapter's planned expenditure total, distinguishing refundable deposits and cash needed separately. Recap amounts MUST reconcile with the detailed calculations before rounding. If unresolved costs prevent a complete total, the table MUST identify them and label any known subtotal as partial.

### Preparation and open decisions

The Preparation and open decisions section MUST list all remaining actions and unresolved decisions needed to prepare for and carry out the chapter. These include, but are not limited to, activities still to be selected or researched, accommodation, transportation, or activity reservations still to be made, missing budget estimates, and outstanding practical arrangements.

Each item MUST explain what remains to be done and when it should be done, including any applicable booking window or deadline. Unknown timing MUST be marked TBD. Dependencies affecting when an action can be completed SHOULD be identified.

## Preparation, review, and maintenance

Chapters MUST be reviewed for consistency between dates, accommodation periods, transportation, activities, and budgets. Reviews MUST check for unexplained gaps or overlaps, missing costs, calculation errors, and duplicated expenditure.

Changes to dates, locations, accommodation, transportation, activities, or costs MUST trigger an update of the affected content, including adjacent chapters and the travel-plan recap where applicable.

Preparation and open decisions, sources, and assumptions MUST be kept current as planning progresses. Chapters SHOULD be reviewed again after significant changes and before the chapter begins.

## Publication

Each chapter MUST be represented in the travel-plan recap. The recap MUST remain consistent with the current chapter content.

## Reusable model

The [chapter model](../models/chapter.md) provides a starting point. It adds no requirements and does not supply actual dates, destinations, prices, reservations, or approval.

## Revisions

| Revision | Date       | Author        | Description   |
| -------- | ---------- | ------------- | ------------- |
| 1        | 2026-10-25 | Akane SHIMOKA | Initial draft |
