# Heart Disease Risk Factor Analysis
> End-to-end EDA on UCI Heart Disease dataset using Python, Pandas, and Seaborn

## Overview
This project performs exploratory data analysis on the UCI Heart Disease dataset to identify key clinical risk factors associated with heart disease. The analysis covers data cleaning, feature exploration, visualisation, and age-stratified risk segmentation across 303 patients and 13 clinical features.

---

## Key Findings
- **Chest pain type** and **max heart rate** are the strongest predictors of heart disease presence
- Sex-based risk differential: 75% disease rate in females vs 44.7% in males *(within this dataset, n=303)*
- Age-stratified segmentation revealed sample imbalance in the under-40 cohort (n=18) — statistical limitations documented

---

## Project Structure
| File | Description |
|------|-------------|
| `heart_disease_eda.ipynb` | Main analysis notebook (EDA, visualisations, findings) |
| `heart.csv` | UCI Heart Disease dataset (303 patients, 13 features) |

---

## Analysis Breakdown

### 1. Data Cleaning
- Validated zero null values across all 13 features
- Encoded categorical variables (chest pain type, resting ECG, slope, thal)
- Confirmed data types and prepared dataset for analysis

### 2. Exploratory Data Analysis
- Age distribution across disease-positive and disease-negative patients
- Cholesterol and resting blood pressure trends
- Max heart rate vs age relationship
- Sex breakdown and disease prevalence
- Chest pain type frequency and correlation with disease

### 3. Visualisations (Seaborn)
6 clinical charts built with written insights for non-technical audiences:
- Age distribution histogram
- Cholesterol box plot by disease status
- Max heart rate scatter plot
- Sex breakdown bar chart
- Chest pain type count plot
- Correlation heatmap across all 13 features

### 4. Risk Segmentation
- Age-stratified analysis (Under-40 / 40–55 / 55+)
- Statistical reliability flag raised for under-40 cohort (n=18)

---

## Tools & Libraries
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
- **Environment:** Google Colab

---

## Dataset
UCI Heart Disease Dataset — publicly available via [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease).
303 patients, 13 clinical features including age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, and more.

---

## Author
**Neeraja Shah** — BTech AIML, DJSCE Mumbai
[LinkedIn](https://linkedin.com/in/neeraja-shah-5450812a1) • [GitHub](https://github.com/neerajashah)
