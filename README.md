# 🚀 Employee Attrition Prediction Using Random Forest

![Analytics](https://img.shields.io/badge/Data-Analysis-blue) ![ML](https://img.shields.io/badge/ML-RandomForest-green) ![Python](https://img.shields.io/badge/Python-DataScience-yellow)

## 📊 Project Overview
Employee attrition is a crucial HR concern, and predicting it can save organizations both time and money. This project explores a real-world dataset of 1,470 employees and builds a predictive model using **Random Forest Classifier**.

## 📁 Dataset
- Source: IBM HR Analytics Employee Attrition & Performance
- Features: 35 columns including demographics, work experience, salary, job role, and more.
- Target: `Attrition` (Yes/No)

## ⚙️ Key Steps
- 🧹 **Data Cleaning**: Handled categorical variables and one-hot encoding
- 📌 **Feature Engineering**: Transformed boolean & categorical data to numerical
- 📈 **Model Training**: Achieved **87.41% accuracy** using RandomForestClassifier
- 🧠 **Feature Importance**: Analyzed top factors causing attrition

## 🔍 Top Attrition Factors
      1. MonthlyIncome
      2. OverTime
      3. TotalWorkingYears
      4. Age
      5. DailyRate
## 📊 Visualizations
    Histograms of key features

Bar plot of feature importances
    <p align="center"> <img src="https://github.com/InshaSadaf/Employee-Attrition-Analysis/blob/main/Important%20feature%20plt.png" width="600"> </p>
## 🛠️ Tech Stack
    -  Python, Pandas, NumPy
    -  Matplotlib, scikit-learn

## 📌 Final Insight
      OverTime and low Monthly Income are significant indicators of employee attrition. Invest in work-life balance and fair compensation to improve retention.
