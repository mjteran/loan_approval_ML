# Prediction of Loan Approval in Banks using Machine Learning Approach

**Summary**: This project uses machine learning models to predict loan approval with greater accuracy. Which help banks make informed decisions efficiently, benefiting both applicants and financial institutions.

## ⚡ Features Overview

| Feature                 | Description                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| 🆔 Loan ID             | A unique identifier for each loan.                                        |
| 🚻 Gender              | Applicant's gender (Male/Female).                                        |
| 💍 Marital Status      | Indicates if the applicant is Married (Yes/No).                         |
| 👨‍👩‍👧 Dependents       | Number of dependents relying on the applicant.                        |
| 🎓 Education           | Applicant’s education level (Graduate/Not Graduate).                   |
| 💼 Self-Employed       | Whether the applicant is self-employed (Yes/No).                        |
| 💰 Applicant Income    | Monthly income of the primary applicant.                                 |
| 🏠 Coapplicant Income | Monthly income of the coapplicant (if any).                             |
| 💵 Loan Amount        | Requested loan amount (in thousands).                                   |
| 📆 Loan Term          | Duration of the loan (in months).                                       |
| 🏦 Credit History     | Whether the applicant meets credit history guidelines.                 |
| 🌍 Property Area      | Location of the property (Urban/Semi-Urban/Rural).                     |
| ✅ Loan Status        | Indicates if the loan was approved (Y/N).                              |

# 📂 GitHub Content
- 📁 `/data`: Dataset from the Loan Prediction Problem Dataset.  
- 📁 `/models`: Jupyter notebook files.  

## 📑 Jupyter Notebook Files

Each file can be executed on Google Colab.

### `loan_approval_ML.ipynb` – 📄 Paper Reproduction  
This notebook replicates the methodology from the referenced paper, focusing on **data preprocessing, feature engineering, and machine learning algorithms** to predict loan approval.

#### 🔹 Key Steps:  
- 🛠 **Data Preprocessing**: Handling missing values and preparing data.  
- 🏗 **Feature Engineering**: Encoding categorical variables and scaling features.  
- 🤖 **Machine Learning Models**:  
  - 🌳 **Random Forest** – Ensemble learning method.  
  - ⛔ **Naïve Bayes** (Skipped in this implementation).  
  - 🌲 **Decision Tree** – Tree-based classification model.  
  - 🔎 **K-Nearest Neighbors (KNN)** – Distance-based algorithm.  

---

### `loan_approval_ML_additional_models.ipynb` – 🚀 Additional ML Models  
This notebook extends the original approach with additional machine learning techniques.  

#### 🔹 Additional Models:  
- 📈 **Logistic Regression** – Binary classification model.  
- 🏆 **Support Vector Machine (SVM)** – Effective for high-dimensional spaces.  
- ⚡ **XGBoost** – Optimized gradient boosting algorithm.  
- 🔄 **SMOTE** – Applied to handle class imbalance in all models.  

---

### `loan_approval_ML_updated.ipynb` – 🔧 Upgraded Version  
An improved version of the methodology with enhanced preprocessing and tuning.  

#### 🔹 Enhancements:  
- 🧹 **Data Preprocessing**: Improved handling of missing values.  
- 📊 **Feature Engineering**: Robust Scaling to reduce outlier impact.  
- 🤖 **Machine Learning Improvements**:  
  - 🔄 **SMOTE** – Addressing class imbalance.  
  - 🔍 **GridSearch** – Hyperparameter tuning for better performance.  

---

