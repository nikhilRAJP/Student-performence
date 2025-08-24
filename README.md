STUDENT PERFORMANCE

#Project Overview

This project builds and compares multiple machine learning models to predict students’ math scores based on demographic and academic features.

Key Steps

1. Data Preparation

* Loaded dataset (Stud.csv) containing features like gender, race/ethnicity, parental education, and lunch type.

 * Split data into input features (X) and target (math_score).

* Encoded categorical columns so models can use them effectively.

2. Exploratory Analysis

* Inspected data distributions and categories.

* Identified patterns that may influence math performance.

3. Model Training & Evaluation

* Tested a wide range of regression models:

    * Linear (Linear Regression, Ridge, Lasso)

    * Tree-based (Decision Tree, Random Forest, AdaBoost)

    * Instance-based (KNN)

    * Advanced boosting (XGBoost, CatBoost)

    * Support Vector Regressor

* Evaluated using standard metrics: R² score, MAE, and MSE.

* Compared performance to find the best-performing model.

4. Hyperparameter Tuning

* Used RandomizedSearchCV to optimize key model parameters for better accuracy.

5. Results

* Visualized Performance of each model with comparison plots.

* Identified the model that generalizes best on unseen data.

Outcome

* Provides an end-to-end machine learning pipeline: from raw data to tuned, evaluated models.

* Easily adaptable to other regression tasks with similar structure.
