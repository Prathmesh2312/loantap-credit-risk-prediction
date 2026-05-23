# 🏦 LoanTap Credit Risk Analysis using Logistic Regression

## 📌 Project Overview
This project focuses on building a **Machine Learning-based Credit Risk Prediction System** for LoanTap, an online lending platform. The objective is to predict whether a borrower is likely to **Fully Pay** or **Default (Charged Off)** on a personal loan using **Logistic Regression**.

The project covers:
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Outlier Treatment
- Logistic Regression Modeling
- Model Evaluation using ROC-AUC & Precision-Recall Curve
- Business Insights & Recommendations

---

# 🎯 Business Problem
LoanTap wants to:
- Predict potential loan defaulters
- Reduce Non-Performing Assets (NPAs)
- Improve underwriting decisions
- Enable risk-based pricing strategies

The goal is to help financial institutions make safer and data-driven loan approval decisions.

---

# 📂 Dataset Information
The dataset contains **396,000+ loan application records** with borrower information such as:

| Feature | Description |
|---|---|
| loan_amnt | Loan amount applied by borrower |
| int_rate | Interest rate on loan |
| annual_inc | Borrower's annual income |
| dti | Debt-to-income ratio |
| grade | Loan grade assigned by LoanTap |
| emp_length | Employment length |
| revol_util | Credit utilization ratio |
| mort_acc | Mortgage accounts |
| pub_rec_bankruptcies | Bankruptcy records |
| loan_status | Target variable |

### 🎯 Target Variable
- Fully Paid → `0`
- Charged Off → `1`

---

# 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Exploratory Data Analysis (EDA)
- Univariate Analysis
- Bivariate Analysis
- Correlation Heatmap
- Class Imbalance Analysis
- Distribution Plots

## 2️⃣ Data Preprocessing
- Missing Value Treatment
- Duplicate Removal
- Outlier Treatment
- Feature Engineering
- One-Hot Encoding
- Feature Scaling using MinMaxScaler

## 3️⃣ Model Building
- Logistic Regression

## 4️⃣ Model Evaluation
- Classification Report
- Confusion Matrix
- ROC-AUC Curve
- Precision-Recall Curve

---

# 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 89% |
| ROC-AUC Score | ~0.73 |
| Precision (Default Class) | 94% |
| Recall (Default Class) | 46% |
| F1-Score (Default Class) | 62% |

---

# 📈 Key Insights
- Around **80% customers fully paid** their loans.
- Borrowers with higher interest rates showed higher default probability.
- Debt-to-Income Ratio (DTI) significantly impacted repayment behavior.
- Loan Grades B and C dominated the portfolio.
- Employment length positively influenced repayment capability.
- Customers with bankruptcy records had higher default risk.

---

# 💡 Business Recommendations
- Use predictive modeling for loan underwriting decisions.
- Focus on high-risk borrower segments to reduce NPAs.
- Apply risk-based pricing strategies.
- Improve recall using advanced ML algorithms like XGBoost or Random Forest.
- Deploy the model for real-time credit risk assessment.


