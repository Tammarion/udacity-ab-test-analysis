# Analyze A/B Test Results

**Udacity Statistics Project | Python · Pandas · NumPy · Statsmodels**

---

## Project Overview

Statistical analysis of an A/B test run by an e-commerce website to determine whether a new page design produces a statistically significant improvement in conversion rates over the existing page.

**Goal:** Recommend whether the company should implement the new page, keep the old page, or run the experiment longer before deciding.

---

## Analysis Sections

- **Part I — Descriptive Statistics** — shape, distributions, and summary stats of the dataset
- **Part II — Probability** — baseline conversion rates by group
- **Part III — Hypothesis Testing** — z-test, p-values, and sampling distributions
- **Part IV — Logistic Regression** — modeling conversion as a function of page and other variables

---

## Key Findings

The data does not provide sufficient evidence to conclude that the new page performs better than the old page. The p-value from hypothesis testing failed to reach statistical significance, and the logistic regression confirmed no meaningful difference in conversion rates between groups. The recommendation is to either keep the old page or run the experiment longer to gather more data.

---

## Files

| File | Description |
|------|-------------|
| `Analyze_AB_Test_Results.ipynb` | Full analysis notebook |
| `analyze-a_b-test-results.pdf` | Project report |

---

## Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5?style=flat&logo=python&logoColor=white)

---

## How to Run

```bash
pip install pandas numpy matplotlib statsmodels jupyter
jupyter notebook Analyze_AB_Test_Results.ipynb
```

---

*Project completed as part of the Udacity Data Analysis and Descriptive Statistics Nanodegree*
