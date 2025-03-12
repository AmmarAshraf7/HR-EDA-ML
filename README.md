# HR Employee Churn: End-to-End ML & EDA (99% Accuracy)

## 📌 Project Overview
This project focuses on analyzing employee churn in an HR dataset using **Exploratory Data Analysis (EDA)** and **Machine Learning (ML) Classification**. The goal is to identify key factors that contribute to employee turnover and build a predictive model with high accuracy.

## 📊 Dataset
The dataset contains various features related to employee performance, satisfaction, and tenure. The target variable is **`left`**, indicating whether an employee has left the company (1) or stayed (0).

### 🔹 Key Features:
- `satisfaction_level`: Employee satisfaction score
- `last_evaluation`: Last performance evaluation score
- `number_project`: Number of projects assigned
- `average_montly_hours`: Average monthly working hours
- `time_spend_company`: Years spent at the company
- `Work_accident`: Whether the employee had a workplace accident
- `promotion_last_5years`: Whether the employee was promoted in the last 5 years
- `Department`: Employee's department
- `salary`: Salary category (low, medium, high)

## 📈 Exploratory Data Analysis (EDA)
EDA was conducted to uncover patterns and relationships between features and employee churn. Key insights:
- **Low satisfaction levels** are highly correlated with leaving.
- Employees working **extremely long or short hours** are more likely to leave.
- **Low salary** significantly increases churn risk.
- Lack of **promotions and accidents** impact churn rates.

## 🏗️ Data Preprocessing
- **Handling Missing Values**: Checked for null values (none found).
- **Encoding Categorical Data**: Used **One-Hot Encoding** for `Department` and `salary`.
- **Outlier Removal**: Used **IQR method**.
- **Feature Scaling**: Applied **StandardScaler** to normalize numerical features.

## 🤖 Machine Learning Model
Several classification models were tested, and the best-performing model achieved **99% accuracy**.

### 🔹 Models Evaluated:
✅ **Logistic Regression**
✅ **Random Forest**
✅ **Gradient Boosting**


💡 **Author:** Ammar  
📌 **Project Status:** Completed ✅  
🚀 **Technologies Used:** Python, Pandas, Seaborn, Scikit-Learn.  
📂 **Dataset:** https://www.kaggle.com/datasets/giripujar/hr-analytics
