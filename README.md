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

See `requirements.txt` in this repository. Use any environment tool you prefer (e.g., `venv`, Conda).

---

## 🚀 Usage

Clone the repository and open the notebook:

```bash
git clone https://github.com/MihaiBudurean/OnlinePaymentsFraudDetection.git
cd OnlinePaymentsFraudDetection
pip install -r requirements.txt
```

Then open **`OnlinePaymentsFraudDetection.ipynb`** in Jupyter (or VS Code) and run the cells.

---

## 📈 Results

The notebook reports cross‑validated performance for KNN, Logistic Regression, and Decision Trees using the metrics above. Include (optional) a small results table or plots saved from the notebook for quick preview in the repo.

---

## 📂 Files

* `OnlinePaymentsFraudDetection.ipynb` – Main notebook with analysis and results
* `requirements.txt` – Python dependencies
* `README.md` – This file

