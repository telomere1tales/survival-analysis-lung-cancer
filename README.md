# Survival Analysis - Lung Cancer

## Overview
This project performs a complete survival analysis on clinical data from 
228 patients with advanced lung cancer, using the `lung` dataset from the 
`survival` package in R.

## Methods
- **Kaplan-Meier** estimation of overall survival
- **Log-rank test** to compare survival between male and female patients
- **Cox proportional hazards regression** to identify independent prognostic factors
- **Schoenfeld residuals** to verify model assumptions

## Key Findings
- Median overall survival: ~305 days
- Female patients had significantly better survival (HR = 0.58, p < 0.001)
- ECOG performance status was the strongest prognostic factor (HR = 1.59, p < 0.001)

## Tools & Packages
- R 4.5.3
- `survival`, `survminer`, `ggplot2`

## Files
- `survival_analysis_lung_cancer.Rmd` — R Markdown source code
- `survival_analysis_lung_cancer.html` — Full rendered report
