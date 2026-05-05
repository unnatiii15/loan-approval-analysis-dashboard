# 📊 Loan Approval Prediction & Dashboard

## 🚀 Overview

This project demonstrates an **end-to-end data analysis and machine learning workflow** to understand and predict loan approval decisions.

It combines:

* Data preprocessing & feature engineering (Python)
* Predictive modeling (Logistic Regression)
* Interactive dashboard (Power BI)

---

## 🎯 Objective

* Identify key factors influencing loan approval
* Build a predictive model for loan decisions
* Visualize insights using an interactive dashboard

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy, Scikit-learn)
* Power BI
* CSV Dataset

---

## 🔍 Data Processing

* Handled missing values
* Encoded categorical variables
* Created features:

  * **Total Income**
  * **Income Band**
  * **Risk Level**
  * **Prediction Labels**

---

## 🤖 Machine Learning

* Model: Logistic Regression
* Target: Loan_Status (Approved / Rejected)

### Outputs:

* Predicted Loan Status
* Approval Probability
* Confidence Segments (Low / Medium / High)

---

## 📊 Dashboard Highlights

* Loan Approval Distribution
* Credit History vs Approval
* Approval Rate by Risk Level
* Loan Approval by Gender
* Loan Approval by Income Band
* Model vs Actual Predictions
* Model Confidence vs Approval Rate

---

## 📷 Dashboard Preview

![Dashboard](dashboard.png)

---

## 💡 Key Insights

* Credit history is the strongest approval factor
* Low-risk applicants have higher approval rates
* Model predictions align closely with actual outcomes
* Income alone does not guarantee loan approval

---

## 📂 Project Files

```bash id="a7k2x1"
loan-approval-analysis-dashboard/
│
├── loan_data.csv            # Dataset
├── loan_analysis.ipynb      # Data cleaning + ML model
├── loan_dashboard.pbix      # Power BI dashboard
├── dashboard.png            # Dashboard preview
├── requirements.txt         # Dependencies
└── README.md
```

---

## ⚙️ How to Use

1. Install dependencies:

```bash id="p9z3n2"
pip install -r requirements.txt
```

2. Run the notebook:

```bash id="v1m8q4"
loan_analysis.ipynb
```

3. Open dashboard:

```bash id="k4x2t7"
loan_dashboard.pbix
```

---

## 👩‍💻 Author

Unnati Bhanushali
B.Tech ECE (AIML)

---

## ⭐ Highlights

* End-to-end project (Data → ML → Dashboard)
* Real-world business problem
* Strong visualization + storytelling
