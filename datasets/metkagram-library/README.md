# Metkagram Library

Structured dataset covering the public Metkagram export across supported languages and collections. Records include annotated library items, patterns, and dialogues with titles, summaries, annotation counts, change timestamps, and public preview URLs. The dataset is intended to support citation, cataloging, and search visibility for the broader Metkagram learning corpus.

## Dataset Facts

- Records: 2240
- Language: en
- License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- Canonical website landing page: https://metalhatscats.com/datasets/metkagram-library
- Source website: https://metalhatscats.com

## Files

- `dataset.jsonl` — newline-delimited records for ingestion
- `schema.json` — JSON Schema for records
- `README.md` — dataset documentation

## Fields

| Field | Type | Description |
| --- | --- | --- |
| `id` | `string` | Stable Metkagram document identifier. |
| `language` | `string` | Language partition for the document export. |
| `collection` | `string` | Collection family: library, patterns, or dialogues. |
| `title` | `string` | Public title of the Metkagram document. |
| `summary` | `string` | Short summary or comment from the exported document. |
| `annotation_count` | `integer` | Number of annotations attached to the document. |
| `changed_on` | `string` | Last source update timestamp in ISO 8601 format. |
| `canonical_url` | `string` | Public Metkagram preview page path. |

## Provenance

This dataset is generated from public source material maintained in the MetalHatsCats website repository. The source collections for this dataset are:

- `data/metkagram-export/enGram/library/documents.json`
- `data/metkagram-export/enGram/patterns/documents.json`
- `data/metkagram-export/enGram/dialogues/documents.json`
- `data/metkagram-export/deGram/library/documents.json`
- `data/metkagram-export/deGram/patterns/documents.json`
- `data/metkagram-export/deGram/dialogues/documents.json`

## Citation

Please cite the dataset landing page first:

- https://metalhatscats.com/datasets/metkagram-library

If the separate GitHub repository and a Zenodo DOI are published later, prefer the release DOI for archival citation and keep the website landing page as the human-readable reference page.

## Related Apps

- Google Play: https://play.google.com/store/apps/details?id=app.metkagram.android
- App Store: https://apps.apple.com/us/app/grammar-cards-ai-tutor/id6502211918
- Microsoft Store: https://www.microsoft.com/store/productId/9N3M601KNVLZ?ocid=pdpshare

## Usage Notes

- Keep the source attribution to MetalHatsCats.
- Do not use the dataset for commercial redistribution without permission.
- Re-check the website landing page for newer release information before large-scale reuse.
