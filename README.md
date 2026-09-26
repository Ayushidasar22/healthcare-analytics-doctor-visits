# Healthcare Analytics for Doctor Visits

Exploratory data analysis (EDA) on a healthcare survey dataset to identify which demographic and health-related factors most strongly influence how often a person visits a doctor.

Completed as the capstone DIY project for the **VOIS for Tech Data Analytics Internship** (Edunet Foundation × Vodafone Idea Foundation, AICTE-certified).

## Problem Statement

Doctors are consulted for a wide range of reasons, and visit frequency varies across gender, age, income, and health status. This project analyzes a survey dataset of 5,190 individuals to uncover the patterns behind healthcare utilization.

## Dataset

- **Records:** 5,190
- **Columns:** `visits`, `gender`, `age`, `income`, `illness`, `reduced`, `health`, `private`, `freepoor`, `freerepat`, `nchronic`, `lchronic`
- Source: Australian Health Survey (doctor visits) dataset

## Tools & Libraries

- Python
- Pandas, NumPy — data loading and cleaning
- Matplotlib, Seaborn — data visualization
- Google Colab / Jupyter Notebook

## Analysis Performed

- **Univariate analysis:** gender distribution, age distribution, distribution of doctor visits
- **Multivariate analysis:** visits by gender, visits vs. illness score, age vs. visits (colored by gender)

## Key Findings

- Out of 5,190 respondents, **2,702 are female and 2,488 are male**.
- **~77% of people had zero doctor visits** in the recorded period.
- Females averaged **0.36 visits** vs. **0.24 visits** for males.
- **Illness score is the strongest driver of visit frequency** — mean visits rise from 0.08 (illness score 0) to 0.81 (illness score 5).
- Age distribution peaks among young adults (~20) and near retirement age (~70); age alone shows no strong linear relationship with visit count.

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/healthcare-analytics-doctor-visits.git
   cd healthcare-analytics-doctor-visits
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Healthcare_Analytics_for_Doctor_Visits.ipynb` in Jupyter Notebook or upload it to [Google Colab](https://colab.research.google.com) along with `doctor_visits.csv`.
4. Run all cells.

## Repository Structure

```
├── Healthcare_Analytics_for_Doctor_Visits.ipynb   # Main analysis notebook
├── doctor_visits.csv                              # Dataset
├── requirements.txt                                # Python dependencies
└── README.md
```

## Author

**Ayushi Dasar**
B.Tech Data Science, Gyan Ganga Institute of Technology and Sciences
[LinkedIn](https://www.linkedin.com/in/ayushi-dasar-34226b34a) · [GitHub](https://github.com/Ayushidasar22)
