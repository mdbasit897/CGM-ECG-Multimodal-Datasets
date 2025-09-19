### CGM Datasets
These are public datasets focused on Continuous Glucose Monitoring (CGM) for diabetes research, often including glucose readings, insulin data, meals, and related covariates. I've compiled from comprehensive sources like Awesome-CGM GitHub, GlucoBench arXiv paper, Jaeb public studies, and other searches. For each, I've included the dataset name, primary link (e.g., download or repository), brief description (e.g., subjects, data types, access), referred papers (if mentioned in sources), and original dataset paper with link.

- **Aleppo (2017)**
  - **Link**: https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Aleppo-(2017) (includes download links for CGM data and pre-processing scripts)
  - **Description**: 225 subjects (adults 25-40 with T1D); CGM data from Dexcom G4 over 6 months; access via dataset-specific use agreements.
  - **Referred Papers**: None specified.
  - **Original Dataset Paper**: None (study-focused; data released via Jaeb Center). Related publication: "Continuous Glucose Monitoring Without Routine Blood Glucose Measurements in Adults With Type 1 Diabetes" (not directly linked as dataset paper).

- **Anderson (2016)**
  - **Link**: https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Anderson-(2016)
  - **Description**: ~14 subjects (T1D); CGM data from closed-loop artificial pancreas system; access via agreements.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: None; study publication: "Closed-Loop Control of Postprandial Glycemia Using an Insulin-on-Board Limitation Through Continuous Action on Glucose Target" (no direct link provided).

- **Brown (2019)**
  - **Link**: https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Brown-(2019)
  - **Description**: 168 subjects (children/adults 14+ with T1D); CGM from Dexcom G6 and t:Slim X2 over 6 months; access via agreements.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: "Six-Month Randomized, Multicenter Trial of Closed-Loop Control in Type 1 Diabetes" (https://www.nejm.org/doi/full/10.1056/NEJMoa1907863).

- **Buckingham (2007)**
  - **Link**: https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Buckingham-(2007)
  - **Description**: Children with diabetes; CGM data over 3 months after blinded week; access via agreements.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: None; study: "Continuous Glucose Monitoring in Children With Type 1 Diabetes" (no link).

- **Chase (2005)**
  - **Link**: https://github.com/IrinaStatsLab/Awesome-CGM/wiki/Chase-(2005)
  - **Description**: 200 subjects; CGM from GlucoWatch G2 Biographer vs. control; access via agreements.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: None; study: "Continuous Glucose Monitoring in Youth With Type 1 Diabetes" (no link).

- **Broll et al. (2021)**
  - **Link**: https://arxiv.org/pdf/2410.05780 (Appendix A for access details; data via original study)
  - **Description**: 5 subjects (T2D); Dexcom G4 CGM at 5-min intervals; covariates (dynamic known from timestamp); access public via study.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: Broll et al. (2021) - Not full citation; part of GlucoBench curation (https://arxiv.org/abs/2410.05780).

- **Colás et al. (2019)**
  - **Link**: https://arxiv.org/pdf/2410.05780 (Appendix)
  - **Description**: 201 subjects (mixed T2D/none); MiniMed iPro CGM at 5-min; static demographic/dynamic covariates; public access.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: Colás et al. (2019) - Curated in GlucoBench.

- **Dubosson et al. (2018)** (Note: This is D1NAMO, paired with ECG - see paired section for details)
  - **Link**: https://arxiv.org/pdf/2410.05780
  - **Description**: 7 subjects (T1D); MiniMed iPro2 CGM at 5-min; dynamic covariates (heart rate, insulin, BP); public.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: Dubosson et al. (2018) - "The open D1NAMO dataset" (https://www.sciencedirect.com/science/article/pii/S2352914818301059).

- **Hall et al. (2018)**
  - **Link**: https://arxiv.org/pdf/2410.05780
  - **Description**: 56 subjects (normoglycemic/prediabetes/T2D); Dexcom G4 CGM at 5-min; static/dynamic covariates; public.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: Hall et al. (2018) - Curated in GlucoBench.

- **Weinstock et al. (2016)**
  - **Link**: https://arxiv.org/pdf/2410.05780
  - **Description**: 192 subjects (T1D); Dexcom G4 CGM at 5-min; static/dynamic covariates; public.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: Weinstock et al. (2016) - Curated in GlucoBench.

- **OhioT1DM**
  - **Link**: http://smarthealth.cs.ohio.edu/OhioT1DM-dataset.html (requires DUA for access)
  - **Description**: 12 subjects (T1D); 8 weeks of CGM, insulin, physiological sensors, life-events; 5-min sampling; public with agreement.
  - **Referred Papers**: Various (e.g., used in glucose prediction studies).
  - **Original Dataset Paper**: "The OhioT1DM Dataset for Blood Glucose Level Prediction: Update 2020" (https://pmc.ncbi.nlm.nih.gov/articles/PMC7881904/).

- **HUPA-UCM Diabetes Dataset**
  - **Link**: https://data.mendeley.com/datasets/3hbcscwz44/1
  - **Description**: 25 subjects (T1D); CGM, insulin, carbs, steps, calories, heart rate, sleep; public download.
  - **Referred Papers**: Used in ML for glucose prediction.
  - **Original Dataset Paper**: "HUPA-UCM diabetes dataset" (2024) (https://www.sciencedirect.com/science/article/pii/S2352340924005262).

- **Jaeb Public Datasets (Multiple Studies)**
  - **Link**: https://public.jaeb.org/ (various datasets under "Datasets & Documents")
  - **Description**: Multiple CGM studies (e.g., "A Randomized Clinical Trial to Assess the Efficacy and Safety of Continuous Glucose Monitoring in Youth <8 with T1D"; subjects vary 50-200+; CGM, glucose profiles; public with registration.
  - **Referred Papers**: Study-specific.
  - **Original Dataset Paper**: Varies per study (e.g., JDRF CGM RCT - no single paper; see site for publications).

- **Synthetic CGM Signals**
  - **Link**: https://data.mendeley.com/datasets/chd8hx65r4/2
  - **Description**: 40,000 synthetic CGM days (288 samples/day); generated via CGAN; public.
  - **Referred Papers**: None.
  - **Original Dataset Paper**: None; description in Mendeley (2021).