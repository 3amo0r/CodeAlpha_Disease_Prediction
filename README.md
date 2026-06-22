# Disease Prediction using Machine Learning

This project is the fourth task of my internship at **CodeAlpha**. It focuses on predicting the likelihood of diseases (specifically Diabetes) based on medical health metrics.

## Project Overview
- **Objective:** To build a robust classification model that predicts disease presence from structured medical data.
- **Data:** Used the Diabetes dataset (UCI Machine Learning Repository).
- **Techniques:**
    - Data Preprocessing & Scaling (StandardScaler).
    - Model Training: Logistic Regression, Random Forest, and XGBoost.
    - **Hyperparameter Tuning:** Optimized the Random Forest model using `GridSearchCV` to achieve the best configuration (`max_depth: 10`, `min_samples_split: 5`, `n_estimators: 100`).
- **Key Visualizations:** Analyzed **Feature Importance** to understand which medical factors contribute most to the prediction.

## Performance
The final model achieved an F1-score of 0.63 for disease detection. The analysis prioritizes balancing precision and recall to ensure reliable medical decision-making.

## How to run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the `Disease_Prediction.ipynb` notebook.
3. Observe the Feature Importance plot to see key medical indicators.

## Tools
- Python
- Scikit-Learn
- XGBoost
- Matplotlib (for visualization)
