# 💳 LoanIQ

### Machine Learning-Based Loan Approval Prediction

**LoanIQ** is a machine learning project built to explore how applicant and financial information can be used to predict **loan approval outcomes**.

The project focuses on the complete ML workflow, from cleaning and understanding the data to preprocessing, feature engineering, model training, and evaluation.

## 📌 What I Did

- Cleaned and handled missing values in the dataset
- Performed **Exploratory Data Analysis (EDA)** to understand loan approval patterns
- Encoded categorical variables and prepared features for modelling
- Used **train-test splitting and feature scaling**
- Compared multiple classification models
- Applied feature engineering to improve the model

## 🤖 Models Compared

I experimented with:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

### 🏆 Best Model: Gaussian Naive Bayes

Based on **precision**, Gaussian Naive Bayes performed best among the models tested.

After feature engineering, the Naive Bayes model achieved:

**Precision: 81.13%**

The project uses precision as the primary basis for selecting the best model.

## 📊 Dataset

The dataset contains **1,000 loan application records** with information such as:

- Applicant & coapplicant income
- Credit score
- Existing loans
- DTI ratio
- Savings
- Collateral value
- Loan amount and term
- Employment and education details

The target variable is **`Loan_Approved`**.

## 🛠️ Tech Stack

**Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Google Colab**

## 🎯 What I Learned

This project helped me understand how a real machine learning workflow comes together, especially **data preprocessing, EDA, feature engineering, model comparison, and evaluation**.

It was also a good exercise in understanding that the model with the highest accuracy is not automatically the best choice. Sometimes one metric matters more depending on the problem. Humanity survives another spreadsheet.

## 🚀 Future Improvements

I’d like to extend LoanIQ by adding model tuning, better feature selection, explainability, and a simple interface for making predictions on new loan applications.
