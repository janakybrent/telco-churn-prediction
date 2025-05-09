# 📉 Telco Customer Churn Prediction

Predicting B2B customer churn using machine learning, hyperparameter optimization, and feature engineering to drive proactive retention strategies.

---

## 🧠 Project Summary

Customer churn is a costly problem—especially in B2B industries where client acquisition costs are high. In this project, I used a dataset from a telecom provider to build a predictive churn model using LightGBM. The model achieved:

- **✅ Accuracy**: 84.4%
- **🎯 AUC-ROC**: 0.93

With this model, Telco can now:
- Identify high-risk customers
- Launch targeted retention campaigns
- Reduce churn and protect recurring revenue

---

## 📊 Dataset

- **Source**: Telco customer churn dataset
- **Size**: 7,043 records
- **Features**: Contract type, tenure, payment method, monthly/total charges, and more
- **Target**: `Churn` (binary classification)

---

## 🧪 Key Techniques

| Task                     | Tool / Method                                |
|--------------------------|----------------------------------------------|
| Data Cleaning            | `pandas`, `numpy`                            |
| Feature Engineering      | `ChargePerMonthRatio`, `TenureContractInteraction` |
| Imbalanced Classes       | SMOTE (Synthetic Minority Oversampling)      |
| Model                    | LightGBM (Gradient Boosting)                 |
| Hyperparameter Tuning    | Optuna (Bayesian optimization)               |
| Evaluation               | AUC, ROC, PR Curve, Feature Importance       |
| Visualization            | `matplotlib`, `seaborn`                      |

---

## 📈 Model Insights

- **Top Churn Drivers**: Contract type, monthly charges, and total charges
- **High-risk customers**: Probabilities > 0.7
- **Retention opportunity**: 21% of customers are at high churn risk

---

## 📂 Files in This Repository

| File                                      | Description                                      |
|-------------------------------------------|--------------------------------------------------|
| `telco_customer_churn_022425.py`          | Main Python script with full modeling workflow   |
| `Telco_Customer_Churn_022425.ipynb`       | Jupyter notebook for step-by-step exploration    |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv`    | Raw dataset                                      |
| `README.md`                               | This readme file                                 |
| `Telco Customer Churn Project Janaky.docx`| Business-friendly project summary                |

---

## 📉 Visual Output Examples

- ROC & Precision-Recall Curves
- Correlation Heatmaps
- Feature Importance Rankings

*Screenshots not included in this repo but available on request.*

---

## 💼 Business Takeaways

- **Churn Prediction = ROI**: Retaining a customer is far cheaper than acquiring one.
- **Smart Intervention**: Targeted offers for high-risk accounts can improve retention.
- **Data-Driven Strategy**: Insight into churn drivers fuels smarter decisions.

---

## 🚀 Tech Stack

- `Python` · `LightGBM` · `Optuna` · `SMOTE` · `Pandas` · `Matplotlib` · `Seaborn` · `Jupyter` · `VS Code` · `GitHub`

---

## 👤 About Me

I'm a B2B Product Manager transitioning into machine learning and AI. This project is part of my portfolio showcasing real-world business impact through data science.

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/janakybrent/)
