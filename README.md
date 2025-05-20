# 🧠 Explainable ML: Predicting Loan Approval with SHAP & LIME

This project builds a machine learning model to predict whether a loan application will be approved. It also uses **explainable AI techniques** like **SHAP** and **LIME** to understand how the model makes its predictions.

---

## 📊 Overview

- **Dataset**: Loan prediction dataset (Kaggle)
- **Goal**: Binary classification - approve or reject loan applications
- **Model**: Random Forest Classifier
- **Explainability**:
  - SHAP for global & local feature importance
  - LIME for instance-level explanations

---

## 🔧 Features

- Data preprocessing (handling nulls, encoding categories)
- Model training & evaluation
- SHAP summary and force plots
- LIME explanations for individual predictions

---

## 📁 Files

- `loan_model.ipynb` — main notebook with code
- `train.csv` — dataset used for training
- `README.md` — project documentation

---

## 🛠 Requirements

- Python 3.10+
- Jupyter Notebook
- pandas, scikit-learn, shap, lime, matplotlib, seaborn

Install everything via conda:

```bash
conda install -c conda-forge shap lime scikit-learn pandas matplotlib seaborn notebook
