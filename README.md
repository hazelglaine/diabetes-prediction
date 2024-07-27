# Diabetes Prediction Project

This project aims to predict the onset of diabetes based on various health indicators. The dataset includes features such as the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.

## Overview

- **Objective**: To build and evaluate machine learning models that can accurately predict whether a patient has diabetes.
- **Dataset**: The <a href="https://www.kaggle.com/datasets/mathchi/diabetes-data-set"> dataset</a> contains health-related features for patients, which are used to train and test the models.
     - sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, selected from a larger database with the following constraints: All are female and at least 21 years old of Pima Indian heritage.
     - Pregnancies: number of times pregnant
     - Glucose: plasma glucose concentration 2 hours in an oral glucose tolerance test
     - BloodPressure: diastolic blood pressure (mm Hg)
     - SkinThickness: triceps skin fold thickness (mm)
     - Insulin: 2-hr serum insulin ($\mu$ U/ml)
     - BMI: body mass index, weight(kg) / (height(m))^2
     - DiabetesPedigreeFunction: diabetes pedigree function
     - Age: age in years
     - Outcome: class variable {0: Normal, 1: Diabetic}

## Setup

**Clone the repository**:
   ```bash
   git clone https://github.com/hazelglaine/diabetes-prediction.git
   cd diabetes-prediction
  ```

## Usage

- **Data Processing**: Preprocesses the dataset by handling missing values, scaling features, and applying one-hot encoding.
- **Model Training and Evaluation**: Trains multiple machine learning models and evaluates their performance.
- **Models Implemented**:
   - Logistic regression
   - Decision tree
   - Random forest
   - Gradient boosting machine
   - Support vector machine
