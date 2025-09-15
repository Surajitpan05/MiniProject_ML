# MiniProject_ML
📌 Project Overview

This project predicts whether a student prefers to work alone (solo) or in groups (team) using machine learning.
It aims to help faculty form balanced and productive project teams by understanding students’ natural working styles.

📊 Dataset

Source: Data collected via Google Form from students.

Target Variable: teamwork_pref

0 = Prefers Solo

1 = Prefers Team

Features Used:

intro_extro – Introversion/Extraversion score

risk_taking – Risk-taking tendency

club_top1 – Favorite club (categorical)

weekly_hobby_hours – Weekly hobby hours

⚙️ Preprocessing

Dropped missing and irrelevant rows

Encoded categorical data using LabelEncoder

Converted weekly_hobby_hours to numeric (filled missing values with median)

Split data into 80% train / 20% test

Balanced the training data using SMOTE

Scaled features using StandardScaler

🤖 Models Used

Logistic Regression

K-Nearest Neighbors (KNN)
(You can extend this with Decision Trees and Random Forest)

Evaluation Metrics:

Accuracy

F1-Score

Confusion Matrix

Classification Report


💡 Insights

Introversion-extraversion was a strong predictor of teamwork preference.

Students with higher risk-taking scores tended to prefer groups.

Club involvement positively influenced group preference.

🚀 Future Scope

Expand dataset across departments and semesters

Add behavioral/psychological metrics

Experiment with advanced ML models (Random Forest, XGBoost, Deep Learning)

Develop a faculty dashboard for automatic team formation suggestions

📂 Files

project.ipynb – Jupyter notebook with full code

dataset.csv – Collected responses

README.md – Project overview and documentation

📌 Author

Surajit Pan
Machine Learning Mini Project 
