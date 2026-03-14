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

- **Weinstock et al. (2016)**
  - **Link**: https://arxiv.org/pdf/2410.05780
  - **Description**: 192 subjects (T1D); Dexcom G4 CGM at 5-min; static/dynamic covariates; public.
  - **Original Dataset Paper**: Weinstock et al. (2016) - Curated in [GlucoBench](https://github.com/IrinaStatsLab/GlucoBench)
# Data

The datasets are distributed according to the following licences and can be downloaded from the following links outlined in the table below.

| Dataset | License | Number of patients | CGM Frequency |
| ------- | ------- | ------------------ | ------------- |
| [Colas](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0225817#sec018) | [Creative Commons 4.0](https://creativecommons.org/licenses/by/3.0/us/) | 208 | 5 minutes |
| [Dubosson](https://doi.org/10.5281/zenodo.1421615) | [Creative Commons 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) | 9 | 5 minutes |
| [Hall](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2005143#pbio.2005143.s010) | [Creative Commons 4.0](https://creativecommons.org/licenses/by/4.0/) | 57 | 5 minutes |
| [Broll](https://github.com/irinagain/iglu) | [GPL-2](https://www.r-project.org/Licenses/GPL-2) | 5 | 5 minutes |
| [Weinstock](https://public.jaeb.org/dataset/537) | [Creative Commons 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) | 200 | 5 minutes |

- **OhioT1DM**
  - **Link**: https://ohio.qualtrics.com/jfe/form/SV_02QtWEVm7ARIKIl (requires DUA for access)
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

- **ShanghaiT1DM and ShanghaiT2DM (2023)**
  - **Link**: https://figshare.com/collections/Diabetes_Datasets_ShanghaiT1DM_and_ShanghaiT2DM/6310860 
  - **Description**: T1D (n=12) and T2D (n=100) patients; CGM data at 15-min intervals over 3–14 days per patient; clinical characteristics including age, BMI, HbA1c, complications, and comorbidities; laboratory measurements (fasting/postprandial glucose, C-peptide, insulin, lipids, renal function); full medication records (hypoglycemic agents and other drugs); daily dietary records; real-life acquisition conditions.
  - **Referred Papers**: Used in blood glucose prediction, Bayesian forecasting, and self-supervised learning benchmarks.
  - **Original Dataset Paper**: Zhao Q, Zhu J, Shen X, et al. "Chinese diabetes datasets for data-driven machine learning." *Scientific Data* 10, 35 (2023). https://doi.org/10.1038/s41597-023-01940-7

- **DiaTrend (2023)**
  - **Link**: [DiaTrend - A dataset from advanced diabetes technology](https://doi.org/10.7303/syn38187184) Register for a Synapse account (www.synapse.org), Become a Synapse Certified User with a validated user profile, Submit an Intended Data Use statement, Agree to the Conditions of Use.
  - **Description**: 54 T1D patients (ages 19–74; 17 male, 37 female); 27,561 days of CGM data (5-min intervals; Dexcom, Abbott, and Medtronic devices) and 8,220 days of insulin pump data (basal/bolus doses, carbohydrate intake logs, insulin-to-carb ratios); recruited across two independent studies (Dartmouth Health 2019; SweetGoals RCT); average ~510 days of follow-up per patient; public with access instructions in paper.
  - **Referred Papers**: Used in blood glucose prediction, hypoglycemia/hyperglycemia detection, meal detection, and insulin delivery algorithm development.
  - **Original Dataset Paper**: Temiloluwa Prioleau, Abigail Bartolome, Richard Comi & Catherine Stanger "DiaTrend: A dataset from advanced diabetes technology to enable development of novel analytic solutions." *Scientific Data* 10, 556 (2023). https://doi.org/10.1038/s41597-023-02469-5
