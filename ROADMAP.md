# Roadmap

Planned additions and improvements, in priority order.

## In Progress

- [ ] PhysioNet review of MIMIC-IV-Ext-ECG-Glucose — awaiting acceptance and DOI assignment
- [ ] Update README with PhysioNet DOI and citation once assigned

## Phase 2 — Planned Index Additions

- [ ] ShanghaiT2DM (2023) — 100 T2D patients, meals + medication + blood tests
- [ ] DiaTrend (2023) — 54 T1D patients, multi-vendor CGM comparison
- [ ] EchoNext (2025) — 100,000 12-lead ECGs, Columbia University
- [ ] Large-Scale Wearable ECG Dataset (Nature Communications 2023) — 658,486 wearable ECGs

## Phase 3 — Repository Improvements

- [ ] Standardise description format across all three index files (add device, duration, DOI fields consistently)
- [ ] Add `scripts/` directory with basic preprocessing utilities for D1NAMO and OhioT1DM
- [ ] Fill missing original paper links across index entries

## Completed

- [x] Initial dataset index: 14 CGM + 8 ECG + 4 paired datasets
- [x] MIMIC-IV-Ext-ECG-Glucose dataset constructed (437,671 records, 131,771 patients)
  - BigQuery SQL extraction pipeline (v3.2, 15-step cohort)
  - PyTorch Dataset class with masked dynamics and sample weighting
  - Six-model XGBoost baseline with Clarke Error Grid and SHAP analysis
  - MLP baseline with masked dynamics embedding and residual diagnostics
  - Figure generation scripts (Figures 1–6)
- [x] PhysioNet submission prepared and submitted
- [x] Google Cloud Research Credits awarded (GCP19980904)