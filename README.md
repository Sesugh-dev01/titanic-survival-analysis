# Titanic Survival Analysis

Exploratory Data Analysis (EDA) on the Titanic passenger dataset to identify the key factors that determined survival.

![Titanic Analysis](Screenshot.png)

## What I Did
- Loaded and inspected 891 passenger records across 12 variables
- Identified and handled missing values — Age (20% missing), Cabin (77% missing, dropped)
- Visualised survival rates by gender, passenger class, and age group
- Quantified the survival gap between demographic groups

## Key Findings
- Women survived at **74%** vs men at **19%** — the largest single factor
- First-class passengers survived at **63%** vs third-class at **24%**
- Women in first class had a **97%** survival rate; men in third class had **13%**
- Children under 10 had higher survival rates regardless of class

## Business Recommendation
The data shows rescue priority was determined by both gender and economic class, not capacity. Any emergency planning framework today should embed objective triage criteria to prevent social bias from determining who survives a disaster.

## Tools Used
Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

## Setup
```bash
pip install -r requirements.txt
jupyter notebook Titanic_survival.ipynb
```

## Dataset
[Titanic dataset](https://www.kaggle.com/competitions/titanic) — Kaggle
