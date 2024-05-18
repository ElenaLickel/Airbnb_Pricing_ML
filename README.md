# Airbnb_Pricing_ML

## Description
This Jupyter notebook provides a detailed workflow for data analysis and model training with a focus on a dataset related to Airbnb listings. It includes steps from initial data loading to advanced modeling techniques.

## Contents
1. **Initial Setup**: Loading essential Python libraries such as pandas, numpy, seaborn, matplotlib, and scikit-learn.
2. **Data Loading**: Instructions for loading the dataset into a pandas DataFrame.
3. **Data Preprocessing**:
   - Managing missing values.
   - Data type conversion and column manipulation.
4. **Exploratory Data Analysis (EDA)**: 
   - Overview of dataset columns.
   - Examination of numeric data distributions.
5. **Feature Engineering**:
   - Text mining on specific columns using TfidfVectorizer.
   - Imputation of missing data.
6. **Outlier Detection**: 
   - Using Isolation Forest for detecting outliers.
7. **Model Training**:
   - Training models including XGBoost, RandomForest, and Support Vector Machines.
   - Implementing and integrating a Neural Network model into a Voting Regressor setup.
8. **Validation**: 
   - Loading and utilizing a separate validation dataset.
   - Applying model predictions to validation data.
9. **Final Steps**: 
   - Saving the processed data and trained models appropriately.

## Requirements
This notebook requires the following Python environment and libraries:
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- xgboost
- keras
- tensorflow
- scikeras

## Author
Elena Lickel
