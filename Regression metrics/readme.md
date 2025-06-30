# What Are Regression Metrics?
Regression metrics are used to evaluate the performance of a regression model—i.e., how well the model's predicted values match the actual continuous target values.
## 1. Mean Absolute Error (MAE)
Definition: Average of the absolute differences between predicted and actual values.

**Formula:**

         MAE=1/𝑛∑∣𝑦true−𝑦pred∣

**Interpretation:** Lower is better; how much your predictions are off on average.

---
## 2. Mean Squared Error (MSE)
Definition: Average of the squared differences between predicted and actual values.

**Formula:**

           MAE=1/𝑛∑(𝑦true−𝑦pred)^2
 
**Interpretation** More sensitive to outliers than MAE (because errors are squared).

---

## 3. Root Mean Squared Error (RMSE)
Definition: Square root of MSE. Puts error back in the original unit.

Formula:

    - RMSE=Sqroot(MSE)
 
**Interpretation:** Easier to interpret than MSE.

---
## 4. R-squared (R²) — Coefficient of Determination
Definition: Tells you how much variance in the target is explained by the model.

Range: 0 to 1 (or negative if worse than a straight line)

Formula:

𝑅2=1−SSres/SStot
 
**Interpretation:**

- 1: Perfect prediction

- 0: Model does no better than predicting the mean

- < 0: Model is worse than using the mean


## When to use when

| Metric   | Best For                        | Notes                                  |
| -------- | ------------------------------- | -------------------------------------- |
| **MAE**  | General error understanding     | Less sensitive to outliers             |
| **MSE**  | Emphasizing large errors        | Penalizes big errors more              |
| **RMSE** | Same as above but interpretable | Most commonly reported                 |
| **R²**   | How good is your model overall? | Gives percentage of variance explained |
