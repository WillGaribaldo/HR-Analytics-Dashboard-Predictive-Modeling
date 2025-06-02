# 📊 HR Analytics Dashboard & Predictive Modeling

## 🔍 Overview

This end-to-end project combines **Power BI** for interactive visualization and **Python** for predictive modeling to address HR attrition. The objective was to deliver actionable insights to help HR teams make data-driven decisions around employee retention and workforce planning.

---

## 🧱 Project Components

### 1. Data Preparation

- **Source**: HR dataset (`HR_Data.xlsx`)
- **Cleaning**:
  - Removed duplicates and null values
  - Standardized column formats and renamed fields
- **Feature Engineering**:
  - Created salary range buckets

### 2. Exploratory Data Analysis (EDA)

- Analyzed attrition patterns across:
  - Departments
  - Job roles
  - Salary ranges
  - Tenure
- Identified trends in age and salary affecting retention

### 3. Predictive Modeling (Python)

- **Notebook**: `HR Predictive Model.ipynb`
- **Models**:
  - Logistic Regression
  - Random Forest Classifier
- **Evaluation**:
  - Confusion Matrix
  - Accuracy Score
  - ROC-AUC Curve
- **Output**:
  - Risk score of attrition per employee
  - Results exported and integrated into Power BI dashboard

### 4. Power BI Dashboard

- **Tool**: Power BI Desktop (`HR Analytics Dashboard.pbix`)
- **Layout Overview**:
  - **Top KPIs**:
    - Total Employees
    - Attrition %
    - Average Age
    - Average Monthly Salary
    - Average Years at Company
  - **Visuals**:
    - Matrix: Attrition by Department & Job Level
    - Bar Chart: Attrition by Years at Company
    - Pie Chart: Attrition by Salary Range
    - Bar Chart: Attrition by Job Role
  - **Filters/Slicers**:
    - Department, Job Level, Education
  - **Employee Table**:
    - `EMPID` and predicted attrition risk score

---

## 🧠 Key Learnings

- Integrated machine learning outputs with business dashboards
- Translated data into visuals tailored for HR stakeholders
- Strengthened skills in predictive analytics and BI storytelling

---

## 🛠 Tools & Technologies

- **Power BI** – Dashboard creation and visual storytelling
- **Data Analysis Expression (DAX)** - Create custom measures & columns through DAX
- **Python** – Data prep and modeling with `pandas`, `scikit-learn`, `seaborn`
- **Excel** – Initial data cleaning and exploration
- **Jupyter Notebook** – Model building and evaluation
