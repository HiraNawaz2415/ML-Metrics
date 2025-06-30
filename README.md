## What are ML metrics?
ML metrics are measures used to evaluate how well your machine learning model is performing. They help answer questions like:

How accurate are my predictions?

Where is my model going wrong?

Is my model biased toward certain outcomes?

Should I adjust my model or collect more data?

The right metric depends on:

The type of problem (classification, regression, clustering, etc.)

The dataset (balanced or imbalanced)

## There are two types of metrices used in ml:
 **1.Regression metrices**
 **2.Classification metrices**

## Classification Metrics
| Metric                   | What it tells you                                                               |
| ------------------------ | ------------------------------------------------------------------------------- |
| **Accuracy**             | How many total predictions were correct.                                        |
| **Precision**            | Of the positive predictions, how many were correct?                             |
| **Recall (Sensitivity)** | Of all actual positives, how many did the model catch?                          |
| **F1-Score**             | Harmonic mean of precision and recall — balances them.                          |
| **Confusion Matrix**     | Table showing True Positives, True Negatives, False Positives, False Negatives. |

## Regression Metrics
These are for predicting continuous values, like house prices, temperature, or sales.

| Metric                                      | What it tells you                                              |
| ------------------------------------------- | -------------------------------------------------------------- |
| **Mean Absolute Error (MAE)**               | Average absolute difference between predicted and true values. |
| **Mean Squared Error (MSE)**                | Average squared difference — penalizes larger errors more.     |
| **Root Mean Squared Error (RMSE)**          | Square root of MSE — interpretable in same units as target.    |
| **R² Score (Coefficient of Determination)** | How much variance is explained by the model (1 = perfect).     |





