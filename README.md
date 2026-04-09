# Forest Fire Prediction (Regression Models Comparison)

This project is an end-to-end Machine Learning application that predicts the **area affected by forest fires** using meteorological and environmental features. The project focuses on comparing multiple regression techniques including **Linear Regression, Ridge, Lasso, and ElasticNet**, along with cross-validation to improve model generalization.

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature correlation and visualization
* Implementation of multiple regression models:

  * Linear Regression
  * Ridge Regression
  * Lasso Regression
  * ElasticNet Regression
* Hyperparameter tuning using Cross-Validation
* Model performance comparison
* Evaluation using RMSE and R² Score

## Tech Stack

* Python (Pandas, NumPy, Scikit-learn)
* Matplotlib & Seaborn (EDA & Visualization)
* Jupyter Notebook / Python Scripts

## Models Used

* **Linear Regression** – Baseline model
* **Ridge Regression** – Reduces overfitting using L2 regularization
* **Lasso Regression** – Performs feature selection using L1 regularization
* **ElasticNet** – Combines both L1 and L2 regularization

## Evaluation Metrics

* R² Score
* Root Mean Squared Error (RMSE)
* Cross-validation scores for model stability

## How It Works

1. Load and preprocess the forest fire dataset
2. Perform EDA to understand feature relationships
3. Train multiple regression models
4. Apply cross-validation for better generalization
5. Compare performance and select the best model

## Run Locally

```bash
pip install -r requirements.txt
python application.py
```

## Key Insights

* Regularization techniques help reduce overfitting
* Lasso can eliminate irrelevant features
* ElasticNet provides a balance between Ridge and Lasso
* Cross-validation improves model reliability


---

⭐ If you found this project useful, consider giving it a star!
