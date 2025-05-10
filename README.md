# 🛡️ Credit Card Fraud Detection Using Machine Learning

Detecting fraudulent credit card transactions is a high-impact, real-world problem that requires balancing **accuracy**, **recall**, and **precision**, especially when fraud cases are extremely rare.

This project explores and compares multiple machine learning models to identify fraudulent transactions using the **Kaggle Credit Card Fraud Detection dataset** — with special focus on **handling class imbalance**, **model evaluation**, and **real-world trade-offs**.

---

## 📌 Problem Overview

- Dataset: 284,807 transactions
- Fraud cases: 492 (only **0.17%**)
- Goal: Build a model that **detects fraud reliably** while **minimizing false alarms**

---

## 🎯 Objectives

- Handle extreme class imbalance
- Train multiple classification models
- Optimize for **recall** (catching fraud) and **precision** (avoiding false positives)
- Use industry-grade metrics: **F1 Score**, **ROC AUC**, **Precision-Recall Curves**
- Select the best model for real-world deployment

---

## 🛠️ Tools & Technologies

- Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- XGBoost, Random Forest, Logistic Regression
- SMOTE for oversampling minority class
- ROC AUC, Confusion Matrix, PR Curve

---

## 🧠 Models & Results

| Model              | Precision | Recall | F1 Score | ROC AUC | False Positives |
|-------------------|-----------|--------|----------|---------|------------------|
| Logistic Regression | 6.1%     | **91.8%**  | 11.4%    | 0.9722  | 1,389            |
| Random Forest       | **82.5%**    | 81.6%  | **82.0%**    | 0.9688  | 17               |
| XGBoost             | 73.1%    | **88.8%**  | 80.2%    | **0.9792** | 32               |

### ✅ **Best Model: XGBoost**
- Best overall balance of **precision and recall**
- **Highest ROC AUC**, indicating strong confidence in predictions
- Ideal for real-world deployment where both catching fraud and minimizing false positives are critical

---

## 🧾 Project Highlights

- Applied **SMOTE** to balance classes without overfitting
- Compared linear (Logistic Regression) and non-linear (RF/XGBoost) classifiers
- Visualized results with PR curves and confusion matrices
- Focused on **interpretable, explainable metrics** for business impact

---

## 💼 Why This Project Matters 

This project demonstrates:
- Proficiency in Python and machine learning workflows
- Understanding of **imbalanced classification**, a real challenge in production
- Ability to communicate model trade-offs for business-critical decisions
- Readiness to build, test, and deploy data-driven solutions in real-world environments


## 📂 Repository Structure

├── creditcards.csv
├── Credit Card Fraud Detection Imbalanced Class.ipyb
└── README.md 

# Project overview

## 📎 Dataset

[🔗 Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)


## 🙋‍♂️ Author

Sammy S. Mutuku  
📍 Nairobi, Kenya | 🌐 [LinkedIn](https://www.linkedin.com/in/samsubu/) | 💻 [GitHub](https://github.com/subu53)  
📧 subusam5@gmail.com

## 🧠 Next Steps

- Add model explainability with SHAP or LIME  
- Build a real-time fraud detection demo with Streamlit  
- Deploy with Flask or FastAPI


⭐ If you find this useful, give it a star or connect on LinkedIn. I'm open to collaboration and opportunities.
