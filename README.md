# MetalHatsCats Open Datasets

MetalHatsCats publishes structured open datasets to make its knowledge bases more citable, easier to audit, and easier to reuse in search, research, and AI retrieval workflows.

## Official Source

- Main website: https://metalhatscats.com
- GitHub repository: https://github.com/metalhatscats/metalhatscats-datasets

This repository is intended to be the public datasets companion to the main MetalHatsCats website. The website remains the canonical human-facing landing surface for dataset explanations and internal linking.

## About The Project

MetalHatsCats is an AI product studio focused on automation systems, product experiments, structured knowledge assets, and AI-ready publishing. We build practical products that turn workflows, expertise, and reusable logic into operational tools, public knowledge layers, and machine-readable data products.

This repository is the open-data layer for that work. It packages selected public datasets from our product ecosystem so they can be cited, indexed, downloaded, and reused with clear provenance.

## Focus Areas

- Agentic AI systems and workflow automation
- Product experiments and reusable digital tools
- Structured knowledge publishing for search and AI retrieval
- Public datasets with stable landing pages, schemas, and release artifacts

## Project Links

- Main site: https://metalhatscats.com
- GitHub datasets repository: https://github.com/metalhatscats/metalhatscats-datasets
- Products overview: https://metalhatscats.com/products
- Services: https://metalhatscats.com/services
- Open datasets hub: https://metalhatscats.com/datasets

## What Is Included

- `cbt-toolkit` — The full public CBT toolkit corpus covering cards, metaphors, and guided protocols.
- `cognitive-biases-library` — The full published cognitive-bias library with families, summaries, related links, and canonical URLs.
- `life-os-all-hacks` — The full public Life OS hacks corpus with hack actions, zones, summaries, and canonical source links.
- `metkagram-library` — The full Metkagram export across languages and collections with annotated learning documents and public preview links.

## Release And Versioning Model

- Website dataset pages are the canonical human-readable landing pages.
- GitHub tags and releases are the archival publication layer for reproducible reuse.
- Zenodo can archive GitHub releases and mint DOI records without changing dataset URLs.
- Each release should keep dataset slugs stable and update changelog entries when source content changes materially.

## Dataset To Product Links

### CBT Toolkit
- Dataset page: https://metalhatscats.com/datasets/cbt-toolkit
- Product page: https://metalhatscats.com/products/cbt-cards
- Google Play: https://play.google.com/store/apps/details?id=cbt.cbtcards.stressrelief
- App Store: https://apps.apple.com/app/cbt-cards-%D1%81bt-for-daily-use/id6737169041

### Cognitive Biases Library
- Dataset page: https://metalhatscats.com/datasets/cognitive-biases-library
- Product page: https://metalhatscats.com/products/cognitive-biases
- Google Play: https://play.google.com/store/apps/details?id=cognitivebiases.thinking.psychology
- App Store: https://apps.apple.com/us/app/biases-cognitive-biases/id6741084128

### Life OS All Hacks
- Dataset page: https://metalhatscats.com/datasets/life-os-all-hacks
- Product page: https://metalhatscats.com/products/brali-life-os
- Google Play: https://play.google.com/store/apps/details?id=app.brainlighter
- App Store: https://apps.apple.com/us/app/brali-lifeos-organizer/id6502211964

### Metkagram Library
- Dataset page: https://metalhatscats.com/datasets/metkagram-library
- Product page: https://metalhatscats.com/products/metkagram
- Google Play: https://play.google.com/store/apps/details?id=app.metkagram.android
- App Store: https://apps.apple.com/us/app/grammar-cards-ai-tutor/id6502211918
- Microsoft Store: https://www.microsoft.com/store/productId/9N3M601KNVLZ?ocid=pdpshare

## Citation

Use the website landing page for human-readable citation:

- https://metalhatscats.com/datasets

For release-based archival citation, use the GitHub release in https://github.com/metalhatscats/metalhatscats-datasets/releases and the Zenodo DOI once enabled.

## Repository Structure

```
datasets
  <dataset-slug>/
    README.md
    dataset.jsonl
    schema.json
```

Root-level metadata files provide citation, release, AI-ingestion, and Zenodo support for the full catalog.

## Licensing

Unless otherwise stated, repository contents are licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Commercial use, redistribution in paid products, or large-scale model training use requires permission from MetalHatsCats.

## Why These Datasets Exist

- to improve source transparency
- to make structured knowledge easier to cite
- to expose machine-readable records beyond page HTML
- to support responsible AI ingestion with attribution
- to keep dataset publication separate from the production website codebase
