
# 📊 Company Bankruptcy Prediction Using Machine Learning Algorithms

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-Completed-brightgreen.svg)]()

> Predicting corporate bankruptcy using advanced ML algorithms with 100% accuracy  
> Taiwan Companies Financial Dataset (1999–2018) | 📅 Completed: May 2025  
> 🎓 National Research University Higher School of Economics – Master’s in Business Analytics & Big Data Systems

---

## 🧠 Project Overview

This project presents a machine learning-based approach to predict **corporate bankruptcy** using financial data. It compares six algorithms and applies advanced preprocessing, SMOTE balancing, feature selection, and hyperparameter tuning.

📌 **Best Result:** `Random Forest` – F1-Score: `1.00`, ROC-AUC: `0.996`, Accuracy: `100%`

---

## 🗃️ Dataset

- **Source**: Taiwan Company Bankruptcy Dataset (1999–2018)
- **Instances**: 6,819 companies
- **Features**: 96 financial ratios (liquidity, profitability, leverage, efficiency)
- **Label**: `Bankrupt` or `Non-Bankrupt` (binary)

---

## 🛠️ Tools & Libraries

- Python 3.10  
- `scikit-learn`  
- `imbalanced-learn` (SMOTE)  
- `XGBoost`, `LightGBM`  
- `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 🤖 Machine Learning Models

- ✅ Random Forest *(Best performing model)*
- ✅ XGBoost
- ✅ LightGBM
- ✅ Logistic Regression
- ✅ K-Nearest Neighbors (KNN)
- ✅ Multi-Layer Perceptron (MLP)

---

## 🔁 Workflow

1. 📥 **Data Preprocessing**: Missing value check, normalization
2. 📊 **Feature Selection**: Correlation threshold > 0.15 → 21 features
3. ⚖️ **Class Imbalance Handling**: SMOTE oversampling
4. 🤖 **Model Training & Evaluation** (Stratified K-Fold CV)
5. 🔍 **Hyperparameter Tuning** using GridSearchCV
6. 📈 **Model Evaluation**: F1-score, Recall, ROC-AUC
7. 📉 **Feature Importance & ROC Curve Analysis**

---

## 📈 Results Summary

| Model               | F1-Score | Recall | ROC-AUC | Accuracy |
|--------------------|----------|--------|---------|----------|
| **Random Forest**   | **1.00** | **1.00** | **0.996** | **100%** |
| XGBoost             | 1.00     | 1.00   | 0.994   | 100%     |
| LightGBM            | 0.81     | 1.00   | 0.994   | 99%      |
| Logistic Regression | 0.28     | 0.87   | 0.93    | 85%      |
| KNN                 | 0.49     | 1.00   | 0.979   | 93%      |
| MLP                 | 0.23     | 0.92   | 0.94    | 80%      |

---

## 📁 Project Structure

```
📦 bankruptcy-prediction/
├── notebooks/           # Jupyter notebooks for modeling
├── data/                # Dataset files
├── requirements.txt     # Python dependencies
└── README.md            # Project description (this file)
```

---

## 📊 Visualizations

- 🔥 Correlation heatmap  
- 📉 ROC curves  
- 📋 Confusion matrices  
- ⭐ Feature importance (Random Forest, XGBoost)

---

## ✍️ Authors

- 👨‍🔬 **Engr. Talha Nazir** – [LinkedIn](https://www.linkedin.com/in/engr-talha-nazir-7b7790201/)  
  *Machine Learning Engineer & AI Researcher*  
- Koyam Moopa Mohammad Sinan  
- Muhammad Ahsan  
- Bernadeth Vanesha Setiawan  

👨‍🏫 **Under the Supervision of [Dmitry Pshichenko](https://www.hse.ru/en/org/persons/795141317/#sci)**  
*Associate Professor, The national research university higher school of Economics, Moscow*

---

## 🧭 Recommendations

- Use ensemble models (RF, XGBoost, LightGBM) for high accuracy.
- Always handle class imbalance with SMOTE or similar methods.
- Apply feature selection before modeling for interpretability.
- Use SHAP/feature importance to explain decisions.

---

## 🔮 Future Scope

- ✅ Real-time bankruptcy monitoring with streaming data
- ✅ Integrate macroeconomic + textual data (news, sentiment)
- ✅ Try deep learning (e.g., RNNs, CNNs)
- ✅ Build explainable dashboards with Streamlit or Gradio

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
**For academic and non-commercial use only.**

---

## 📬 Contact

**Talha Nazir**  
📧 Email: tnazir@edu.hse.ru  
📍 Moscow, Russia

---
