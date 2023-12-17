# HR Analytics README

## Overview
This project takes an HR analytics dataset from Kaggle and seeks to predict attrition amongst high-performing employees.  The following steps are undertaken in the Jupyter Notebook:

- exploring/cleansing the data
- prepping multiple pipelines against a Histogram-Based Gradient Boosting Estimator - utilises OneHotEncoder and OrdinalEncoder from scikit-learn to test effectiveness across different approaches to using categorical data.

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