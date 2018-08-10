# Breast Cancer Prediction using Breast Cancer Wisconsin (Diagnostic) Data Set from sklearn dataset library.

This project aims to find best estimators of 6 common machine learning algorithms (K-Nearest Neighbor, Naive Bayes, Logistic Regression, Random Forests, Kernalised Support Vector Machine & Gradient Boosting). The best estimators for each are used to make uncorrelated predictions which in turn are concatenated and fed into a secondary Support Vector Machine estimator by stacking. The result of the final stacked model is calculated.

### Steps involed are as follows:
- Exploratory Data Analysis (EDA.ipynb)
- Preprocessing, Building first level esimators, Building second level estimator, predicting results, evaluating performance (modelling.ipynb)

### Pre-requisites
Libaries mentioned in requirements.txt must be installed (preferably within a python virtual environment to avoid clashes with existing libraries) using command "pip install -r requirements.txt"
