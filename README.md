# Credit Scoring Model – CodeAlpha Internship

## Project Overview
This project is developed as part of the CodeAlpha Machine Learning Internship. The main objective is to predict a customer's credit score based on financial and credit-related information using Machine Learning algorithms.

## Project Objective
To build a Machine Learning classification model that predicts whether a customer's credit score is:
- Good
- Standard
- Poor

## Dataset
- **Dataset:** Credit Score Classification
- **Source:** Kaggle
- **Training Records:** 100,000
- **Testing Records:** 50,000

Dataset: https://www.kaggle.com/datasets/parisrohan/credit-score-classification

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Kaggle Notebook
- Joblib

## Project Workflow

### 1. Data Loading
Loaded training and testing datasets using Pandas.

### 2. Data Cleaning
- Handled missing values.
- Converted incorrect numeric data into valid numeric format.
- Handled invalid and extreme values.
- Removed unnecessary columns.

### 3. Data Preprocessing
- Missing value imputation.
- Numerical feature scaling.
- Categorical feature encoding using OneHotEncoder.

### 4. Model Training
Implemented and compared two Machine Learning algorithms:
- Random Forest Classifier
- Logistic Regression

### 5. Model Evaluation
Evaluated the models using:
- Accuracy
- Balanced Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

Random Forest was selected as the best-performing model based on the validation F1 score.

### 6. Prediction
Generated credit score predictions for 50,000 test records.

## Project Files

| File | Description |
|---|---|
| `codealpha-credit-scoring-model.ipynb` | Complete project notebook |
| `credit_score_predictions.csv` | Predicted credit scores for test data |

The trained model was saved as `credit_score_model.pkl` during execution. It is not included in this repository because of the GitHub browser upload file-size restriction.

## How to Run the Project

1. Download or clone this repository.
2. Open the notebook using Kaggle or Jupyter Notebook.
3. Add the Credit Score Classification dataset.
4. Run the notebook cells sequentially.
5. View the generated predictions CSV file.

## Internship
**Organization:** CodeAlpha  
**Domain:** Machine Learning  
**Project:** Credit Scoring Model  
**Task:** Task 1

---

**Developed as part of the CodeAlpha Machine Learning Internship.**
