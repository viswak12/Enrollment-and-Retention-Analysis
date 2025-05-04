# Enrollment and Retention Analysis Project

This project focuses on identifying the key drivers behind student enrollment decisions using a structured dataset of admitted undergraduate students. The goal is to apply statistical techniques and machine learning to analyze yield trends and build a predictive model that supports data-driven enrollment strategies.

## 📊 Objective

The assignment involved analyzing a dataset of high school students who were admitted to a university. Using descriptive statistics and a machine learning model (Random Forest Classifier), the analysis aims to:

- Explore enrollment yield across factors like GPA, FAFSA status, scholarship tier, discount rate, and college admitted to.
- Identify the most influential variables affecting a student’s decision to enroll.
- Provide initial recommendations for increasing enrollment yield.

## 🧾 Dataset Summary

The dataset includes:
- **College Admitted To** (8 academic colleges)
- **FAFSA Application Status** (Yes/No)
- **Merit Scholarship Received** (Yes/No) + Scholarship Tier (CTA to USB)
- **Discount Rate Offered** (percentage)
- **State of Residency** (2-letter abbreviation)
- **Enrollment Decision** (Yes/No)
- **Recalculated High School GPA**

GPA values of 0/NA indicate missing entries.

## 🧠 Methodology

- **Data Cleaning**: Handled missing values, encoded categorical variables, and balanced classes using undersampling and SMOTE.
- **Modeling**: Trained a Random Forest Classifier to predict the likelihood of enrollment.
- **Feature Importance**: Used the trained model to rank the most predictive factors.

## 🔍 Key Insights

- FAFSA application status, GPA, and the college to which a student was admitted were the strongest predictors of enrollment.
- Higher merit scholarship tiers slightly increased yield but had diminishing returns beyond a certain point.
- Students with a GPA between 3.0 and 4.0 showed higher enrollment probabilities.

## 🛠 Tools & Libraries

- Python
- pandas, numpy
- scikit-learn
- imblearn (SMOTE)
- matplotlib / seaborn
- Jupyter Notebook

## 📁 Repository Structure

