---
id: ryugu-documentation-standards
standard_revision: 1
---

# Ryugu documentation standards
## Purpose and basis

Ryugu extends the documentation standards in the sibling Hypatia project. The [shared documentation standard](../../../hypatia/docs/standards/README.md) defines structure, metadata, language, notices, revisions, translations, assets, and source references. The [governance standard](../../../hypatia/docs/standards/GOVERNANCE.md) defines ownership, review, approval, and licensing. Those requirements apply here; local categories add project-specific requirements.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../LICENCE).

## Standards and dependencies

| Local category | Revision | Shared documentation dependency | Governance dependency | Placement |
| --- | --- | --- | --- | --- |
| [WHV chapters](./categories/chapters.md), `std-whv-chapters` | 1 | Hypatia `std-documentation`, revision 1 | Hypatia `std-governance`, revision 1 | `docs/internal/planning/chapters/<id>/README.md` and supporting pages |
| [WHV travel plan](./categories/travel-plan.md), `std-whv-travel-plan` | 1 | Hypatia `std-documentation`, revision 1 | Hypatia `std-governance`, revision 1 | `docs/internal/planning/README.md` and supporting pages outside `chapters/` |
| [WHV cover letter](./categories/cover-letter.md), `std-whv-cover-letter` | 1 | Hypatia `std-documentation`, revision 1 | Hypatia `std-governance`, revision 1 | `docs/internal/application/cover-letter/README.md` and supporting pages |

This entrypoint, [PUBLICATION](./PUBLICATION.md), and the [chapter](./models/chapter.md), [travel plan](./models/travel-plan.md), and [cover letter](./models/cover-letter.md) models follow Hypatia's shared documentation standard, revision 1, with governance revision 1. PUBLICATION revision 1 extends those shared requirements for generated outputs. Travel plan revision 1 uses chapter revision 1 and PUBLICATION revision 1; chapter revision 1 likewise uses travel plan revision 1 and PUBLICATION revision 1 for consolidation and publication. These bindings remain attached to these draft revisions.

The upstream repository is `https://github.com/whiteeclipse-studio/hypatia`. Its local shared and governance standards are currently uncommitted drafts. Exact-version canonical adoption references are therefore TBD; the sibling links provide navigation, not immutable adoption references. These dependency bindings describe the intended draft basis. Formal adoption and owner approval remain pending, and Ryugu's `CODEOWNERS` is still an unresolved scaffold.

Cover-letter revision 1 uses travel plan revision 1 and PUBLICATION revision 1 for consistency and generation requirements.

## Categories and models

- [WHV chapter standard](./categories/chapters.md): chronologically numbered stays, expected content, budgets, and connecting transport.
- [WHV chapter model](./models/chapter.md): copyable chapter template.
- [WHV travel plan standard](./categories/travel-plan.md): complete chapter recap and trip-wide consolidation.
- [WHV travel plan model](./models/travel-plan.md): copyable chapter recap and publication record.
- [WHV cover letter standard](./categories/cover-letter.md): personal motivations, letter content, and consular PDF publication.
- [WHV cover letter model](./models/cover-letter.md): copyable letter source with drafting and publication notes.
- [PUBLICATION](./PUBLICATION.md): required output register and consular PDF generation requirements.

The local categories preserve Hypatia's mandatory shared requirements. No itinerary choices or reservations are established by the standard or model.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial draft standards index and Hypatia dependency bindings for chapters, travel plan consolidation, cover letters, their reusable models, and publication. |
