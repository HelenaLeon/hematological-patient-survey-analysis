# Hematological Patient Survey Analysis
### Data Cleaning, Analysis & Visualization for Healthcare Research

[![Project Type](https://img.shields.io/badge/Project-Healthcare%20Analytics-blue)]()
[![Tools](https://img.shields.io/badge/Tools-Excel%20%7C%20SPSS-green)]()
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

---

## Overview

A real-world data analysis project conducted in collaboration with **ASCOL** (Asociación Contra la Leucemia y Enfermedades de la Sangre — Association Against Leukemia and Blood Diseases) to analyze survey data from **234 hematological cancer patients** in Spain.

This project was part of the **AECOCO initiative** (Aprendiendo Estadística Colaborando con la Comunidad), a service-learning program connecting university statistics students with healthcare organizations.

**Objective:** Improve the quality of care and support provided to hematological patients and their caregivers through rigorous data cleaning and analysis.

---

## Key Contributions

| Task | Description |
|------|-------------|
| **Data Cleaning** | Processed raw survey data: handled missing values, corrected data entry errors, removed duplicates, standardized formats |
| **Data Unification** | Recoded 69 variables across multiple categories; standardized regional and diagnostic classifications |
| **Descriptive Analysis** | Computed measures of central tendency, dispersion, and distribution shape |
| **Visualization** | Created bar charts, pie charts, histograms, and box plots segmented by sex |
| **Statistical Reporting** | Interpreted results and identified potential biases in the data collection |

---

## Results & Visualizations

### Age Distribution & Disease Types
![Age and Disease Distribution](images/01_age_distribution_and_disease_types.jpg)

**Key findings:**
- Female patients predominate (144 vs 90 males)
- Lymphomas are the most common diagnosis (~42% of sample)
- Age range: 71 years (males), 66 years (females)

---

### Employment Status, Mobility & Sociofamiliar Impact
![Employment and Mobility Analysis](images/02_employment_mobility_sociofamiliar.jpg)

**Key findings:**
- ~70% report the diagnosis influenced their employment status
- Most patients report low difficulty in mobility tasks (median = 0)
- Women more frequently perceive changes in socio-family environment

---

### Body Image, Relationships & Statistical Summary
![Body Image and Relationships](images/03_body_image_relationships_stats.jpg)

**Key findings:**
- 77% report changes in intimate/sexual relationships
- Majority of both sexes perceive changes in body image
- Complete statistical summary for nominal variables shown

---

### Descriptive Statistics Table
![Statistics Table](images/04_statistics_table.jpg)

Full measures of central tendency and dispersion for quantitative variables, segmented by sex.

---

## Dataset Characteristics

| Attribute | Value |
|-----------|-------|
| **Sample Size** | 234 patients (after cleaning) |
| **Variables** | 69 total |
| **Variable Types** | Sociodemographic, clinical, functional (22 daily living scales), psychosocial |
| **Scale** | Likert 0-10 for functional variables |

### Disease Categories
| Category | Description |
|----------|-------------|
| Leukemias | Chronic and acute forms |
| Lymphomas | Most prevalent (~42%) |
| Myelomas | Multiple myeloma |
| Other | Myelodysplastic syndromes |

---

## Technical Skills Demonstrated

### Data Wrangling
- Handling **missing data** (modal imputation for categorical variables)
- Correcting **data entry errors** (e.g., birth year typos: 1054 → 1954)
- **Recoding categorical variables** (cities → autonomous communities, diagnoses → disease groups)
- Validating **date plausibility** and removing empty records
- Eliminating **duplicate entries**

### Statistical Analysis
- **Central tendency:** Mean, median, mode
- **Dispersion:** Variance, standard deviation, range, coefficient of variation
- **Distribution analysis:** Skewness identification, percentile calculations
- **Appropriate metric selection** based on variable type (nominal, ordinal, ratio)

### Data Visualization
- Segmented analysis by demographic groups
- Box plots with outlier identification
- Frequency distributions
- Proportional representations

### Tools
- **Microsoft Excel** — Data cleaning, unification, frequency tables
- **IBM SPSS** — Statistical analysis, visualization, descriptive statistics

---

## Bias Identification

Documented potential sources of bias in the study:

| Bias Type | Description |
|-----------|-------------|
| **Volunteer bias** | Participants may be more health-conscious than non-responders |
| **Non-response bias** | Sensitive questions may have lower response rates |
| **Social desirability** | Self-reported limitations may be under/over-stated |
| **Detection bias** | Patients with more healthcare contact may report more issues |
| **Confounding** | Age, disease stage, treatment could confound relationships |

---

## Repository Structure

```
├── README.md                          # Project overview
├── report/
│   └── ASCOL_Project_Full_Report.pdf  # Complete academic report (Spanish)
└── images/
    ├── 01_age_distribution_and_disease_types.jpg
    ├── 02_employment_mobility_sociofamiliar.jpg
    ├── 03_body_image_relationships_stats.jpg
    └── 04_statistics_table.jpg
```

---

## Context

Completed as part of the **Data Collection Techniques** course in the Statistics degree at the **University of Salamanca**, Spain (Academic Year 2025-2026).

The service-learning methodology ensured academic learning directly contributed to a real healthcare organization while developing:
- Ethical handling of sensitive health data
- Working with real-world messy data
- Communicating findings to non-technical stakeholders

---

## Ethical Considerations

- Data handled in compliance with Spanish data protection regulations
- Patient identities anonymized prior to analysis
- Confidentiality agreements maintained
- Results used solely for academic and organizational purposes

---

## Contact

**Helena Leon Santos Rocha**

- 📧 helena.srocha23@gmail.com  
- 💼 [LinkedIn](https://www.linkedin.com/in/helena-leon-4b3082213)

---

*This project demonstrates my ability to work with real healthcare data, apply rigorous data cleaning methodologies, perform descriptive statistical analysis, and communicate findings effectively—core competencies for a Data Analyst role.*
