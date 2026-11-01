# Titanic Survival: Exploratory Data Analysis

## Objective
To identify the factors that influenced passenger survival on the Titanic.

## Dataset
891 passengers, 12 variables (age, sex, class, fare, survival status, etc.).
Source: https://github.com/datasciencedojo/datasets

## Methodology
- Data quality check (missing values, duplicates)
- Data cleaning (median imputation for Age, mode for Embarked, dropped Cabin)
- Exploratory analysis and visualizations
- Hypothesis testing (chi-square tests and Welch's t-test)

## Key Findings
- Women survived at ~74% versus ~19% for men.
- Survival rate declined with passenger class (63% / 47% / 24%).
- Children had the highest survival rate among age groups (58%).
- Survivors paid a higher average fare than non-survivors (48.4 vs 22.1).
- All differences were statistically significant (p < 0.05).

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

## How to Run
Open `Titanic_EDA.ipynb` in Google Colab and select Runtime > Run all.

## Author
ATHAMBAWA FATHIMA ANEESIYA
LinkedIn: https://www.linkedin.com/in/abf-aneesiya-850646340/
