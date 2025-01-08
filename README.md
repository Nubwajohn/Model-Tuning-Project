# Model-Tuning-Project
Model Tuning Project: ReneWind

## About

The objective is to build and tune multiple classification models to identify potential failures, enabling proactive repairs of generators before they break, thereby reducing overall maintenance costs.

*Disclaimer: All datasets and reports do not represent any company, institution, or country, but just a dummy dataset for learning purposes.*

## Project Overview

ReneWind aims to use machine learning to predict generator failures in wind turbines, using ciphered data with 40 predictors. 

The goal is to build and optimize classification models to proactively identify failures, reducing maintenance costs by preventing costly replacements. The model will be evaluated on its ability to predict failures, balancing repair, inspection, and replacement costs. The target variable is binary, with "1" indicating failure and "0" indicating no failure, and the focus is on minimizing false negatives while managing overall costs.

## Data Description

- The data provided is a transformed version of original data which was collected using sensors.
- Train.csv - To be used for training and tuning of models.
- Test.csv - To be used only for testing the performance of the final best model.
- Both the datasets consist of 40 predictor variables and 1 target variablehe customer (e.g. high floor, view from the room, etc)
- booking_status: Flag indicating if the booking was canceled or not.

## Tools

- Programming Language: Python.
- Data Manipulation & Analysis Libraries: Pandas, NumPy.
- Data Visualization Libraries: Matplotlib, Seaborn.
- Machine Learning Library: Scikit-Learn, sklearn.
- Metric scores: sklearn.metrics.
- Data scaling and one hot encoding: StandardScaler, MinMaxScaler, OneHotEncoder
- Oversample and Undersample data: SMOTE, RandomUnderSampler
- Impute missing: SimpleImputer.
- Metric scores: sklearn.metrics, confusion_matrix, accuracy_score, precision_score, recall_score, f1_score.
- Ensemble classifiers: BaggingClassifier, RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, StackingClassifier, XGBClassifier, DecisionTreeClassifier.
- hyperparameter tuning: RandomizedSearchCV
- Creating pipelines and personalizing: Pipeline, ColumnTransformer.
- Suppress scientific notations: pd.set_option.
- Filtering Warnings: warnings, ConvergenceWarning.
- Data Preprocessing & Exploratory Data Analysis (EDA) Tools:Excel, Google Colab.
