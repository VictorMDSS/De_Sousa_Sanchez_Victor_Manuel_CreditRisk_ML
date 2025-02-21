# 🚀 Machine Learning Project: Credit Risk Assessment

## 📌 Overview
Credit risk assessment is crucial for financial institutions to determine the probability of a borrower defaulting on a loan. This project applies **Machine Learning** techniques to analyze and predict credit risk, improving decision-making and minimizing financial losses.

## 🎯 Objective
Develop an accurate and scalable **credit risk prediction model** using **supervised learning algorithms**, enhancing risk evaluation for financial institutions.

## 🔍 Data
- **Dataset**: Credit risk dataset with 32,581 records and 12 features
- **Features**:
  - **Demographics**: Age (`person_age`), Employment Length (`person_emp_length`)
  - **Financial Info**: Income (`person_income`), Home Ownership (`person_home_ownership`)
  - **Loan Details**: Amount (`loan_amnt`), Interest Rate (`loan_int_rate`), Purpose (`loan_intent`)
  - **Credit History**: Credit History Length (`cb_person_cred_hist_length`), Prior Defaults (`cb_person_default_on_file`)
  - **Target Variable**: Loan Status (`loan_status`, 1 = Default, 0 = Paid)

## 🏗️ Methodology
1. **Data Preprocessing** 📊  
   - Handling missing values (`loan_int_rate`, `person_emp_length`)
   - Encoding categorical variables (`person_home_ownership`, `loan_intent`, `cb_person_default_on_file`)
2. **Exploratory Data Analysis (EDA)** 🔎  
   - Identifying trends in default risk by income, loan amount, and credit history
   - Visualizing correlations between features
3. **Model Selection & Training** 🤖  
   - Logistic Regression, Random Forest, XGBoost  
   - Hyperparameter tuning & cross-validation  
4. **Evaluation & Optimization** 📈  
   - Metrics: AUC-ROC, Precision-Recall  
   - Feature importance analysis  

## 📊 Key Results
- **Accuracy:** 86.6%  
- **AUC-ROC Score:** 0.92  
- **Feature Importance:** Credit History Length, Loan Amount, Income  

## 🛠️ Tech Stack
- **Programming:** Python (Pandas, NumPy, Scikit-learn, XGBoost)
- **Visualization:** Matplotlib, Seaborn
- **Version Control:** Git, GitHub

## 🎯 Impact
- **Improved Loan Approvals**: More accurate risk prediction reduces default rates.
- **Faster Decision-Making**: Automates risk assessment, improving efficiency.
- **Better Customer Experience**: Fairer credit decisions based on data-driven insights.

## 📌 Next Steps
✅ Improve model interpretability with SHAP values  
✅ Expand dataset for greater generalization  
✅ Deploy as an interactive web application  

## 📬 Let's Connect!
🔗 [LinkedIn](https://www.linkedin.com/in/victor-manuel-de-sousa-sanchez-3391b61b5/)  
📧 victordesousasanchez@gmail.com  
💻 [GitHub Repo](https://github.com/VictorMDSS/De_Sousa_Sanchez_Victor_Manuel_CreditRisk_ML)  

---
_This project demonstrates expertise in Machine Learning, data analysis, and deployment—showcasing practical skills in financial risk modeling._ 🚀