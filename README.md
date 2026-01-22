# 💳 CreditWise Loan Approval Prediction System  
### End-to-End Supervised Machine Learning Pipeline (Binary Classification)

## 📌 Project Overview  
**CreditWise Loan System** is an intelligent **loan approval prediction system** designed for a bank to automate and improve loan approval decisions using **Machine Learning**.

Traditionally, loan approval decisions are made manually by loan officers after verifying documents like:  
✅ Income proof  
✅ Employment details  
✅ Credit history  
✅ Existing liabilities  

This manual process is often:  
- **Slow & time-consuming**  
- **Inconsistent** (human bias and judgment differences)  
- **Hard to scale** with increasing applications  

This project solves the problem by building a **supervised machine learning pipeline** that predicts whether a loan should be:

✅ **Approved (1)**  
❌ **Rejected (0)**  

---

## ✅ What I Built (Project Highlights)  
- Built an **end-to-end supervised ML pipeline** using:  
  - **K-Nearest Neighbors (KNN)**  
  - **Logistic Regression**  
  - **Naive Bayes**
- Implemented **Binary Classification** to predict loan approval.
- Performed detailed **EDA (Exploratory Data Analysis)** to discover patterns in applicant behavior.
- Applied **feature engineering + preprocessing** to improve model performance.
- Evaluated models using classification metrics:  
  - **Precision**  
  - **Recall**  
  - **F1 Score**  
  - **Confusion Matrix** *(optional)*

---

## 🎯 Problem Statement  
Banks face two major challenges during loan approvals:

### ⚠️ Key Challenges  
1. **Rejecting eligible applicants** → loss of business & customer dissatisfaction  
2. **Approving risky applicants** → financial loss due to defaults  

### ✅ Solution  
A machine learning system that automatically learns from historical loan data and provides:  
✅ Faster decision-making  
✅ More accurate predictions  
✅ Consistent & unbiased approvals  

---

## 🧠 Machine Learning Task  
- **Type:** Supervised Learning  
- **Problem:** Binary Classification  
- **Target Variable:** `Loan_Approved`  
  - `1` → Loan Approved  
  - `0` → Loan Rejected  

---

## 📂 Dataset Information  
Each record represents one applicant and includes personal + financial + credit details.

### 🧾 Example Features  
- Applicant income & co-applicant income  
- Age, marital status, dependents  
- Employment status  
- Credit score  
- Debt-to-income ratio  
- Savings balance  
- Existing loans  
- Collateral value  
- Requested loan amount / loan term  

---

## 🔍 Exploratory Data Analysis (EDA)  
EDA was performed to understand the dataset and applicant trends, such as:  
- Distribution of income and loan amount  
- Loan approval trends by credit score  
- Relationship between DTI ratio and approval chances  
- Missing values and outliers  
- Correlation between features  

---

## 🛠️ Feature Engineering & Preprocessing  
Key preprocessing steps included:  
✅ Handling missing values (mean/median/mode imputation)  
✅ Encoding categorical variables (One-Hot Encoding / Label Encoding)  
✅ Scaling numerical features (StandardScaler / MinMaxScaler)  
✅ Feature selection to remove noise and reduce overfitting  

---

## 🤖 Models Implemented  
### 1️⃣ K-Nearest Neighbors (KNN)  
- Uses distance-based classification  
- Works best with scaled data  
- Tuned using different values of **K**

### 2️⃣ Logistic Regression  
- Strong baseline model for binary classification  
- Works well with linearly separable data  
- Provides interpretable coefficients  

### 3️⃣ Naive Bayes  
- Probabilistic classifier based on Bayes Theorem  
- Works well for fast baseline comparisons  
- Performs well with independent feature assumptions  

---

## 📊 Model Evaluation Metrics  
Models were evaluated using:

✅ **Precision** → How many predicted approvals were actually correct  
✅ **Recall** → How many actual approvals were correctly identified  
✅ **F1 Score** → Balance between Precision and Recall  

> The best model was selected based on strong **F1 Score** and consistent results.

---

## 🧪 Project Workflow  
1. Data Loading  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Train/Test Split  
6. Model Training (KNN, Logistic Regression, Naive Bayes)  
7. Model Evaluation (Precision, Recall, F1)  
8. Final Model Comparison  

---

## 🧰 Tech Stack / Tools Used  
- **Python**  
- **Pandas, NumPy** (Data Handling)  
- **Matplotlib, Seaborn** (Visualization)  
- **Scikit-learn** (ML Models + Preprocessing + Metrics)  

---

## 🚀 How to Run the Project  
### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
