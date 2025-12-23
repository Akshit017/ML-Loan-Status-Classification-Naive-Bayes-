# 💰 Loan Status Prediction using Naive Bayes

## 📌 Project Overview
This project aims to predict **loan approval status** using a **Naive Bayes classification model**. By analyzing applicant demographic and financial information, the model helps identify patterns that influence whether a loan is approved or not.

---

## 🎯 Objectives
- Clean and preprocess loan applicant data
- Perform exploratory data analysis (EDA)
- Apply feature engineering techniques
- Train and evaluate a Naive Bayes classification model
- Analyze model performance using standard metrics

---

## 🗂️ Dataset Description
The dataset contains information related to loan applicants, including:

- Gender
- Marital Status
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Target variable: **Loan Status** (Approved / Not Approved)

---

## 🧹 Data Preprocessing & Exploratory Data Analysis
The following steps were performed:

- Loaded and inspected the dataset
- Removed irrelevant or duplicate columns
- Handled missing values in numerical and categorical features
- Encoded categorical variables into numerical format
- Performed statistical analysis to understand approval patterns
- Visualized relationships between loan status and key features such as:
  - Credit History
  - Applicant Income
  - Property Area

---

## 🤖 Machine Learning Model
### Model Used
- **Naive Bayes Classifier**

### Feature Engineering
- Encoded categorical variables using appropriate encoding techniques
- Scaled numerical features where required
- Split the dataset into training and testing sets

---

## 📊 Model Evaluation
The model was evaluated using the following metrics:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix
- Classification Report

These metrics provide insights into how effectively the model predicts loan approval outcomes.

---

## 🧠 Key Insights
- Credit history is a strong indicator of loan approval
- Naive Bayes performs efficiently on classification problems with categorical features
- Proper preprocessing improves prediction accuracy

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure
