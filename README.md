# HR Analytics README

## Overview
This project takes an HR analytics dataset from Kaggle and seeks to predict attrition amongst high-performing employees.  The following steps are undertaken in the Jupyter Notebook:

- exploring/cleansing the data
- using SelectKBest to establish the best number of numerical/categorical features
- Fitting a Stacked Regressor consisting of a Random Forest and a Gradient Booster to establish the best model for predicting attrition.

## Components
- HR_Analytics csv data file
- HR Analytics Jupyter Notebook
- requirements.txt
- Companion blog: url-to-follow

## Requirements
This notebook requires the packages listed below.  These can be installed from the requirements.txt file by executing the following code in the terminal.  

*Note: please ensure that you are in the directory to which you have saved this Python project before running this code*

`pip install -r requirements.txt`

For data analysis:
- pandas
- numpy

For data visualisation:
- seaborn
- plotly
- matplotlib

For machine learning:
- scikit-learn

## Notes on Implementation