**Population Healthcare Analytics**
A data analytics project focused on synthetic healthcare data, exploring chronic disease risk stratification, lab trends, care interventions, and population health patterns using Python and Tableau.

This repository contains a synthetic healthcare dataset and a comprehensive analysis pipeline for visualizing and identifying high risk diabetic patients, understanding insurance coverage patterns, and evaluating care management effectiveness in a value-based care model.

PopulationHealthcareAnalytics/
├── data/
│   ├── patient_demographics.csv
│   ├── clinical_diagnoses.csv
│   ├── lab_results.csv
│   ├── medications.csv
│   ├── visits.csv
│   └── care_management.csv
│
├── notebooks/
│   ├── 01_HealthcareDatabaseGeneration.ipynb
│   ├── 02_eda_demographics.ipynb
│   ├── 03_risk_scoring.ipynb
│   ├── 04_visualizations_tableau_prep.ipynb
│
├── tableau/
│   ├── dashboard.twbx
│   └── screenshots/
│       ├── risk_tiers_pie_chart.png
│       ├── uninsured_by_county.png
│
├── requirements.txt
├── LICENSE
└── README.md


**Data Description**
| Table                      | Description                                       |
| -------------------------- | ------------------------------------------------- |
| `patient_demographics.csv` | Age, Sex, County, Insurance Type                  |
| `clinical_diagnoses.csv`   | Diabetes diagnoses (E11, E11.2, E11.9)            |
| `lab_results.csv`          | HbA1c, LDL, Creatinine with timestamps            |
| `medications.csv`          | Diabetes prescriptions (Metformin, Insulin, etc.) |
| `visits.csv`               | Visit types and outcomes                          |
| `care_management.csv`      | Education, case management, adherence programs    |

**Tools Used**
- Python
- Tableau
- Colab
- Git / GitHub
