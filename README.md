CardioSense: A Data-Driven Heart Disease Prediction System

CardioPredict ????
A Machine Learning-Based Heart Disease Prediction System
Overview of the Project

CardioPredict tries to predict the presence of heart disease from clinical and demographic patient data using a machine learning approach.

The project focuses on EDA, statistically sound preprocessing, and understanding the features prior to the application of machine learning models.

Rather than jumping directly to the training of the model, this project follows a data-centric approach whereby at the end of this process, the dataset is well understood and cleaned with proper transformations that improve model performance and reliability.

Objectives:

Understand the distribution of features and their relationships by analyzing patient health data.

Identify patterns of heart diseases

Perform appropriate preprocessing and feature engineering.

Prepare data for supervised machine learning classification models Build a basis for correct and interpretable predictions

Description of Dataset:

Source: Heart Disease Dataset heart.csv

Records: 303 patients

Features: 13 input features + 1 target variable

Target Variable

target = 1 → Presence of heart disease

target = 0 → No heart disease

Features Used

Continuous Features

age - Patient's age

trestbps – Resting blood pressure

chol – Serum cholesterol

thalach – Maximum heart rate achieved

oldpeak – ST depression induced by exercise

Categorical / Discrete Features sex, cp, fbs, restecg, exang, slope, ca, thal

Exploratory Data Analysis (EDA)

The process will include extensive univariate and bivariate examinations:

> Univariate Analysis

Histogram with KDE for continuous features

Frequency and percentage bar plots for categorical features display information about the most frequently occurring categories

> Bivariate Analysis

Continuous features vs Target using Bar Plots and KDE

Categorical Features vs Target using Stacked Bar Charts

These visualizations assist in determining:

Feature Distributions

Skewness and Outliers

Main differences between heart disease and non-disease cases

Data Preprocessing:

The following steps were performed for preprocessing:

Conversion of Categorical Features to Relevant Data Types

One-Hot encoding for nominal categorical variables - cp, restecg,thal

Binary and ordinal feature values kept as integers

Stratified Train-Test Split (80

Outlier Detection Using IQR Method

Box Cox transformation on continuous variables to reduce skewness

Machine Learning Models (Planned / Implemented)

The processed data is then ready for training more supervised classifiers such as:

K-Nearest Neighbor (

Support Vector Machine (SVM)

Decision Tree Classifier

Random Forest Classifier

For hyperparameter tuning and cross-validation, GridSearchCV can be used.

Technologies & Libraries Used:

Python

NumPy

Pandas

Matplotlib

Seab

Scikit

SciPy

Key Takeaways:

Strong emphasis on Data Understanding before Modeling

Proper handling of categorical and continuous features.

Statistical transformations enhance model readiness

Suitable for Academic Assessment, Interviews, and Portfolio Use

Future Improvements:

Integrate preprocessing and modeling using Pipeline and ColumnTransformer
     
import pandas as

Add model comparison metrics and ROC curves

Feature Importance and Interpretability Analysis

Deploy as a simple web application

Author
Anushka Jana
