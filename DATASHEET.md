# Datasheet: Omnus Hematology Entity-Extraction Evaluation Dataset

**Motivation.** Created to evaluate clinical entity extraction and polarity
handling for community-hematology presentations that are under-represented in
existing NLP benchmarks. Created by Omnus Labs, Inc.

**Composition.** 42 synthetic, physician-authored clinical vignettes with 714
gold-standard annotated entities. Concepts labeled for presence vs. negation.
Scope: MGUS, MBL, CLL, and undifferentiated cytopenias/cytoses. No real
patient data; no PHI.

**Collection process.** Vignettes were authored and annotated by a
board-certified hematologist-oncologist to reflect realistic community
presentations while remaining fully synthetic. Annotations follow a
pre-specified concept-and-polarity rubric.

**Preprocessing / labeling.** Entities annotated by span, normalized concept,
and polarity. Annotation inconsistencies reviewed against the rubric.

**Uses.** Intended for benchmarking extraction/normalization systems.
Not representative of true disease prevalence; not for epidemiologic
estimation or clinical use.

**Distribution.** Publicly released under [license]; archived with a
persistent identifier (DOI) via Zenodo.

**Maintenance.** Maintained by Omnus Labs, Inc. Versioned releases; issues
and corrections tracked in the repository.
