# Loan Prediction using Machine Learning

## Overview
This project predicts whether a loan application will be approved or rejected using Machine Learning algorithms. The model is trained on applicant details such as income, education, credit history, loan amount, and employment status.

The project was developed in Jupyter Notebook as part of hands-on practice for Machine Learning and hackathon preparation.

---

## Problem Statement
Financial institutions receive thousands of loan applications every day.  
The goal of this project is to automate the loan approval process by predicting loan eligibility based on customer information.

---

## Dataset Features

Some important features used in the dataset:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

Target Variable:
- Loan_Status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models Used

### 1. Logistic Regression
Used as a baseline classification model.

### 2. Decision Tree Classifier
Used to capture non-linear relationships in the dataset.

### 3. Random Forest Classifier
Used for improving prediction accuracy and reducing overfitting.

---

## Project Workflow

### 1. Data Collection
Loaded training and testing datasets using Pandas.

### 2. Data Cleaning
- Removed unnecessary columns
- Checked dataset structure
- Handled inconsistent values

### 3. Missing Value Handling
- Numerical values filled using mean
- Categorical values filled using mode

### 4. Exploratory Data Analysis (EDA)
Visualized:
- Loan approval distribution
- Income distribution
- Credit history impact
- Correlation between features

### 5. Data Preprocessing
- Label Encoding for categorical variables
- Feature selection
- Train-test split

### 6. Model Training
Trained multiple classification models:
- Logistic Regression
- Decision Tree
- Random Forest

### 7. Model Evaluation
Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

Accuracy formula:

\[
Accuracy = \frac{Correct\ Predictions}{Total\ Predictions}
\]

### 8. Final Prediction
Generated predictions on test dataset and created submission file.

---

## Results

| Model | Accuracy |
|------|------|
| Logistic Regression | 80% |
| Decision Tree | 72% |
| Random Forest | 84% |

Best performance was achieved using Random Forest Classifier.

---

## Sample Visualizations

The project includes:
- Count plots
- Histograms
- Heatmaps
- Feature importance graphs

---

## Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Deployment using Flask or Streamlit

---

## How to Run the Project

### Clone Repository

```bash
git clone https://github.com/kvenky24/Project--Loan-Prediction.git
```

### Open Jupyter Notebook

```bash
jupyter notebook
```
---

## Requirements

Install required libraries using:

```bash
pip install -r requirements.txt
```
---

## Author

Venky
