# Task 4 - Classification with Logistic Regression

## Objective

The objective of this task is to build a binary classification model using Logistic Regression and evaluate its performance using various classification metrics.

## Tools & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Dataset Used

Breast Cancer Wisconsin Dataset

## Steps Performed

### 1. Data Loading and Exploration

* Loaded the dataset using Pandas
* Checked dataset shape, columns, and missing values

### 2. Data Cleaning

* Removed unnecessary columns (`id`, `Unnamed: 32`)
* Converted diagnosis column into numerical values:

  * Malignant (M) = 1
  * Benign (B) = 0

### 3. Train-Test Split

* Split the dataset into training and testing sets using an 80:20 ratio

### 4. Feature Scaling

* Applied StandardScaler to standardize numerical features

### 5. Model Training

* Trained a Logistic Regression model using Scikit-Learn

### 6. Model Evaluation

Evaluated the model using:

* Confusion Matrix
* Precision
* Recall
* F1 Score
* ROC-AUC Score

### 7. ROC Curve Analysis

* Generated ROC Curve
* Calculated Area Under Curve (AUC)

### 8. Threshold Tuning

* Tested custom probability thresholds
* Observed changes in classification results

### 9. Sigmoid Function

* Visualized the sigmoid function used by Logistic Regression
* Understood how probabilities are generated

## Key Findings

* Logistic Regression achieved high classification accuracy.
* ROC-AUC score indicated strong class separation.
* Feature scaling improved model performance.
* Threshold selection affects prediction behavior.
* Logistic Regression is effective for binary classification problems.

## Files Included

* Task4_LogisticRegression.ipynb
* breast_cancer.csv
* README.md
* Screenshots Folder

## Outcome

Successfully built, trained, and evaluated a Logistic Regression model for breast cancer classification using multiple evaluation metrics and visualization techniques.
