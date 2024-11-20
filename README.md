# Heart Failure Prediction

## Project Description

This project focuses on predicting heart failure events using patient clinical records. The analysis leverages machine learning models and various visualization techniques to identify significant patterns in the data. The ultimate goal is to aid in early detection and intervention for patients at risk of heart failure.

## Dataset

The dataset contains 199 records of patient clinical features, including:

- **age**: Age of the patient  
- **anaemia**: Presence of anaemia (0: No, 1: Yes)  
- **creatinine_phosphokinase**: Levels of the CPK enzyme (mcg/L)  
- **diabetes**: Presence of diabetes (0: No, 1: Yes)  
- **ejection_fraction**: Percentage of blood leaving the heart with each contraction  
- **high_blood_pressure**: High blood pressure status (0: No, 1: Yes)  
- **platelets**: Platelet count (kiloplatelets/mL)  
- **serum_creatinine**: Level of serum creatinine (mg/dL)  
- **serum_sodium**: Serum sodium level (mEq/L)  
- **sex**: Gender of the patient (Male/Female)  
- **smoking**: Smoking status (0: No, 1: Yes)  
- **time**: Follow-up period (days)  
- **DEATH_EVENT**: Death due to heart failure (0: No, 1: Yes)

## Features

- **Data Cleaning**: Handle missing values and inconsistencies in the dataset.
- **Exploratory Data Analysis (EDA)**: Visualize key relationships using graphs and charts.
- **Predictive Modeling**: Build and evaluate machine learning models to predict the `DEATH_EVENT` attribute.
- **Feature Importance**: Identify critical factors influencing heart failure outcomes.

## Tools and Libraries

- **Programming Language**: R
- **Libraries**: 
  - `naniar` for missing data visualization
  - `ggplot2` for visualizations
  - Machine learning libraries (based on future implementation)

## Project Highlights

- Comprehensive data cleaning to manage missing and inconsistent values.
- Insights from detailed visualizations to understand feature relationships.
- Predictive models that help identify patients at risk of heart failure.

## Future Works
- Implementation of machine learning models for prediction.
- Deployment of the model as a web application for real-world usage.
