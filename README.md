# CGM and ECG Multimodal Datasets

A curated index of publicly available datasets combining Continuous Glucose Monitoring (CGM) and Electrocardiogram (ECG) data for diabetes and cardiac research.

## Contents

| Category | Count | File |
|---|---|---|
| CGM datasets | 14 | [CGM Datasets/CGM Datasets.md](CGM%20Datasets/CGM%20Datasets.md) |
| ECG datasets | 8 | [ECG Datasets/ECG Datasets.md](ECG%20Datasets/ECG%20Datasets.md) |
| Paired CGM + ECG datasets | 4 | [Glucose-ECG Pairs Datasets/Glucose-ECG Pairs Datasets.md](Glucose-ECG%20Pairs%20Datasets/Glucose-ECG%20Pairs%20Datasets.md) |

## Contributed Dataset

**MIMIC-IV-Ext-ECG-Glucose** — A large-scale multimodal dataset linking 12-lead ECG signals with serial glucose measurements for ICU glucose prediction.

- 437,671 records · 131,771 unique patients · 101 columns
- Sources: MIMIC-IV v3.1 + MIMIC-IV-ECG v1.0 · Date range: 2008–2022
- Features: pharmacological confounding annotation, 10-component Signal Quality Index, four QTc formulas, glucose trajectory classification, patient-level 80/10/10 split with zero leakage
- Code: BigQuery SQL pipeline, PyTorch dataloader, figure generation scripts, XGBoost and MLP baselines
- PhysioNet submission under review
- Supported by Google Cloud Research Credits program (award GCP19980904)

## Roadmap

See [ROADMAP.md](ROADMAP.md) for planned additions and improvements.

## License

MIT — see [LICENSE](LICENSE). Individual datasets listed in this index retain their own licenses and access terms.

## Citation

If you use this repository, please cite it using the metadata in [CITATION.cff](CITATION.cff).