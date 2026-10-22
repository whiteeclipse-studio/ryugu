---
id: std-whv-chapters
standard_revision: 1
---

# WHV chapter standard
## Purpose and scope

A chapter describes a bounded period of the Working Holiday stay: where to be, what to arrange or experience, how much to budget, and how to reach and leave it. Chapters divide the trip into manageable planning units. A chapter may cover one base, several destinations, or a purpose such as arrival, settling in, work, or exploration.

This draft category extends the Hypatia shared documentation and governance standards bound in the [Ryugu standards entrypoint](../README.md). Their mandatory requirements continue to apply; review and formal adoption remain pending.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Requirement terminology

Uppercase requirement keywords follow IETF **BCP 14**, as defined by [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and clarified by [RFC 8174](https://www.rfc-editor.org/rfc/rfc8174). Their BCP 14 meanings apply only when written entirely in uppercase; lowercase forms retain their ordinary English meanings.

## Location and identification

Each chapter MUST reside under `docs/internal/planning/chapters/<id>/`, with a main `README.md` as its entrypoint. The directory name MUST equal the entrypoint's project-unique lowercase kebab-case ID in the form `chapter-NN-subject`, such as `chapter-01-tokyo`. `NN` MUST be a zero-padded chronological sequence starting at `01`, so folder sorting matches the itinerary. All chapter numbers MUST use the same width; expand that width if needed.

Ryugu chapter identifiers encode chronological order. Inserting or reordering chapters MUST update affected numbers, matching directory names, all links, and any ID-prefixed assets together. Other changes SHOULD preserve identifiers unless the user requests a rename.

Entry files MUST declare `standard_revision: 1` when following revision 1 of this category. Supporting pages inherit the entry pin and MUST link back to the chapter entrypoint. Each authored page retains its own ID, copyright notice, and final revision history under Hypatia's shared rules. Assets follow Hypatia's shared placement and naming rules.

## Required content

The entrypoint MUST contain these sections in order. Details MAY be split into linked supporting pages; the entrypoint MUST summarize the date range, expected stay, budget total, adjacent chapters, and open decisions. Unknown content MUST be marked TBD. Inapplicable content MUST state that it does not apply and why.

| Section | Required content |
| --- | --- |
| **Summary** | Purpose, intended outcome, and overall planning certainty. |
| **Copyright and licence** | Shared notice and relative link to the root licence. |
| **Dates and continuity** | Start, end, duration, boundary convention, previous and next chapters, gaps and overlaps. |
| **Expected stay** | Locations, bases, housing, sightseeing, activities, everyday needs, and work, study, or administrative expectations. |
| **Budget** | Planned expenditure, assumptions, contingency, cash needed, and transfer allocation. |
| **Transportation** | Arrival, local movement, and departure toward the next chapter or final return. |
| **Preparation and open decisions** | Actions, dependencies, deadlines, and unresolved choices. |
| **Sources and assumptions** | Evidence and assumptions behind dates, costs, housing, activities, and routes. |
| **Revisions** | Shared numbered revision history. |

## Dates and continuity

Each chapter MUST give start and end dates using `YYYY-MM-DD`, or explicitly identify tentative windows or TBD boundaries. Dates MUST distinguish intended plans from confirmed reservations. Duration MUST state its units and counting convention; housing nights MUST be identified separately where they differ from calendar days.

The default interval is arrival-inclusive and departure-exclusive: its end is the next chapter's start. A different convention MAY be used if stated explicitly. Transfer times MUST identify local time zones when relevant, including overnight travel and international date changes.

Each chapter MUST link to its predecessor and successor, or state first chapter, final chapter, or next chapter TBD. Gaps, overlaps, and overnight transfers MUST be explained. Transition days MAY contain activities in both chapters, but time and housing assumptions MUST remain consistent.

When chapters are created, the overall travel plan MUST maintain a chronological index linking their entrypoints and summarizing dates, bases, certainty, and budget totals. Chapter data remains authoritative in each chapter; the travel plan maintains a derived recap under the [travel plan standard](./travel-plan.md).

## Expected stay

Each chapter MUST describe locations and bases with their purpose; housing type, area, duration, and booking certainty; priority and optional sightseeing or activities; everyday needs; and work, study, or administrative expectations. Seasonal, booking, and scheduling constraints MUST be recorded where relevant. Unresolved choices MAY remain TBD; a complete daily itinerary is not required.

Individual dates, bookings, costs, activities, and decisions MUST use the certainty labels **Confirmed**, **Tentative**, **Ideas**, or **TBD**. Confirmed items MUST identify supporting evidence. Overall chapter certainty MUST NOT imply that every item is confirmed. Confirmation of a fact or reservation does not establish document approval.

## Budget

Each chapter MUST state its planned expenditure total or mark it TBD. A partial subtotal MUST identify unknown amounts and MUST NOT be presented as a complete total. Housing and fees, food and everyday expenses, local transport, sightseeing and activities, owned inter-chapter transfers, other costs, and contingency MUST each be included or explicitly marked inapplicable or TBD.

Amounts MUST identify their currency. Estimates MUST state a calculation basis, such as nights × nightly rate. All EUR/JPY conversions MUST use the fixed planning exchange rate **€1 = ¥160**: multiply EUR amounts by 160 to obtain JPY, and divide JPY amounts by 160 to obtain EUR. This is a project planning assumption, not a live market rate. Mixed currencies MUST NOT be added without conversion to a stated reporting currency using this rate. Converted EUR amounts MUST be displayed rounded to the nearest €10, with exact halfway values rounded away from zero (for example, €625 becomes €630). Calculations MUST retain unrounded values and round each displayed total or range endpoint only after calculation; displayed rounded line items may therefore differ from the rounded total.

Refundable deposits MUST be distinguished from expenditure and included in cash-needed estimates. Expected income MAY be tracked separately but MUST NOT silently reduce expenditure. Trip-wide costs and emergency reserves MUST be linked to the overall budget recap and counted once; any chapter allocation MUST be explicit. Actual spending MAY be tracked separately from estimates.

## Transportation and cost ownership

Each chapter MUST describe inbound travel, local movement, and outbound travel. Routes MUST identify origin, destination, intended date or window, mode, cost and currency, booking certainty, and relevant luggage or timing constraints. Unknown details MUST remain TBD.

The departing chapter MUST own the authoritative record and budget allocation for its transfer to the next chapter. The receiving chapter MUST link to that record and exclude the same cost from its total. The first chapter MUST own the initial journey to the trip; the final chapter MUST own the return journey. If the next chapter is TBD, the departing chapter MUST still record the outbound transfer as unresolved.

A single booking covering multiple transfers MUST have one authoritative cost record. Linked chapters MUST either exclude that cost or state allocations whose sum matches the record. Transport and housing during an overnight transfer MUST be allocated explicitly to avoid missing or duplicated costs and nights.

## Preparation, review, and maintenance

Preparation actions MUST identify what remains to be arranged, with known deadlines and dependencies or explicit TBD values. Sources MUST distinguish verified facts, estimates, and assumptions, with check dates where relevant. Sensitive booking evidence MAY remain in an appropriate private source without exposing credentials or unnecessary personal information.

Changes to dates, housing, routes, or budgets MUST trigger review of adjacent boundaries, transfer ownership, the itinerary index, and the overall budget recap. Review MUST check continuity, housing nights, arithmetic, unknown amounts, and single counting of shared costs. Planned checks MUST be distinguished from completed checks.

Review and approval follow Hypatia governance. Agents MAY prepare documents and record explicit owner decisions but MUST NOT approve them. All uncommitted changes to a document share its pending revision number under the [Ryugu authoring instructions](../../AGENTS.md).

## Publication

All chapter data MUST be recapped in the travel plan and in a PDF generated following the format required by the applicable consulate. Sources, required output files, official-format verification, and generation checks are defined in [PUBLICATION](../PUBLICATION.md). Generated recaps MUST preserve chapter values and uncertainty; changes to a chapter MUST trigger review of the travel plan and any affected PDF.

## Reusable model

The [chapter model](../models/chapter.md) provides a starting point. It adds no requirements and does not supply actual dates, destinations, prices, reservations, or approval.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial draft category for numbered WHV chapters, budgets using €1 = ¥160, connecting transport, travel plan consolidation, and consular PDF publication; EUR displays rounded to the nearest €10. |
