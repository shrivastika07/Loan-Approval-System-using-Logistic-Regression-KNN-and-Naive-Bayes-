# Credit Wise - Loan Approval Prediction

## Overview

Credit Wise is a Machine Learning project that predicts whether a loan application is likely to be approved based on applicant details such as income, credit score, employment status, loan amount, and other financial factors.

The project includes:

* Data preprocessing
* Missing value handling
* Exploratory Data Analysis (EDA)
* Feature encoding
* Feature engineering
* Model training and evaluation
* Loan approval prediction

---

## Dataset Features

The dataset contains applicant information such as:

* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit Score
* Debt-to-Income Ratio (DTI)
* Gender
* Marital Status
* Employment Status
* Education Level
* Property Area
* Loan Purpose
* Loan Approval Status (Target Variable)

---

## Project Workflow

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Identified missing values
* Imputed numerical features using mean values
* Imputed categorical features using most frequent values

### 2. Exploratory Data Analysis (EDA)

Performed visual analysis using:

* Pie Charts
* Histograms
* Box Plots
* Correlation Heatmaps

Key insights were extracted regarding:

* Loan approval distribution
* Income patterns
* Credit score impact
* Outlier detection
* Feature relationships

### 3. Feature Encoding

Applied:

* Label Encoding
* One-Hot Encoding

to convert categorical features into machine-readable format.

### 4. Feature Engineering

Created additional features to improve model performance:

* Squared Debt-to-Income Ratio
* Squared Credit Score

These transformations helped capture non-linear relationships in the data.

### 5. Feature Scaling

Used StandardScaler to normalize numerical features before training machine learning models.

### 6. Model Training

Implemented and compared:

#### Logistic Regression

* Baseline classification model
* Fast and interpretable

#### K-Nearest Neighbors (KNN)

* Instance-based learning algorithm
* Classifies based on nearest neighbors

#### Gaussian Naive Bayes

* Probabilistic classification model
* Achieved the best performance among tested models

---

## Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

### Best Performing Model

🏆 **Gaussian Naive Bayes**

Followed by:

1. Gaussian Naive Bayes
2. Logistic Regression
3. K-Nearest Neighbors (KNN)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

```text
Credit-Wise/
│
├── credit_wise.ipynb
├── loan_approval_data.csv
├── README.md
│
└── outputs/
    ├── visualizations
    └── model_results
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/credit-wise.git
cd credit-wise
```

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:

```bash
jupyter notebook credit_wise.ipynb
```

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Ensemble models (Random Forest, XGBoost)
* Model deployment using Flask or Streamlit
* Real-time loan approval prediction web application

---

## Author

Developed as a Machine Learning project for exploring credit risk assessment and loan approval prediction using classification algorithms.
# Loan-Approval-System-using-Logistic-Regression-KNN-and-Naive-Bayes-
