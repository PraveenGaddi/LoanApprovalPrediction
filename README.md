# Loan Approval Prediction using Machine Learning

A machine learning project that predicts whether a loan application will be approved based on applicant information. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## Project Overview

The objective of this project is to build classification models that can predict loan approval using applicant details. The notebook covers the end-to-end ML pipeline from loading the dataset to comparing multiple classification algorithms.

---

## Features

- Data loading using Pandas
- Exploratory Data Analysis (EDA)
- Missing value handling
- Categorical feature encoding
- Feature scaling
- Train-test split
- Training multiple classification models
- Performance evaluation using standard classification metrics

---

## Machine Learning Workflow

```
Dataset
   │
   ▼
Data Exploration
   │
   ▼
Missing Value Imputation
   │
   ▼
Categorical Feature Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
```

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Preprocessing

The following preprocessing steps are implemented:

- Missing values in numerical columns filled using **SimpleImputer (Mean Strategy)**
- Missing values in categorical columns filled using **SimpleImputer (Most Frequent Strategy)**
- **Label Encoding** for:
  - Education_Level
  - Loan_Approved (Target)
- **One-Hot Encoding** for:
  - Employment_Status
  - Marital_Status
  - Loan_Purpose
  - Property_Area
  - Gender
  - Employer_Category
- **StandardScaler** applied to feature values before training

---

## Machine Learning Models

The notebook trains and evaluates the following classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

---

## Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics are used to compare the performance of the different classification models.

---

## Project Structure

```
Loan-Approval-Prediction/
│
├── Loan-Approval-Prediction.ipynb
├── loan_approval_data.csv
└── README.md
```

---

## Required Libraries

Install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/<your-username>/Loan-Approval-Prediction.git
```

Navigate to the project directory:

```bash
cd Loan-Approval-Prediction
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Loan-Approval-Prediction.ipynb
```

Run all cells in sequence.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Train additional classification models such as Random Forest, XGBoost, and Support Vector Machine
- Deploy the trained model using FastAPI

---

## Author

**Gaddi Praveen Kumar**

---

## License

This project is intended for learning and portfolio purposes.