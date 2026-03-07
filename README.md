# Chronic Pain Science Repository

This repository is organized for deterministic multilingual documentation of the Chronic Pain Science model.

## Single Source of Truth (SSOT)

- `docs/en/chronic_pain_model_v2_en.md` is the authoritative English V2 source.
- `docs/de/chronic_pain_model_v2_de.md`, `docs/pt-PT/chronic_pain_model_v2_pt-PT.md`, and `docs/nl/chronic_pain_model_v2_nl.md` are strict 1:1 translations.
- Section numbering, heading order, paragraph boundaries, lists, diagrams, and references are alignment-locked.

## Binary Asset Protection

- Files in `figures/` (especially PNG files) are binary assets and must not be modified, regenerated, renamed, or recompressed during translation updates.

## Drift Detection

- `docs/source-map/section_alignment_map.md` tracks section-level alignment across EN, DE, PT-PT, and NL documents.
- `docs/source-map/file_inventory.md` provides an inventory of repository files used in this deterministic build.
- Structural drift detection depends on heading, URL, and diagram parity checks.
