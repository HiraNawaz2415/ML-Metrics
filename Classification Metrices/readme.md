## What are Classification Metrics?
Classification metrics are quantitative measures that evaluate how well a classification model (like Logistic Regression, Decision Tree, Random Forest, SVM, etc.) performs.

They help you answer:
 Is the model accurate?
 Is it missing too many positive/negative cases?
 Is it biased toward one class?

They are especially important when you have imbalanced classes (e.g., fraud detection, disease diagnosis).

## 📊 Key Classification Metrics

Below are the most commonly used evaluation metrics for classification problems:

---

### 1️⃣ **Accuracy**
- **Definition:** Proportion of total correct predictions.
- **Formula:**  
  \[
  \text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}
  \]
- Good when classes are balanced.
- Can be misleading for imbalanced classes (e.g., if 95% of data is negative).

---

### 2️⃣ **Precision**
- **Definition:** Out of all positive predictions, how many were actually positive?
- **Formula:**  
  \[
  \text{Precision} = \frac{TP}{TP + FP}
  \]
- Useful when False Positives are costly (e.g., spam detection).

---

### 3️⃣ **Recall** (*Sensitivity*, *True Positive Rate*)
- **Definition:** Out of all actual positives, how many did the model correctly detect?
- **Formula:**  
  \[
  \text{Recall} = \frac{TP}{TP + FN}
  \]
- Useful when False Negatives are costly (e.g., cancer detection).

---

### 4️⃣ **F1-Score**
- **Definition:** Harmonic mean of Precision and Recall. Balances the two.
- **Formula:**  
  \[
  \text{F1} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}
  \]
- Good choice for imbalanced classes.

---

**TP** = True Positive  
**TN** = True Negative  
**FP** = False Positive  
**FN** = False Negative

---

>  **Tip:** Use multiple metrics to get a clearer view of your model’s performance!


