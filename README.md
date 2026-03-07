# Chronic Pain Science Repository

This repository is organized for deterministic multilingual documentation of the Chronic Pain Science model.

## Single Source of Truth (SSOT)

The authoritative English sources are:

- `docs/en/chronic_pain_model_summary.md`
- `docs/en/chronic_pain_model_summary_v_2.md`

Translations are maintained from these SSOT files:

- German: `docs/de/chronic_pain_model_summary_de.md`, `docs/de/chronic_pain_model_summary_v_2_de.md`
- Dutch: `docs/nl/chronic_pain_model_summary_nl.md`, `docs/nl/chronic_pain_model_summary_v_2_nl.md`
- European Portuguese: `docs/pt-PT/chronic_pain_model_summary_pt-PT.md`, `docs/pt-PT/chronic_pain_model_summary_v_2_pt-PT.md`

## Binary Asset Protection

- Files in `figures/` (especially PNG files) are binary assets and must not be modified, regenerated, renamed, or recompressed during translation updates.

## Drift Detection

- `docs/source-map/section_alignment_map.md` tracks section-level alignment across SSOT documents and language variants.
- `docs/source-map/file_inventory.md` provides an inventory of repository files used in this deterministic build.
- Structural drift detection depends on heading, URL, and diagram parity checks.
