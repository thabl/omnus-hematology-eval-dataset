# Omnus Hematology Entity-Extraction Evaluation Dataset

A physician-authored, synthetic evaluation dataset for clinical entity
extraction in community hematology. Built to test structured capture of
diagnoses, laboratory findings, medications, and clinical signs from
narrative encounters, with concept and polarity (present / negated)
annotations against a gold standard.

## Important: synthetic data

All cases are **synthetic, physician-authored clinical vignettes**. They are
**not** derived from real patients and contain **no protected health
information (PHI)**. Any resemblance to a specific individual is coincidental.
The dataset exists to evaluate information-extraction systems, not to
represent real clinical populations.

## Scope

Cases span the community-hematology presentations this work targets:
- Monoclonal gammopathy of undetermined significance (MGUS)
- Monoclonal B-cell lymphocytosis (MBL)
- Chronic lymphocytic leukemia (CLL)
- Undifferentiated cytopenias and cytoses

## Contents

- `[cases file(s), e.g. cases/*.json]` — 42 annotated vignettes
- `[schema file]` — annotation schema
- 714 gold-standard annotated entities across the 42 cases
- Entity concepts with polarity labels (present vs. negated)

## Annotation schema

Each annotated entity includes:
- `text` — the span as it appears in the vignette
- `concept` — the normalized clinical concept
- `polarity` — `present` or `negated`
- `[category]` — e.g. diagnosis / laboratory / medication / sign-symptom

[Adjust field names to match your actual files.]

## Intended use

- Benchmarking clinical entity-extraction and information-structuring systems
- Evaluating concept normalization and negation/polarity handling
- Reproducible scoring against a fixed gold standard

## Provenance

Authored and annotated by a board-certified hematologist-oncologist. Part of
the Omnus open community-hematology informatics work.

## License

Released under [CC0-1.0 / CC-BY-4.0]. See `LICENSE`.

## Citation

Samour M. Omnus Hematology Entity-Extraction Gold-Standard Evaluation
Dataset (synthetic clinical vignettes with concept and polarity
annotations). Omnus Labs, Inc., 2026. [DOI once minted]

## Disclaimer

For research and evaluation only. Not a clinical decision-support tool and
not for clinical use.
