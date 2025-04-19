

# IBM HR Analytics Employee Attrition & Performance

---

## Project Overview

Employee attrition is a significant challenge for organizations, leading to increased recruitment, hiring, and training costs, as well as loss of productivity and institutional knowledge. This project aims to analyze the IBM HR dataset to uncover the key factors influencing employee attrition and performance, and to build predictive models to identify employees at risk of leaving. The insights generated can help HR departments implement targeted retention strategies and improve workforce management.

---

## Problem Statement

Organizations invest heavily in hiring and nurturing employees. However, employee attrition, especially among key resources, can cause substantial losses. Attrition may result from low salaries, limited career growth, poor supervision, lack of recognition, or inadequate work conditions. Predicting attrition risk allows HR to proactively retain valuable employees or plan preventive hiring to minimize organizational impact.

---

## Objectives

- Analyze demographic and job-related factors influencing employee attrition.
- Explore relationships between features such as salary, job satisfaction, work-life balance, and attrition.
- Build machine learning models to predict employee attrition.
- Evaluate model performance using metrics like accuracy, F1-score, and ROC-AUC.
- Provide actionable recommendations to reduce attrition and enhance employee engagement.

---

## Dataset Description

The dataset is a fictional HR analytics dataset created by IBM data scientists, containing 1,470 employee records with 35 features including:

- Demographics: Age, Gender, Marital Status, Education, Education Field
- Job-related: Department, Job Role, Job Level, Business Travel, OverTime
- Performance and Satisfaction: Performance Rating, Job Satisfaction, Environment Satisfaction, Work-Life Balance
- Compensation: Monthly Income, Percent Salary Hike, Stock Option Level
- Other: Distance From Home, Years at Company, Training Times Last Year, etc.

The target variable is `Attrition` (Yes/No).

---

## Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Machine Learning Algorithms (Decision Tree, Random Forest, Logistic Regression)
- SQL and Excel for data exploration and preprocessing

---

## Methodology

### Data Cleaning & Preparation
- Load and inspect the dataset for missing values and duplicates (none found).
- Convert categorical variables to numeric using encoding techniques.
- Perform feature selection and engineering to improve model input.
- Split data into training and testing sets.

### Exploratory Data Analysis (EDA)
- Visualize attrition distribution across demographics and job roles.
- Analyze correlations between attrition and factors like income, job satisfaction, and overtime.
- Use plots such as bar charts, box plots, and heatmaps for insights.

### Model Building & Evaluation
- Handle class imbalance using stratified sampling.
- Train models including Decision Tree and Random Forest classifiers.
- Use 5-fold cross-validation to assess model generalization.
- Evaluate models with accuracy, F1-score, and ROC-AUC metrics.
- Example result: ROC-AUC of 0.61 and F1 score of 0.81 for Decision Tree model.

---

## Key Findings & Suggested Actions

- Improve Work Conditions:
  Offer flexible work arrangements and ergonomic workspaces to boost employee satisfaction and work-life balance.

- Competitive Compensation:  
  Provide equitable salaries and perks such as flexible schedules and travel discounts to retain critical employees.

- Enhance Employee Engagement:  
  Encourage skill development and job involvement to reduce boredom and increase retention.

---

## Repository Contents

- Data Folder: Contains the raw IBM HR Analytics dataset (downloadable from [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset))
- Attrition Analysis Report: Detailed project summary and insights (`Attrition_Analysis_report.pdf`)
- Source Code: Jupyter notebook with data preprocessing, EDA, model building, and evaluation (`Employee-Attrition-Analysis_DT.ipynb`)

---

