# Skill Based Salary Analysis Using Regression and Statistical Modelling

## 📌 Overview

This project analyzes how different technical skills (Python, SQL, AWS, Tableau, etc.), experience levels, and industry types influence salary levels. The goal is to understand which skills provide the highest salary advantage and to provide data-backed career recommendations.

## 🎯 Objective

* Identify which technical skills correlate with higher salaries.
* Understand how experience and industry modify salary outcomes.
* Build a statistical model to analyze salary predictors.
* Provide actionable career upskilling recommendations.

## 🧹 Step 1 — Data Cleaning & Preparation

* Loaded cleaned Glassdoor job posting dataset.
* Standardized salary values (min, max, average salary).
* Normalized text columns and removed irrelevant features.
* Created binary indicator columns for key skills:
  `python_yn, sql_yn, aws_yn, tableau_yn, spark_yn, r_yn, sas_yn, hadoop_yn, java_yn, excel_yn`
* Verified dataset contained **no missing or duplicate values**.

## 📊 Step 2 — Exploratory Data Analysis (EDA)

* Calculated mean & median salary by skill, job role, and location.
* Visualized salary distributions using histograms and boxplots.
* Identified top-earning skill combinations.
* Key Insight:

  > **Python + SQL + Tableau** profiles earn **20–25% higher salaries** on average.

## 🧠 Step 3 — Statistical Modeling

A multiple linear regression model was built:

```
Salary = β₀ + β₁(Skill) + β₂(Experience) + β₃(Industry)
```

* Used scaling + one-hot encoding via `ColumnTransformer` and `Pipeline`.
* **R² Score ≈ 0.058** → Salary influenced by additional external factors.
* **Highest positive salary impact skills:** SAS, AWS, Python, R, SQL.

## 📈 Step 4 — Visualization & Insights

| Visualization | Purpose                       |
| ------------- | ----------------------------- |
| Bar Chart     | Avg salary by skill           |
| Heatmap       | Salary vs Experience vs Skill |
| Bubble Plot   | Top-paying skill clusters     |

#### ✅ Top 5 Skills by Average Salary

1. SAS
2. AWS
3. Python
4. R
5. Hadoop

## 🚀 Step 5 — Career Recommendations

* Learn **Python + SQL** as foundational skills.
* Add **Tableau/Power BI** for business intelligence.
* Upskill in **AWS / Cloud Data Services** to stand out.
* Build real-world portfolio projects (Dashboards, Analytics Reports).

> **Conclusion:** Developing multi-skill proficiency—especially in data analysis, cloud computing, and business visualization—significantly increases salary and career growth opportunities.

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

## 🏷 Tags

`#DataScience` `#SalaryAnalysis` `#EDA` `#RegressionModel` `#Python` `#CareerInsights`


👤 Contact

Name: Jay Panchal

Email: panchaljay2711@gmail.com

LinkedIn: https://www.linkedin.com/in/jay-panchal-396443176/

GitHub: https://github.com/jay-panchal2711
