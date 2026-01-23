#  Student Exam Score Prediction

This project focuses on predicting students' final exam scores based on various demographic and behavioral factors such as study hours, attendance, and sleep quality.

##  Project Overview
The goal is to build a high-performance regression model that can accurately estimate exam results, helping educators identify students who might need additional support.

##  Key Steps Taken
- **Data Preprocessing:** Handled categorical variables and applied **StandardScaler** to numerical features for model optimization.
- **Feature Engineering:** Created new indicators like `study_efficiency` to capture deeper insights.
- **Model Training:** Evaluated multiple algorithms, including Random Forest, SVR, and Gradient Boosting.
- **Ensemble Learning:** Implemented a **Voting Regressor** to combine the strengths of different models.

##  Results
The **Ridge Regression** model emerged as the best performer with:
- **R² Score:** 0.733
- **MAE:** 7.86
- **RMSE:** 9.76

##  Top 10 Influential Features
