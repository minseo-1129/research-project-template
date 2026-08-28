# Research Project Template

A reusable starting point for project-based statistical analysis and research documentation.

## Research overview

**Research question**  
Write the main research question here.

**Study / dataset**  
Describe the study, sample, source, and unit of analysis. Do not commit restricted, identifiable, or institution-only data.

**Methods**  
List the statistical methods, models, or analyses used in the project.

**Tools**  
Python / R / Stata / other tools used for the analysis.

**Status**  
Planning / data preparation / analysis / writing / complete.

## Analysis workflow

1. `notebooks/01-data-preparation.ipynb` — cleaning, coding, exclusions, derived variables
2. `notebooks/02-analysis.ipynb` — descriptive statistics and statistical models
3. `notebooks/03-visualization.ipynb` — publication-ready figures and result summaries

## Repository structure

```text
.
├── README.md
├── notebooks/
│   ├── 01-data-preparation.ipynb
│   ├── 02-analysis.ipynb
│   └── 03-visualization.ipynb
├── data/
│   └── README.md
├── figures/
│   └── .gitkeep
├── src/
│   └── .gitkeep
├── requirements.txt
└── .gitignore
```

## Main findings

Add a short plain-language summary of the key result here once the analysis is stable.

## Reproducibility

Record package versions, important analytic decisions, exclusion criteria, model specifications, and random seeds where relevant.

## Data note

This template intentionally does not include research data. For public repositories, use open, de-identified, synthetic, or otherwise shareable data only.
