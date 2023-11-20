# Bank Customer Churn Prediction

## Objective

The goal of this project is to develop a machine learning model that accurately predicts which customers are at risk of churning.

## Tools Used

- Python
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

## Project Overview

This project involves predicting customer churn probabilities in a bank. We used exploratory data analysis (EDA) with Seaborn and Matplotlib to gain insights into the dataset. The primary focus was on developing machine learning models to predict customer churn.

## Approach

1. **Exploratory Data Analysis (EDA):**
   - Utilized Seaborn and Matplotlib for data visualization.
   - Identified and handled outliers in numerical features.
   - Explored the distribution of key numerical variables.
   - Created box plots to visualize the spread of numerical variables.

2. **Data Preparation:**
   - Removed unnecessary columns (RowNumber, CustomerId, Surname).
   - Applied one-hot encoding to categorical variable 'Geography'.
   - Mapped 'Gender' to numerical values.
   - Performed feature scaling on selected columns.

3. **Machine Learning Models:**
   - Implemented Logistic Regression, Decision Trees, and Random Forest algorithms.
   - Split the dataset into training and testing sets.
   - Trained and evaluated each model's performance using metrics such as accuracy, precision, recall, and ROC-AUC.

4. **Randomized Search Cross-Validation (Random Forest):**
   - Conducted hyperparameter tuning using Randomized Search CV for Random Forest to enhance model performance.

5. **Results:**
   - Achieved notable accuracy, precision, and recall scores across different models.
   - Evaluated and compared model performance using ROC curves.

## Usage

To run the project, ensure you have Python and the required libraries installed. You can use the Jupyter Notebook or run the Python script.

```bash
python churn_prediction.py
