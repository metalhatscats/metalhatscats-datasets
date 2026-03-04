# Life OS All Hacks

Structured dataset covering the full public Life OS hacks corpus published by MetalHatsCats. Each record links a hack to its zone, practical action, check-in instruction, summary, and canonical page URL so researchers, search systems, and assistants can cite the full Life OS knowledge base with clear provenance.

## Dataset Facts

- Records: 948
- Language: en
- License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- Canonical website landing page: https://metalhatscats.com/datasets/life-os-all-hacks
- Source website: https://metalhatscats.com

## Files

- `dataset.jsonl` — newline-delimited records for ingestion
- `schema.json` — JSON Schema for records
- `README.md` — dataset documentation

## Fields

| Field | Type | Description |
| --- | --- | --- |
| `id` | `string` | Stable Life OS source identifier. |
| `slug` | `string` | Stable Life OS hack slug used in the canonical URL. |
| `title` | `string` | Human-readable hack title. |
| `zone_slug` | `string` | Life OS zone slug for the record. |
| `zone_title` | `string` | Life OS zone title for the record. |
| `what_you_do` | `string` | Practical action summary from the source record. |
| `check_in_prompt` | `string` | Check-in instruction tied to the action. |
| `summary` | `string` | Description or summary used for public understanding. |
| `canonical_url` | `string` | Canonical public Life OS page path. |
| `updated_at` | `string` | Latest published or updated timestamp. |

## Provenance

This dataset is generated from public source material maintained in the MetalHatsCats website repository. The source collections for this dataset are:

- `data/life-os-hacks.json`
- `generated/life-os/index.json`

## Citation

Please cite the dataset landing page first:

- https://metalhatscats.com/datasets/life-os-all-hacks

If the separate GitHub repository and a Zenodo DOI are published later, prefer the release DOI for archival citation and keep the website landing page as the human-readable reference page.

## Related Apps

- Google Play: https://play.google.com/store/apps/details?id=app.brainlighter
- App Store: https://apps.apple.com/us/app/brali-lifeos-organizer/id6502211964

## Usage Notes

- Keep the source attribution to MetalHatsCats.
- Do not use the dataset for commercial redistribution without permission.
- Re-check the website landing page for newer release information before large-scale reuse.
