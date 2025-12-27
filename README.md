# Urinalysis Data Analytics and Clinical Risk Modeling

This repository contains an end-to-end data science and machine learning pipeline
for analyzing urinalysis test results. The project is based on a publicly available
Kaggle dataset collected from a local clinic in the Philippines (2020–2023).

The goal is to:
- Explore and clean urinalysis data
- Identify clinical patterns and associations
- Analyze temporal trends
- Build predictive models for abnormal results / UTI likelihood
- Perform unsupervised clustering of urine profiles
- Construct interpretable clinical risk scores

---

## Dataset

**Source:** Kaggle – Urinalysis Test Results  
**Type:** Structured clinical laboratory data  
**Features include:**
- Physical: Color, Transparency
- Chemical: pH, Specific Gravity, Glucose, Protein, Ketones
- Microscopic: RBC, WBC, Bacteria, Crystals
- Date of test

---

## Repository Structure

- `data/` – Raw and processed datasets
- `notebooks/` – Jupyter notebooks for each analysis stage
- `src/` – Reusable preprocessing and feature engineering functions
- `outputs/` – Generated figures, tables, and trained models

---

## Analysis Notebooks

| Notebook | Description |
|--------|-------------|
| 01_eda.ipynb | Exploratory Data Analysis |
| 02_correlation_association.ipynb | Statistical relationships |
| 03_time_series_analysis.ipynb | Temporal trends |
| 04_predictive_modeling.ipynb | Supervised ML models |
| 05_unsupervised_learning.ipynb | Clustering & PCA |
| 06_risk_stratification.ipynb | Clinical risk scoring |

