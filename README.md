# 📊 CreditWise Loan Approval System

## 🚀 Project Overview
The CreditWise Loan Approval System is a machine learning project designed to automate and optimize the loan approval process. It predicts whether a loan application should be approved or rejected based on applicant financial, demographic, and credit-related features.

This project goes beyond basic prediction by incorporating model comparison, feature engineering, hyperparameter tuning, and feature reduction analysis to build a robust and interpretable solution.

---

## 🎯 Problem Statement
SecureTrust Bank aims to automate its loan approval process to reduce manual bias and improve consistency in decision-making. The objective is to develop a machine learning model that accurately predicts loan approval outcomes while optimizing performance through model comparison, feature engineering, and feature selection techniques. The final system should be reliable and interpretable for data-driven decisions.

---

## 📂 Dataset Description
Each record represents a loan applicant with features such as:

- Applicant Income, Coapplicant Income  
- Employment Status, Employer Category  
- Credit Score, Existing Loans, DTI Ratio  
- Savings, Collateral Value  
- Loan Amount, Loan Term, Loan Purpose  
- Property Area, Education Level, Gender  
- Target: Loan_Approved (1 = Approved, 0 = Rejected)

---

## 🔍 Exploratory Data Analysis (EDA)
- Slight class imbalance in loan approval status  
- Majority of applicants are male (62.1%)  
- Graduates dominate the dataset (72.2%)  
- Loan purposes are fairly distributed (Business highest at 25.2%)  
- Income distributions overlap across approval classes  
- No significant outliers observed in numerical features  

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Missing value imputation  
- Encoding categorical variables  
- Feature scaling  
- Column Transformer pipeline  

### 2. Baseline Models
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Evaluated using Accuracy, Precision, Recall, F1-score  

### 3. Advanced Model
- Random Forest Classifier  
- Hyperparameter tuning using GridSearchCV  

### 4. Feature Engineering
- Created new features  
- Evaluated impact on performance  

### 5. Model Comparison
- Compared all models  
- Selected best-performing model  

### 6. Model Insights
- Feature importance analysis  
- Identified key drivers of loan approval  

### 7. Feature Reduction
- Reduced feature set  
- Observed performance drop  

---

## 📈 Results
- Best Model: Random Forest (Tuned)  
- Accuracy: ~91%  
- F1 Score: ~0.85  
- Achieved balanced performance across metrics  

---

## 🧠 Key Insights
- Credit-related features strongly influence loan approval  
- Income alone is not a strong predictor  
- Feature engineering gave limited improvement  
- Feature reduction negatively impacted performance  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📌 Conclusion
This project demonstrates an end-to-end machine learning workflow, including data preprocessing, model building, optimization, and evaluation. The final model provides a reliable and interpretable solution for loan approval prediction.

---

## 🔮 Future Work
- Deploy using Streamlit or Flask  
- Add real-time prediction interface  
- Experiment with XGBoost / LightGBM  
- Apply cross-validation  

---

## 👨‍💻 Author
Your Name
