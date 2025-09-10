# Online Payments Fraud Detection

This project builds and evaluates **binary classifiers** to detect **fraudulent online transactions** using **Python**. The focus is on clear metrics and reproducible evaluation rather than complex deployment details.

---

## 📊 Project Description

The notebook covers:

1. **Exploratory Data Analysis (EDA)** – basic inspection and sanity checks.
2. **Preprocessing** – minimal cleaning and train/validation split.
3. **Models** – **k‑Nearest Neighbors (KNN)**, **Logistic Regression**, and **Decision Trees**.
4. **Evaluation** – **k‑fold cross‑validation** with the following metrics:

   * Accuracy
   * Sensitivity / Recall
   * Specificity
   * Precision
   * F1 Score
   * Matthews Correlation Coefficient (MCC)
   * Mean Accuracy and Std. Dev. across folds

> Note: The notebook does **not** include gradient boosting, XGBoost, SMOTE, SHAP, or other techniques beyond the models listed above.

---

## 🛠️ Requirements

```bash
pip install -r requirements.txt
```


