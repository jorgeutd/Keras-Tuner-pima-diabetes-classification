# Keras-Tuner-pima-diabetes-classification

## Project Description
This is a simple sequential DL based approach to predict whether an individual is healthy or diabetic using the pima-indians-diabetes dataset.
I used the KerasTuner framework for scalable hyperparameter optimization using a RandomSearch approach and find the best parameters of our sequential model.
This notebook is part of my deep learning DAAN 570 class, I used a AWS sagemaker instance for GPU runtime.

## Data

The dataset consist of several medical predictors (independents) features and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on. [link of data in kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

### Columns

|Columns|Description|
|-------|------------|
|Pregnancies|Number of times pregnant|
|Glucose|Plasma glucose concentration for 2 hours in an oral glucose tolerance test|
|BloodPressure|Diastolic blood pressure (mm Hg)|
|SkinThickness|Triceps skin fold thickness (mm)|
|Insulin|2-Hour serum insulin (mu U/ml)|
|BMI|Body mass index (weight in kg/(height in m)^2)|
|DiabetesPedigreeFunction|Diabetes pedigree function|
|Age|Age (years)|
|Outcome|Class variable (0 or 1) 268 of 768 are 1, the others are 0|