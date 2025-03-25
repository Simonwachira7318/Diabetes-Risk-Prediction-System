# Diabetes-Risk-Prediction-System

## Overview
The Diabetes Risk Prediction System is a machine learning project aimed at predicting the risk of diabetes based on various health metrics. This project utilizes a dataset containing information about patients, including features such as glucose levels, blood pressure, BMI, and more. The goal is to build a predictive model that can help identify individuals at risk of developing diabetes.

## Dataset
The dataset used in this project is named `diabetes_risk_prediction.csv`. It contains the following columns:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- **Blood Pressure**: Diastolic blood pressure (mm Hg)
- **Skin Thickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **Diabetes Pedigree Function (DPF)**: Diabetes pedigree function
- **Age**: Age (years)
- **Diabetes**: Target variable (1 if diabetes is present, 0 otherwise)

## Installation
To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn
