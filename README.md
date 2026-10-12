# Student Performance Statistical Analysis

## Project Overview
An exploratory and inferential statistical analysis of student performance data using Python. The project examines differences in final grades across student groups and investigates the association between school absences and final grades.

## Research Questions
1. Does final grade differ by sex?
2. How does final grade vary across study-time groups?
3. Do final grades differ by number of previous failures?
4. Is school absence associated with final grade?

## Methods
- Data auditing and descriptive statistics
- Exploratory data analysis and visualization
- Shapiro-Wilk normality test
- Mann-Whitney U test
- Kruskal-Wallis test
- Pearson and Spearman correlation
- Rank-biserial effect size

## Key Findings
- Final grades differed significantly between female and male students.
- Descriptive statistics showed differences in grades across study-time groups.
- Final grades differed significantly across previous-failure groups (Kruskal-Wallis, p < 0.001).
- Absences had a weak negative association with final grades (Spearman's rho = -0.159, p < 0.001).

## Tools
Python, Pandas, NumPy, SciPy, Matplotlib, Seaborn, Jupyter Notebook.

## Dataset
Source: [Student Performance Dataset on Kaggle](https://www.kaggle.com/datasets/larsen0966/student-performance-data-set/data)

## Limitations
The analysis is observational and cannot establish causation. Findings may not generalize to other student populations. Some groups have small sample sizes, and statistical significance does not necessarily imply practical importance.
