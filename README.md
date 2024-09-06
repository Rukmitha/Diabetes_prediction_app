# Diabetes_prediction_app

This repository contains a machine learning project that predicts the likelihood of a person having diabetes based on various medical attributes. The model is trained on the well-known Pima Indians Diabetes dataset, and the goal is to develop a predictive system that can classify a person as diabetic or non-diabetic.

## Project Overview

The project explores various machine learning algorithms to predict diabetes, with a focus on accuracy and model performance. The dataset used consists of several medical predictors, including the number of pregnancies the person has had, their BMI, insulin level, age, and more.

### Features:
- Data preprocessing, including handling missing values, scaling, and normalization
- Exploratory Data Analysis (EDA) to understand the data
- Model training and evaluation with different algorithms (e.g., Logistic Regression, Random Forest, SVM, etc.)
- Model performance comparison and selection of the best-performing model
- Deployment-ready code for prediction

## Dataset

The dataset used for this project is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database). The dataset contains 768 entries and 8 feature columns:

1. Pregnancies: Number of pregnancies
2. Glucose: Plasma glucose concentration
3. BloodPressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skinfold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: A function that scores likelihood of diabetes based on family history
8. Age: Age of the person
9. Outcome: Class variable (0 for non-diabetic, 1 for diabetic)
