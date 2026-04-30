# FRACTURE-RELATED INFECTION (FRI) ANALYSIS

## Overview

This project presents a comprehensive **10-year retrospective analysis** of Fracture-Related Infection (FRI) cases at **Hospital Universiti Sains Malaysia (2014-2023)**. The analysis includes demographic characteristics, temporal trends, risk factors, microbiological profiles, antibiotic treatment patterns, and treatment outcomes for **85 patients** with confirmed FRI.

---

## Objectives

| Objective | Description |
|-----------|-------------|
| **SO1** | To describe the pattern of reported FRI cases from 2014 to 2023 |
| **SO2** | To determine the predisposing factors contributing to FRI |
| **SO3** | To describe the types of organisms, antibiotic treatment patterns, and treatment given |

---

## Key Findings

| Domain | Finding |
|--------|---------|
| **Total patients** | 85 cases |
| **Mean age** | 38.2 years |
| **Gender predominance** | Male (75.3%), ratio 2.3:1 |
| **Most affected age group** | 18-40 years (41.2%) |
| **Top risk factors** | Male gender (75.3%), Plating (52.9%), Smoking (42.4%) |
| **Most common pathogen** | *Staphylococcus aureus* (34.1%) |
| **Second most common** | *Pseudomonas aeruginosa* (18.8%) |
| **Primary treatment** | IV antibiotics + surgery (78-100%) |
| **Temporal trend** | Increasing (from 7 to 9 cases annually) |

---

## Research Questions Answered

| RQ | Question | Answer |
|----|----------|--------|
| 1 | How has the pattern changed over years? | Increasing trend observed |
| 2 | What risk factors contribute to FRI? | Male gender, Plating, Smoking |
| 3 | What are the most common microorganisms? | *S. aureus* (34.1%), *P. aeruginosa* (18.8%) |
| 4 | What are the antibiotic treatment patterns? | Gentamicin most broadly used |
| 5 | Are there changes in treatment given? | IV + surgery remained standard (78-100%) |

---

## Features

- ✅ Automated data cleaning and preprocessing
- ✅ visualizations (300 DPI figures)
- ✅ Descriptive statistical analysis
- ✅ Risk factor ranking and prevalence calculation
- ✅ Microbial distribution analysis
- ✅ Antibiotic treatment pattern heatmaps
- ✅ Temporal trend analysis with year-over-year changes

---

## Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Core programming language |
| Pandas | Data manipulation and analysis |
| Matplotlib & Seaborn | Publication-ready visualizations |
| NumPy & SciPy | Statistical calculations |
| Google Colab | Development environment |

---

## Output Figures

| Figure | Description |
|--------|-------------|
| Figure 1 | Demographics (age distribution, gender, comorbidities) |
| Figure 2 | Temporal trends (annual cases, cumulative, percentage change) |
| Figure 3 | Risk factor prevalence |
| Figure 4 | Microbial distribution (pie chart + bar chart) |
| Figure 5 | Antibiotic treatment patterns (heatmap) |
| Figure 6 | Treatment trends over time |

---

## Project Structure
FRI-Analysis/
│
├── data/
│ └── latest data.xlsx # Raw dataset
│
├── notebooks/
│ └── fri_analysis.ipynb # Main analysis notebook
│
├── output/
│ ├── Figure_1_Demographics.png
│ ├── Figure_2_Temporal_Trends.png
│ ├── Figure_3_Risk_Factors.png
│ ├── Figure_4_Microbial_Distribution.png
│ ├── Figure_5_Treatment_Patterns.png
│ └── Figure_6_Treatment_Trends.png
│
├── README.md # This file
└── requirements.txt # Dependencies

