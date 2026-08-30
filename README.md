# Inflammatory Breast Cancer and Racial Disparities

## Manuscript

- Breast_cancer_research_manuscript_Second_Revision.pdf
- Supplementary.pdf

## Overview

This repository contains materials related to the manuscript:

**Inflammatory Breast Cancer and Racial Disparities: A SEER Database Analysis of Survival Outcomes**

The study evaluates breast cancer-specific survival among women with inflammatory breast cancer (IBC) and non-inflammatory locally advanced breast cancer using data from the Surveillance, Epidemiology, and End Results (SEER) Program.

## Methods

The manuscript includes:

- Kaplan–Meier survival analysis
- Cause-specific Cox proportional hazards models
- Fine–Gray competing-risks regression
- Accelerated Failure Time (AFT) models
- Propensity-score matching
- Formal interaction testing
- Sensitivity analyses

## Software

The analysis used the following R packages:

| Package | Version |
|----------|----------|
| survival | 3.8.3 |
| cmprsk | 2.2.12 |
| MatchIt | 4.7.2 |
| cobalt | 4.6.3 |
| gtsummary | 2.4.0 |
| survminer | 0.5.1 |

## Data Availability

SEER data are not included in this repository.

Researchers who wish to reproduce the analysis must obtain access to SEER data directly from the National Cancer Institute and comply with all applicable data-use agreements.

## Repository Status

This repository is being updated progressively with additional documentation and reproducibility materials.
