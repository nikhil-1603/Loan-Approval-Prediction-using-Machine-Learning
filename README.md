# 📊 Loan Approval Prediction using Machine Learning

## 📝 Project Overview
Financial institutions process thousands of loan applications every day. Manually evaluating applications is time-consuming and may introduce bias.  
This project uses **Machine Learning** to predict whether a loan application will be **approved or rejected** based on applicant financial and personal details.

The system helps banks:
- Reduce manual workload
- Improve decision accuracy
- Minimize financial risk

---

## 🎯 Objective
- Perform exploratory data analysis on loan data
- Identify key factors influencing loan approval
- Build and evaluate multiple ML models
- Select the best-performing model for prediction

---

## 📁 Dataset Information
The dataset contains the following features:

| Feature | Description |
|------|-----------|
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Graduate / Not Graduate |
| Self_Employed | Employment type |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Co-applicant income |
| LoanAmount | Loan amount requested |
| Loan_Amount_Term | Loan repayment term |
| Credit_History | Credit history (0 or 1) |
| Property_Area | Urban / Semi-Urban / Rural |
| Loan_Status | Target variable (Approved / Rejected) |

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **IDE:** Jupyter Notebook

---

## 🔍 Project Workflow
1. Data Loading
2. Data Cleaning
   - Handling missing values
   - Encoding categorical variables
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Result Analysis

---

## 🤖 Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 📈 Model Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

---

## ⚙️ Hyperparameter Tuning
To improve model performance and prevent overfitting, **hyperparameter tuning** was applied using **GridSearchCV**.

---


## 🏆 Best Model
The **Random Forest Classifier** achieved the highest accuracy and provided better generalization compared to other models.

---

## 📊 Key Insights
- Credit history plays a major role in loan approval
- Higher applicant income increases approval chances
- Semi-urban areas show higher approval rates

---
