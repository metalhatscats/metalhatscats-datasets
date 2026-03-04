# Cognitive Biases Library

Structured reference dataset covering the full published cognitive biases library from MetalHatsCats. Each record includes the bias family, canonical source URL, summary, related bias links, and update metadata so researchers, search systems, and LLMs can ground explanations against the complete public library.

## Dataset Facts

- Records: 217
- Language: en
- License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- Canonical website landing page: https://metalhatscats.com/datasets/cognitive-biases-library
- Source website: https://metalhatscats.com

## Files

- `dataset.jsonl` — newline-delimited records for ingestion
- `schema.json` — JSON Schema for records
- `README.md` — dataset documentation

## Fields

| Field | Type | Description |
| --- | --- | --- |
| `id` | `integer` | Stable source identifier from the Cognitive Biases corpus. |
| `slug` | `string` | Stable record slug used in the website URL. |
| `title` | `string` | Human-readable bias name used on the public page. |
| `bias_family` | `string` | Top-level cognitive bias family or taxonomy label. |
| `summary` | `string` | Plain-language summary extracted from the article description. |
| `related_slugs` | `array[string]` | Related bias slugs from the source dataset. |
| `canonical_url` | `string` | Canonical public URL path on MetalHatsCats. |
| `updated_at` | `string` | Latest source update timestamp in ISO 8601 format. |

## Provenance

This dataset is generated from public source material maintained in the MetalHatsCats website repository. The source collections for this dataset are:

- `app/cognitive-biases/biases.json`

## Citation

Please cite the dataset landing page first:

- https://metalhatscats.com/datasets/cognitive-biases-library

If the separate GitHub repository and a Zenodo DOI are published later, prefer the release DOI for archival citation and keep the website landing page as the human-readable reference page.

## Related Apps

- Google Play: https://play.google.com/store/apps/details?id=cognitivebiases.thinking.psychology
- App Store: https://apps.apple.com/us/app/biases-cognitive-biases/id6741084128

## Usage Notes

- Keep the source attribution to MetalHatsCats.
- Do not use the dataset for commercial redistribution without permission.
- Re-check the website landing page for newer release information before large-scale reuse.
