---
id: std-whv-travel-plan
standard_revision: 1
---

# WHV travel plan standard
## Purpose and scope

The travel plan recaps the complete Working Holiday plan from the chapters in one place. It brings together dates, locations, housing, activities, budgets, transportation, preparation, and unresolved decisions without becoming a separate source of chapter decisions.

This draft category extends the Hypatia shared documentation and governance standards bound in the [standards entrypoint](../README.md). It uses revision 1 of the [chapter standard](./chapters.md) and revision 1 of the [publication standard](../PUBLICATION.md). Review and formal adoption remain pending.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Requirement terminology

Uppercase requirement keywords follow IETF **BCP 14**, as defined by [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and clarified by [RFC 8174](https://www.rfc-editor.org/rfc/rfc8174). Their BCP 14 meanings apply only when written entirely in uppercase.

## Location and identification

The single travel plan entrypoint MUST be `docs/internal/planning/README.md`. It MUST have a project-unique ID and declare `standard_revision: 1` when following revision 1 of this category. This placement governs that entrypoint and its supporting pages, excluding the independently governed `chapters/` subtree. Supporting pages MUST link back to the travel plan and inherit its pin; each retains its own ID, notice, and revision history.

## Required content

The travel plan MUST include the following sections in order. Detail MAY reside in linked supporting pages, but the entrypoint MUST retain its chapter index, trip expenditure total or explicit TBD, unplanned intervals, and publication status.

| Section                            | Required recap                                                                                                                                    |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Summary**                        | Overall travel period, purpose, certainty, and completeness.                                                                                      |
| **Copyright and licence**          | Shared notice and link to the root licence.                                                                                                       |
| **Chronological chapter index**    | Every chapter, linked by ID, with title, date range, duration, locations, certainty, and expenditure total.                                       |
| **Unplanned intervals**            | Gaps, overlaps, approximate boundaries, and missing chapters, including the initial and return journeys.                                          |
| **Expected stay recap**            | Per-chapter bases, housing and nights, priority and optional activities, everyday needs, work or study, and administrative expectations.          |
| **Budget recap**                   | Per-chapter expense categories, totals, deposits, cash needed, separately tracked income, contingency, trip-wide costs, and emergency reserve.    |
| **Transportation recap**           | Initial journey, local movement, inter-chapter transfers, and final return, with routes, windows, modes, certainty, constraints, and cost owners. |
| **Preparation and open decisions** | Outstanding chapter and trip-wide actions, deadlines, dependencies, and review state.                                                             |
| **Sources**                        | Chapter source IDs and revisions.                                                                                                                 |
| **Revisions**                      | Shared numbered revision history.                                                                                                                 |

## Completeness and source ownership

All substantive chapter data MUST be represented in the travel plan recap, including TBD values, certainty labels, assumptions, and constraints. Wording MAY be condensed, but distinct values and material qualifications MUST NOT be silently omitted. Each chapter's recap MUST link to its source; detailed evidence MAY be referenced rather than copied. The source coverage record MUST identify each chapter's ID and document revision, including supporting pages used.

Chapters remain authoritative for their own values. Corrections to chapter data MUST be made in the owning chapter before updating the travel plan and publication outputs. The travel plan MAY own trip-wide assumptions, costs, reserves, and actions, provided they are explicitly distinguished from chapter data. Recap maintenance MAY be manual or automated; this standard does not establish an implemented generator.

Every chapter MUST appear in chronological order. Missing dates, approximate boundaries, unplanned intervals, and unconfirmed bookings MUST remain visible. An unknown amount MUST NOT be treated as zero; a known subtotal MUST NOT be labeled a complete trip total.

## Budget consolidation

All EUR/JPY conversions MUST use **€1 = ¥160**. The travel plan MUST state the reporting currency. Converted EUR amounts MUST be displayed rounded to the nearest €10, with exact halfway values rounded away from zero (for example, €625 becomes €630). Calculations MUST retain unrounded values and round each displayed total or range endpoint only after calculation; displayed rounded line items may therefore differ from the rounded total. Unrounded category totals and trip expenditure MUST reconcile with chapter expenditure plus unallocated trip-wide expenditure. A shared cost already allocated to chapters MUST NOT be added again at trip level. Inter-chapter transfer costs MUST follow chapter ownership and be counted once.

Refundable deposits, expenditure, contingency, emergency reserve, and expected income MUST remain distinguishable. Cash-needed totals MUST explain which of these they include. When inputs are incomplete, affected totals MUST remain TBD or be explicitly labeled partial with their missing inputs.

## Publication and maintenance

Chapter data MUST be recapped in a PDF generated according to the applicable consulate's required format, as registered in [PUBLICATION](../PUBLICATION.md#consular-chapter-recap-pdf). The travel plan MUST provide the consolidated source for that output; the PDF MUST NOT be maintained as an independent itinerary.

Any chapter change MUST trigger review of the corresponding travel plan recap and invalidate any generated PDF that no longer matches. Before generation, review MUST reconcile chapter coverage, dates, housing nights, budgets, transfer ownership, and uncertainty labels. Before a PDF is marked ready for submission, the official consular format MUST be verified and the rendered output checked. Required checks, source references, and generation status follow the publication standard.

## Reusable model

The [travel plan model](../models/travel-plan.md) provides a copyable template and authoring guidance. It adds no requirements to this standard.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial draft travel plan recap category covering chapter consolidation, budgets, source coverage, and consular PDF publication, with a reusable model; EUR displays rounded to the nearest €10. |
