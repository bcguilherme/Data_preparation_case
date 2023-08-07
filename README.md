# Data_preparation_case

Churn Classification Dataset and Analysis
This repository contains code and analysis for preparing a dataset used for the classification of churn prediction. The dataset is sourced from a fictional telecommunications company and is provided by IBM for educational purposes. The goal is to predict customer churn using various features.

Dataset Source and Description
The dataset used in this analysis is sourced from a fictional telecommunications company and is provided by IBM. The dataset includes various features related to customer information, services, and contract details. The dataset is available on Kaggle. The features and their descriptions can be found in the Kaggle Dicionary.

Getting Started
To use this code, you'll need to have Python and the required libraries installed. You can install the necessary libraries using the following command:

bash
Copy code
!pip install pandas-profiling==3.3.0
Libraries Used
pandas
pandas-profiling
numpy
seaborn
matplotlib
scikit-learn
Data Loading and Initial Exploration
The dataset is loaded from an Excel file hosted by IBM. The initial exploratory data analysis (EDA) includes data profiling using pandas-profiling, checking for duplicated rows, and handling missing values.

Data Preprocessing
Columns related to churn information (Churn Label, Churn Score, Churn Reason) are dropped.
Columns with constant values are dropped.
Geographic columns (City, Zip Code, Lat Long) are dropped.
Data types are adjusted for the Total Charges column.
Categorical columns are encoded using OrdinalEncoder.
Feature Selection
Feature selection is performed using Mutual Information (MI) scores. The MI scores help identify the importance of each feature for predicting churn.

Visualizing MI Scores
MI scores are visualized using a bar plot to show the importance of each feature in predicting churn.

Conclusion
This repository provides code and analysis for preparing a churn prediction dataset using Python and various libraries. The dataset is sourced from a fictional telecommunications company and is used to build a classification model for predicting customer churn.

Feel free to explore the code and analysis in this repository to gain insights into data preprocessing, feature selection, and churn prediction using machine learning techniques.
