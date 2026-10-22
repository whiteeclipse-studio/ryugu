---
id: ryugu-documentation
standard_revision: 1
---

# Ryugu documentation
## Summary

Ryugu is the documentation and planning vault for the Japan Working Holiday stay planned from October 20, 2027 to October 2028.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../LICENCE) for the current scope and retained third-party notices.

## Structure and navigation

| Location                                       | Purpose                                                     |
| ---------------------------------------------- | ----------------------------------------------------------- |
| [Travel plan](./internal/planning/README.md)   | Consolidated recap of WHV chapters, budgets, and publication status |
| [Standards](./standards/README.md)             | Local extensions based on the sibling Hypatia standards     |
| [Chapter model](./standards/models/chapter.md) | Reusable template for a dated WHV chapter                   |
| [Publication](./standards/PUBLICATION.md) | Required outputs and consular PDF generation rules |
| `translations/`                                | Optional translations mirroring the English source tree     |

The vault root is the `ryugu` directory. Open that directory as an existing vault in Obsidian; start with this index. The empty `.obsidian/` directory reserves the vault configuration location. No plugins, synchronization, publication, or application settings are configured.

Authored documents are under `docs/`. Links use relative Markdown paths. Supporting assets belong in an `assets/` directory beside their document, with filenames beginning with the document ID. Twelve chronologically numbered chapters record the draft itinerary. The first Tokyo chapter retains its existing planning; eight newly added chapters contain short summaries with tentative windows and intentionally empty planning sections for later detail. The second Tokyo stay includes a Fujinomiya side trip.

## Documentation basis

Ryugu is based on the sibling Hypatia shared documentation and governance standards. The overall travel plan follows the local [travel plan category](./standards/categories/travel-plan.md); individual chapters follow the local [WHV chapter category](./standards/categories/chapters.md), adding date ranges, expected stays, budgets, and connecting transport. The [standards entrypoint](./standards/README.md) records draft dependency bindings and unresolved adoption references.

English is the canonical language. The travel plan retains Confirmed, Tentative, Ideas, and TBD labels. Document review and approval remain pending.

## Revisions

| Revision | Date       | Author        | Description                          |
| -------- | ---------- | ------------- | ------------------------------------ |
| 1        | 2026-10-19 | Akane SHIMOKA | Initial documentation scaffold, Hypatia-based chapter standard and model, four chapter scaffolds, travel plan consolidation, and publication requirements. 2026-10-22: Expanded the draft itinerary to twelve chronological chapters and registered the Fujinomiya side trip, keeping new chapter planning sections empty. |
