# CS3-DS4002: Tech Employment in the Age of AI

A DS 4002 Case Study by Jensen Harvey | Spring 2026

## Overview

This case study invites you to extend a time series forecasting project on global tech sector layoffs. The previous team built a SARIMA model on monthly layoff data from 2020 to 2025 and beat their seasonal naive baseline. They flagged real limitations: public reporting bias in the data, no macroeconomic covariates, only eight months of test data, no industry-level breakdowns. Your job is to pick one of those limitations (or a related extension) and produce a forecast and writeup that improves on what came before.

## Getting Started

Work through the materials in this order:

1. **Read the Hook** (`CS3Hook_TechLayoffs.pdf`) to understand the topic and the role you're stepping into.
2. **Read the Rubric** (`CS3Rubric_TechLayoffs.pdf`) to understand exactly what you need to produce and how you'll be evaluated.
3. **Explore the Materials folder** to see how the previous team approached the problem. Start with the slides for a high-level summary, then read the M2 EDA and M3 Analysis for full technical detail. The Big 5 Tech Layoffs case study is a motivating blog post that frames the broader industry context.
4. **Inspect the Data folder** when you're ready to start building. The data dictionary in `DataAppendix.pdf` documents every variable in `Tech_layoffs.csv`.
5. **Pick an extension direction** from the rubric (or propose your own to your instructor) and start building.

## Repository Structure

```
CS3-DS4002/
│
├── README.md                           This file
├── LICENSE.md                          MIT License
├── REFERENCES.md                       IEEE-style references with annotations
│
├── CS3Hook_TechLayoffs.pdf             One-page hook document
├── CS3Rubric_TechLayoffs.pdf           Full rubric with deliverable specs
│
├── Data/
│   ├── Tech_layoffs.csv                Layoffs.fyi data, 2020-2025
│   └── DataAppendix.pdf                Data dictionary and variable descriptions
│
└── Materials/
    ├── Case_Study_Big_5_Tech_Layoffs.pdf    Motivating blog post on tech layoffs
    ├── Tech_Layoffs_Slides.pdf              Previous team's presentation
    ├── tech_layoffs_M2_EDA.pdf              Previous team's exploratory analysis
    └── tech_layoffs_M3_Analysis.pdf         Previous team's modeling and forecasting
```
## Software Requirements

This project was originally built in R. The 2nd year is welcome to work in R, Python, or any language they prefer, as long as the analysis is documented and reproducible.

If working in R, the previous team used the following packages:

- tidyverse
- lubridate
- scales
- forecast
- tseries
- zoo
- ggplot2
- patchwork
- knitr
- kableExtra

If working in Python, equivalent packages would include pandas, numpy, matplotlib, statsmodels, and pmdarima.

## Deliverables

Per the rubric, your final submission should include:

- A public GitHub repository containing your code, data, and writeup
- A written report (PDF, 5-8 pages) covering Goal Statement, Research Question, Data, EDA, Methodology, Results, Limitations, and Next Steps
- A README that orients a reader to your repository

## Acknowledgements

This case study was created by Jensen Harvey for DS 4002 (Spring 2026), based on the Project 2 work of Jensen Harvey, Kaitlyn Chou, and Emily Friedman. Special thanks to the DS 4002 instructional team.

Rubric structure adapted from the CS3 assignment template (Streifer & Palmer, 2020).
