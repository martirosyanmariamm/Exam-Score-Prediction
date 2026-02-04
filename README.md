#  Exam Score Prediction Analysis

This project predicts students' final exam scores based on demographic and behavioral factors using various regression techniques.

###  Data Source
The dataset used in this project is sourced from **Kaggle**: 
 [Student Performance Factors Dataset]([https://www.kaggle.com/datasets/laotse/student-performance-factors](https://www.kaggle.com/datasets/laotse/student-performance-factors))

*Note: This is a synthetic dataset designed for educational purposes and predictive modeling practice.*

###  Key Technical Steps
* **Data Preprocessing:** Handled categorical variables and performed feature scaling using `StandardScaler`.
* **Exploratory Data Analysis (EDA):** Visualized feature correlations and distributions.
* **Modeling:** Compared multiple algorithms including Ridge, Random Forest, and Gradient Boosting.
* **Ensemble Learning:** Implemented a `VotingRegressor` to combine the strengths of different models.

###  Model Performance Results
| Model | R2 Score |
| :--- | :--- |
| **Ridge Regression** | **0.7332** |
| Voting Ensemble | 0.7322 |
| Random Forest | 0.7185 |

###  Conclusion
The analysis reveals that **Study Hours** and **Class Attendance** are the primary drivers of student success. The Ridge Regression model provided the most accurate and interpretable results for this specific dataset.
