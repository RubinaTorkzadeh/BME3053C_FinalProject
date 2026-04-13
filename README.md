# BME3053C_FinalProject
Predictive Modeling of Sleep Disorders from Behavioral and Physiological Data

# Sleep Disorder Prediction using Machine Learning

## Overview
This project uses machine learning to predict whether an individual has a sleep disorder based on lifestyle and physiological factors such as BMI, stress level, occupation, sleep duration, and heart rate.

We frame this as a binary classification problem:
- 0 = No Sleep Disorder
- 1 = Sleep Disorder (Insomnia or Sleep Apnea)

---

## Dataset
Source: Kaggle Sleep Health and Lifestyle Dataset  
Contains 374 samples and 13 features.

---

## Methods
We used two machine learning models:
- Logistic Regression
- Random Forest Classifier

Preprocessing included:
- Handling missing values
- Encoding categorical variables
- Feature scaling (for Logistic Regression)

---

## Results
- Logistic Regression Accuracy: ~93%
- Random Forest Accuracy: ~96%

---

## Key Findings
Most important features:
- BMI Category
- Blood Pressure
- Occupation
- Sleep Duration

---

## Conclusion
Machine learning models can effectively predict sleep disorders using lifestyle and physiological data, with Random Forest performing best due to its ability to capture nonlinear relationships.

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
