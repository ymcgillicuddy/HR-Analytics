# HR Analytics README

## Overview
This project takes an HR analytics dataset from Kaggle and seeks to predict attrition amongst high-performing employees.  The following steps are undertaken in the Jupyter Notebook:

- exploring/cleansing the data
- using SelectKBest to establish the best number of numerical/categorical features
- using One-Hot Encoding to convert categorical features to numerical and comparing outcomes to using purely numerical features.
- exploring alternative model parameters
- data visualisation (for both data analysis and model analysis)

## Components
- HR_Analytics csv data file
- HR Analytics Jupyter Notebook
- requirements.txt
- [Companion blog](https://yvonnemcg.hashnode.dev/predicting-negative-attrition-with-machine-learning)

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

## Notes on Functions
This notebook incorporates some functions for ease of use that are listed below:

- **replace** - Replaces a value in one column with a given alternative value
- **print_shape** - Prints the shape of train and test data sets after splitting
- **model_fit_score** - Uses train and test data to fit and predict a RandomForestClassifier
- **plot_k_best** - Plots a chart of scores for all dataset features using SelectKBest
- **select_features** - Creates a dictionary from two lists and converts that into a dataframe that can be used to plot values