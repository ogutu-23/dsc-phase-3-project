# Heart Disease Prediction Data Analysis

## Overview
This is a project on heart disease prediction dataset. We will perfom data analysis then we shall build models such as logistic regression and decision trees by splitting data into training and test sets. The essence of this process is obtain predictions from our models. 

## Business Understanding
I have chosen a heart disease prediction dataset, my stakeholder is a hospital administrator. We would like to predict the likelihood of a patient having a heart disease based on their medical history and other factors. In order to help the hospital administrator make informed decisions about resource allocation and patient care.

A classification problem in data science is a type of supervised learning problem where the goal is to predict a categorical label or class that an instance belongs to, based on its features or characteristics.

## Data understanding and Data Analysis
The data used in this analysis contains data collected from the dataset: Heart disease-prediction. A heart disease prediction dataset typically consists of various features related to patient characterisctics and medical history. These features can include age, sex, blood pressure, cholestorol levels, smoking habits and other relevant factors. The dataset may also contain a target variable indicating whether the patient has a heart disease or not.

## Distribution of each column.

![vis2](https://github.com/user-attachments/assets/77cdd2bf-bfbd-499f-ac1e-80cc047df6e3)

# Observations
* There are more males affected by heart disease than females
* Chest pain type 1 is common
* The majority have normal thalassemia
* Most patients have 0 major vessels colored by fluroscopy,(ca)
* Most patients do not have exercise-induced angina (0)
* The majority of patients have either result 0 or 1 rest ecg

## Distribution of Each Column Vs Target
![vis1](https://github.com/user-attachments/assets/42bf780a-f328-469f-8c9e-19e2d60630fb)

## Observations

* The higher the slope, heart disease is more likely
* There is no significant difference in resting blood pressure and cholestrol level between patients with and without heart disease.
* Patients with heart disease tend to have a lower maximum heart rate achieved compared to those without heart disease.
* Male patients(1) have a higher chance of heart disease than female patients(0)
* The box plots shows that the age distribution is similar between patients with and without heart disease.
* Patients with heart disease tend to have a lower maximum heart rate achieved compared to those without heart disease.
* Higher rest ecg higher chances of having the disease.

## Models

Two models were trained and evaluated on the dataset:

Logistic Regression: A logistic regression model was trained to predict the probability of [target variable] based on the input features.
Decision Trees: A decision tree classifier was trained to predict the class labels of the target variable.

## Results

The performance of each model was evaluated using accuracy, precision, recall, F1-score, and confusion matrices. The results are summarized below:

Logistic Regression

Accuracy: [1.00]
Classification Report: [   precision    recall  f1-score   support

           0       1.00      1.00      1.00        29
           1       1.00      1.00      1.00        32]

  



