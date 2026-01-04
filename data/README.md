# Data directory (git-ignored)

This template assumes you will not commit raw or processed datasets.

Use this structure locally:
- `data/raw/` — raw downloads (keep original filenames); record provenance in `data/raw/README.md`.
- `data/processed/` — derived datasets (splits, encoded matrices, cached features); document in `data/processed/README.md`.

Notes:
- Do not store secrets (API keys, credentials) under `data/`.
