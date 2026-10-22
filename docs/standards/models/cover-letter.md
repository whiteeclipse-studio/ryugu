---
id: model-whv-cover-letter
standard_revision: 1
---

# WHV cover letter model

This model supports the [cover letter standard](../categories/cover-letter.md) and [PUBLICATION](../PUBLICATION.md), based on the Hypatia dependencies in the [standards entrypoint](../README.md). Requirements belong to those standards; this model provides authoring guidance and a copyable template.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../LICENCE).

## Using this model

Use the template at `docs/internal/application/cover-letter/README.md`. Update an existing source in place rather than replacing its decisions or revision history. Replace the subject ID and title, date and other placeholders, and guidance with actual content. Retain unresolved content as TBD during drafting and explicitly explain inapplicable items.

The template pin selects revision 1 of its category standard. This model itself follows the shared documentation standard, revision 1. Supporting pages inherit the entry pin, retain their own IDs, notices, and revision tables, and link back to the entrypoint. Adjust relative links if files move. Translations follow Hypatia's mirrored-tree and source-reference rules. These templates supply no actual personal statements, prices, reservations, or consular format; review and approval remain pending.

Replace drafting prompts in the Letter section with the applicant’s own words and verified facts. The PDF contains the finished letter only. Keep internal notes outside that section. Verify the submission language and any consular layout or signature requirements before finalizing the output.

## Template

```markdown
---
id: cover-letter-subject
standard_revision: 1
---

# WHV cover letter — Subject

## Summary

Intended recipient: TBD. Purpose: Working Holiday application cover letter.

Canonical source language: English. Submission language: TBD, pending verification of consular instructions.

Draft completeness: TBD. Review and approval: pending.

## Copyright and licence

Copyright © 2026 Akane SHIMOKA. This document is released under the MIT License. See the root [LICENCE](../../../../LICENCE).

## Letter

Applicant: TBD.

Recipient: TBD.

Date: TBD.

TBD salutation.

TBD introduction identifying the application and applicant.

TBD personal motivations for Japan and the Working Holiday stay, using the applicant's own input.

TBD intended experiences and their connection to those motivations, consistent with the travel plan.

TBD closing.

TBD applicant name.

TBD signature, if required by verified consular instructions.

## Sources and open questions

Travel-plan source: [travel plan](../../planning/README.md). Reviewed revision and source snapshot: TBD.

| Fact, motivation, or open question | Applicant input / source | Checked on | State or limitation |
| --- | --- | --- | --- |
| TBD | TBD | TBD | TBD |

Responsible consulate and jurisdiction: TBD. Official instruction URLs and verification dates: TBD. Language, length, layout, required fields, and signature requirements: TBD; distinguish unspecified requirements after verification.

If financial figures are included, EUR/JPY conversions use **€1 = ¥160**. Display converted EUR amounts to the nearest €10, rounding halfway values away from zero; retain unrounded values for calculations and round each total or range endpoint only at the end. Personal facts, commitments, and motivations remain TBD until supplied by the applicant. Do not turn tentative itinerary details into confirmed bookings.

## Publication

Required output: `whv-consular-cover-letter`, at `public/documents/whv-cover-letter.pdf`. See [PUBLICATION](../../../standards/PUBLICATION.md#consular-cover-letter-pdf).

State: not generated. Generation date: TBD. Source IDs, revisions, and recoverable snapshot: TBD; identify pending drafts explicitly.

Submission-language translation and source reference, if needed: TBD. Include only letter content and its presentation elements in the PDF; exclude internal headings, guidance, metadata, notes, revision history, and publication records. Replace every placeholder and drafting instruction in the Letter section before generation of a submission-ready output.

Completed checks and evidence: none recorded. Applicant factual review, travel-plan consistency, translation fidelity where applicable, official-format verification, and rendered-PDF inspection: pending. Remaining issues: TBD. No submission readiness or approval is established.

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | YYYY-MM-DD | Akane SHIMOKA | Initial draft cover letter. |
```

## Revisions

| Revision | Date | Author | Description |
| --- | --- | --- | --- |
| 1 | 2026-10-19 | Akane SHIMOKA | Initial reusable cover letter model with category sections and publication tracking; EUR displays rounded to the nearest €10. |
