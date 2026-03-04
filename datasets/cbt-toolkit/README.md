# CBT Toolkit

Structured dataset covering the public CBT toolkit on MetalHatsCats. It combines reflection cards, metaphors, and protocols into one citable corpus so assistants, educators, and practitioners can reference the toolkit with clear type labels, summaries, canonical links, and source provenance.

## Dataset Facts

- Records: 115
- Language: en
- License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- Canonical website landing page: https://metalhatscats.com/datasets/cbt-toolkit
- Source website: https://metalhatscats.com

## Files

- `dataset.jsonl` — newline-delimited records for ingestion
- `schema.json` — JSON Schema for records
- `README.md` — dataset documentation

## Fields

| Field | Type | Description |
| --- | --- | --- |
| `id` | `string` | Stable CBT source identifier. |
| `content_type` | `string` | Record family within the toolkit: card, metaphor, or protocol. |
| `title` | `string` | Public English title for the toolkit item. |
| `summary` | `string` | Primary prompt, description, or explanatory summary. |
| `step_count` | `integer` | Number of steps for protocol records, or 0 for non-protocol items. |
| `language` | `string` | Primary language used for the exported record. |
| `canonical_url` | `string` | Canonical public CBT page path. |

## Provenance

This dataset is generated from public source material maintained in the MetalHatsCats website repository. The source collections for this dataset are:

- `app/cbt/data/cbt_cards.json`
- `app/cbt/data/metaphors.json`
- `app/cbt/data/protocols.json`

## Citation

Please cite the dataset landing page first:

- https://metalhatscats.com/datasets/cbt-toolkit

If the separate GitHub repository and a Zenodo DOI are published later, prefer the release DOI for archival citation and keep the website landing page as the human-readable reference page.

## Related Apps

- Google Play: https://play.google.com/store/apps/details?id=cbt.cbtcards.stressrelief
- App Store: https://apps.apple.com/app/cbt-cards-%D1%81bt-for-daily-use/id6737169041

## Usage Notes

- Keep the source attribution to MetalHatsCats.
- Do not use the dataset for commercial redistribution without permission.
- Re-check the website landing page for newer release information before large-scale reuse.
