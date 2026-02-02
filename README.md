# group-exercise-two
Regression Analysis with Preprocessing & Model Enhancement

Project Description

This project focuses on performing regression analysis on a dataset with more than 1000 data points and 30+ features.
The objective is to apply data preprocessing techniques, build and evaluate regression models, and enhance model performance using feature selection and advanced regression methods.
The project demonstrates the complete pipeline from raw data to improved predictive models.

Dataset Information

Dataset Type: Synthetic Regression Dataset

Generation Method: sklearn.datasets.make_regression

Number of Samples: 1200

Number of Features: 30

Target Variable: Continuous numerical value

Purpose: To simulate a real-world, high-dimensional regression problem suitable for model evaluation and enhancement.


Group Members and Contributions
Janvi Mahapadi

Handled the complete implementation of the project

Generated and loaded the dataset

Performed preprocessing including missing value handling, outlier removal, and feature scaling

Built and evaluated regression models

Integrated advanced models and visualizations

Compiled the final notebook and documentation

Devendra Ghawat

Assisted with outlier detection using the Z-score method

Contributed to understanding the impact of outlier removal on regression performance

Kshitija Satpute

Worked on feature selection techniques

Helped analyze the impact of feature selection on model performance

Assisted with documentation and final review

Tasks Performed
1. Preprocessing

Artificial missing values were introduced and handled using mean imputation

Outliers were detected and removed using the Z-score method

Numerical features were scaled using Z-score standardization

Feature selection was performed using a filter-based statistical method (SelectKBest)

2. Model Building and Evaluation

A Linear Regression model was trained on the preprocessed dataset

Model performance was evaluated using:

R² Score

Root Mean Square Error (RMSE)

5-Fold Cross-Validation was performed to ensure model stability

3. Model Enhancement

The impact of feature selection on model performance was analyzed

Residual plots were used to examine prediction errors

Feature importance was visualized using regression coefficients

4. Creativity and Advanced Techniques

Ridge Regression was applied to reduce multicollinearity

Lasso Regression was used for automatic feature selection

Polynomial Regression was implemented to capture non-linear relationships

Performance comparisons were made between all models

Conclusion

This project demonstrates how proper data preprocessing, feature selection, and model enhancement techniques can significantly improve regression performance.
The use of regularization and cross-validation ensured robustness, while visual analysis provided deeper insights into model behavior.
Overall, the project provides a comprehensive understanding of regression modeling on high-dimensional datasets.
