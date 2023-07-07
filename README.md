# Heart Disease Classification
This project aims to predict whether or not a person has heart disease based on various medical attributes using machine learning techniques.

## Problem Definition
The problem we are addressing is binary classification, where we need to determine if a patient has heart disease or not based on clinical parameters.

## Data
The dataset used for this project is sourced from the Cleveland database available on the UCI Machine Learning Repository. It contains 14 attributes, including age, sex, chest pain type, blood pressure, cholesterol level, fasting blood sugar, electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of peak exercise ST segment, number of major vessels, thalium stress result, and the target variable indicating the presence or absence of heart disease.

## Features
The following features are used to predict the presence of heart disease:

1. Age: Age of the patient in years.
2. Sex: Gender of the patient (1 = male, 0 = female).
3. Chest Pain Type: The type of chest pain experienced by the patient (0-3).
4. Resting Blood Pressure: Resting blood pressure in mm Hg on admission to the hospital.
5. Serum Cholesterol: Serum cholestoral in mg/dl.
6. Fasting Blood Sugar: Fasting blood sugar level > 120 mg/dl (1 = true, 0 = false).
7. Resting Electrocardiographic Results: Results of resting electrocardiogram (0-2).
8. Maximum Heart Rate Achieved: Maximum heart rate achieved during exercise.
9. Exercise-Induced Angina: Whether exercise induced angina or not (1 = yes, 0 = no).
10. ST Depression Induced by Exercise: ST depression induced by exercise relative to rest.
11. Slope of Peak Exercise ST Segment: The slope of the peak exercise ST segment (0-2).
12. Number of Major Vessels: Number of major vessels colored by flourosopy (0-3).
13. Thalium Stress Result: Thalium stress test result (1, 3, 6, 7).
14. Target: Presence of heart disease (1 = yes, 0 = no).

## Evaluation
The evaluation metric for this project is accuracy. Our goal is to achieve at least 95% accuracy in predicting whether a patient has heart disease or not.

## Tools and Libraries Used
The following tools and libraries were used for this project:

1. Python: Programming language used for data analysis and machine learning.
2. pandas: Library for data analysis.
3. NumPy: Library for numerical operations.
4. Matplotlib and seaborn: Libraries for data visualization.
5. Scikit-Learn: Library for machine learning modelling and evaluation.

## Project Workflow
The project follows the following workflow:

1. Exploratory Data Analysis (EDA): Analyzing the dataset to gain insights and understand the data.
2. Model Training: Creating machine learning models to predict heart disease based on the given features.
3. Model Evaluation: Evaluating the performance of the models using appropriate evaluation metrics.
4. Model Comparison: Comparing different models to identify the best performing one.
5. Model Fine-tuning: Fine-tuning the selected model to improve its performance.
6. Feature Importance: Determining the importance of different features in predicting heart disease.
7. Cross-Validation: Assessing the model's performance on unseen data using cross-validation techniques.
8. Reporting: Summarizing and presenting the findings of the project.

The notebook associated with this project provides a step-by-step implementation of the above workflow.

Please note that no personal identifiable information (PPI) is present in the dataset.

Feel free to explore the notebook for more details and insights.

## Conclusion
By leveraging machine learning techniques and analyzing various clinical parameters, we can accurately predict whether a patient has heart disease or not. This can aid in early diagnosis and prompt treatment of individuals at risk, potentially saving lives.

### For a more detailed understanding of the project, refer to the notebook provided.
