# Task 1 - Data Cleaning & Preprocessing

## Objective

The objective of this task is to learn how to clean and preprocess raw data for Machine Learning.

## Tools & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset Used

Titanic Dataset

## Steps Performed

### 1. Data Loading

Loaded the Titanic dataset using Pandas.

### 2. Data Exploration

* Checked dataset information
* Checked data types
* Identified missing values

### 3. Handling Missing Values

* Filled missing Age values using median
* Filled missing Embarked values using mode
* Dropped Cabin column due to too many missing values

### 4. Encoding Categorical Features

* Converted Sex column into numerical format
* Applied one-hot encoding on Embarked column

### 5. Feature Scaling

Standardized numerical columns using StandardScaler.

### 6. Outlier Detection & Removal

* Visualized outliers using boxplots
* Removed outliers using IQR method

## Output

Generated a cleaned dataset ready for Machine Learning models.

## Files Included

* Task 1.ipynb
* Titanic-Dataset.csv
* README.md
* Screenshots folder
