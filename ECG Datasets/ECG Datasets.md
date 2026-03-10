### ECG Datasets

Public ECG datasets for ML/AI in biomedical research, often from PhysioNet, Kaggle, etc. Includes arrhythmia, diagnostics, etc.

- **PTB-XL**
  - **Link**: https://physionet.org/content/ptb-xl/1.0.3/
  - **Description**: 21,801 12-lead ECGs from 18,869 patients (10-sec); annotations for 71 statements; public access.
  - **Referred Papers**: Used in arrhythmia studies.
  - **Original Dataset Paper**: "PTB-XL, a large publicly available electrocardiography dataset" (2020) (https://www.nature.com/articles/s41597-020-0495-6).

- **PTB Diagnostic ECG Database**
  - **Link**: https://physionet.org/content/ptbdb/1.0.0/
  - **Description**: 549 high-res 15-lead ECGs from 290 subjects; includes healthy and diseased; public.
  - **Referred Papers**: Various diagnostic studies.
  - **Original Dataset Paper**: "The PTB Diagnostic ECG Database" (2000) (no direct link; described on PhysioNet).

- **MIT-BIH Arrhythmia Database**
  - **Link**: https://physionet.org/content/mitdb/1.0.0/
  - **Description**: 48 half-hour 2-lead ECGs; annotated beats; public.
  - **Referred Papers**: Standard for arrhythmia detection.
  - **Original Dataset Paper**: "The MIT-BIH Arrhythmia Database" (1980) (described on PhysioNet; paper in Circulation).

- **MIMIC-IV-ECG**
  - **Link**: https://physionet.org/content/mimic-iv-ecg/1.0/
  - **Description**: Diagnostic ECGs from MIMIC-IV (critical care); linked to clinical data; credentialed access.
  - **Referred Papers**: Used in multimodal studies.
  - **Original Dataset Paper**: None; part of MIMIC series (https://www.nature.com/articles/s41597-023-02153-8 for related).

- **MEETI**
  - **Dataset Paper**: https://www.nature.com/articles/s41597-026-06796-1
  - **Description**: Built on the MIMIC
-IV-ECG database of over 800,000
recordings, MEETI aligns each record across four components using unique identifiers: (1) raw
signals, (2) plotted images, (3) per
-beat parameters, and (4) interpretation text. This structure
enables multimodal transformer learning and supports explainable, integrated analysis. MEETI
provides a robust foundation and benchmark for next
-generation cardiovascular artificial
intelligence research
.
  - **Dataset**: [MEETI: A Multimodal ECG Dataset from MIMIC-IVECG with Signals, Images, Features and
Interpretations](https://zenodo.org/doi/10.5281/zenodo.15893351)


- **A large-scale multi-label 12-lead electrocardiogram database with standardized diagnostic statements**
  - **Dataset Paper**: https://www.nature.com/articles/s41597-022-01403-5
  - **Description**: The dataset contains 25770 ECG records from 24666 patients, which were acquired from Shandong Provincial Hospital (SPH) between 2019/08 and 2020/08.
  - **Dataset**: [A large-scale multi-label 12-lead electrocardiogram database with standardized diagnostic statements](https://doi.org/10.6084/m9.figshare.c.5779802.v1)