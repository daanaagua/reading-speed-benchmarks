# Contributing

Thanks for helping improve this benchmark repository.

## Scope

This project maintains practical reading-speed benchmark defaults by content type.
Contributions should improve clarity, data quality, or reproducibility.

## What to contribute

- Benchmark refinements in `data/benchmarks.csv`
- Method updates in `docs/methodology.md`
- Additional worked examples in `docs/examples.md`
- Typos, clarity, and structure improvements in docs

## Data rules

When editing `data/benchmarks.csv`, keep this schema and order:

`group,genre_id,genre_label,default_wpm,speed_band,notes`

Please follow these constraints:

- `default_wpm` must be a positive integer.
- `speed_band` must be one of: `fast`, `moderate`, `careful`, `deep`.
- Keep `genre_id` stable; avoid renaming existing IDs unless necessary.
- Add short, plain-English `notes` that explain the assumption.

## Pull request checklist

Before submitting a PR, make sure you:

1. Explain what changed and why.
2. Reference source rationale for any benchmark value change.
3. Keep edits focused (avoid unrelated formatting churn).
4. Confirm links in markdown files still work.

## Suggested PR format

- **Summary:** one short paragraph
- **Files changed:** list of edited files
- **Reasoning:** source notes or practical rationale
- **Impact:** who benefits and how

## Style guide

- Use concise, plain English.
- Prefer practical defaults over speculative precision.
- Keep the project consistent with the methodology document.
