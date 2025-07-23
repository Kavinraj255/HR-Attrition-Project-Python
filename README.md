📊 HR Employee Attrition Analysis – Logistic Regression

📁 Project Overview
This project focuses on predicting employee attrition (whether an employee will leave the company) using logistic regression. It uses the publicly available HR-Employee-Attrition dataset and applies data preprocessing, modeling, and various visualizations to understand and explain patterns behind attrition.

🧠 Objectives
Predict employee attrition using Logistic Regression

Identify key features contributing to attrition

Visualize attrition trends and correlations in the dataset

Evaluate model performance with metrics and plots

🔧 Technologies & Libraries Used
Python

Pandas, NumPy

Scikit-learn (LogisticRegression, train_test_split, etc.)

Seaborn & Matplotlib for visualizations

🛠 Features Implemented
Data Preprocessing

Converted categorical variables using One-Hot Encoding

Dropped irrelevant columns like EmployeeNumber, Over18, etc.

Handled scaling using StandardScaler

Modeling

Applied Logistic Regression to predict the Attrition column

Used train-test split for evaluation

Model Evaluation

Accuracy Score

Confusion Matrix with heatmap visualization

Classification Report (Precision, Recall, F1-score)

Visualizations

📊 Column Chart: Shows count of employees who stayed vs left

🥧 Pie Chart: Percentage split of attrition

🔥 Heatmap: Correlation between features

📉 ROC Curve (optional if implemented)

📌 Results
The model achieved [insert your model accuracy here]% accuracy

Correlation heatmap highlighted features like JobSatisfaction, OverTime, MonthlyIncome, etc., as strong indicators of attrition

Visualizations help stakeholders quickly understand patterns and problem areas
