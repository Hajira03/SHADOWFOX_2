# 🏦 Loan Approval Prediction with Machine Learning

This project is part of the **ShadowFox AIML Internship – Intermediate Level Task 3**, focusing on building a machine learning model to predict loan approval outcomes.

## 📌 Problem Statement

The goal is to predict whether a loan application will be **approved or rejected** based on several features like credit history, income, employment, loan amount, etc. Accurate predictions can assist financial institutions in making informed decisions.

## 📂 Dataset

- Provided by ShadowFox
- [Click here to download the dataset](https://drive.google.com/drive/folders/18nheKtzhesFv_M6DB081dcmvphQXs7st?usp=sharing)

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

## ✅ ML Techniques Used

- Data Preprocessing & Cleaning
- Label Encoding
- Train-Test Split
- Model: Random Forest Classifier
- Model Evaluation:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

## 📊 Results

- **Accuracy:** ~78%
- **High Recall for Approved Loans (Class 1)**
- **Moderate F1-Score for Rejected Loans (Class 0)**

## 📁 Repository Structure

```
Loan_Approval_Prediction/
├── loan_approval_prediction.ipynb
├── dataset.csv
├── README.md
└── screenshots/
```

## 📸 Proof of Work

- Screenshots of outputs and GitHub upload in the `screenshots/` folder.
- Video explanation uploaded to LinkedIn with ShadowFox tagged.

## 🚀 Future Improvements

- Handle class imbalance using SMOTE or class weights
- Try different models (Logistic Regression, XGBoost)
- Perform Hyperparameter Tuning (GridSearchCV)
