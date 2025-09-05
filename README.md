# Loan-Status-Prediction
Loan approval prediction using SVM classifier
# Loan Status Prediction using Machine Learning

This project predicts whether a loan application will be approved or rejected based on applicant details.  
It uses a Support Vector Machine (SVM)with a linear kernel for classification.

---

## 📌 Project Overview
Loan approval is a critical process for financial institutions. Automating this process with Machine Learning can help reduce human bias and improve decision-making efficiency.

---

## 📂 Dataset
The dataset contains applicant details such as:

- Gender, Married, Dependents, Education, Self_Employed  
- ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term  
- Credit_History, Property_Area  
- Loan_Status (Target variable: 1 = Approved, 0 = Not Approved)  

---

## ⚙️ Technologies Used
- Python 3
- Pandas & NumPy → Data processing  
- Seaborn→ Data visualization  
- Scikit-learn → Model training & evaluation  

---

## 📊 Workflow
1. Data Collection & Preprocessing
   - Handle missing values  
   - Encode categorical variables  
   - Clean and prepare dataset  

2. Exploratory Data Analysis (EDA) 
   - Visualize relationships between applicant features and loan status  

3. Model Training  
   - Support Vector Machine (SVM) classifier  

4. Model Evaluation  
   - Accuracy on Training Data → 79.9%  
   - Accuracy on Test Data → 83.3%  

---

## 🚀 Results
✅ The model generalizes well with slightly higher accuracy on the test set compared to the training set.  
✅ Demonstrates that SVM is effective for loan status prediction.  



