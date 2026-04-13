# Sleep Disorder Prediction using Machine Learning

## Overview
This project analyzes a publicly available sleep health dataset containing lifestyle and physiological variables such as sleep duration, stress level, BMI, occupation, and heart rate.

A supervised machine learning **multi-class classification model** is developed to predict an individual's sleep condition:

- 0 = No Sleep Disorder (Normal)
- 1 = Insomnia
- 2 = Sleep Apnea

The goal is to identify which factors contribute most strongly to different sleep disorders and demonstrate how machine learning can be used to analyze sleep health outcomes.

---

## Dataset
Source: Kaggle Sleep Health and Lifestyle Dataset  
- 374 samples  
- 13 features  

The dataset includes demographic, physiological, and lifestyle-related variables.

---

## Problem Type
This is a **multi-class classification problem**, where the model predicts one of three possible sleep health outcomes.

---

## Methods

### Data Preprocessing
- Missing values in `Sleep Disorder` filled with "None"
- Label encoding applied to convert categorical variables into numeric form
- Feature scaling applied for Logistic Regression

### Models Used
- Logistic Regression (baseline linear model)
- Random Forest Classifier (non-linear ensemble model)

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix (3×3)

---

## Results

### Model Performance
- Logistic Regression: ~85–93% accuracy
- Random Forest: ~90–96% accuracy

Random Forest performed better due to its ability to capture non-linear relationships between features.

---

## Key Findings

The most important predictors of sleep disorders were:

- BMI Category
- Blood Pressure
- Occupation
- Sleep Duration
- Stress Level

These results suggest that both physiological health and lifestyle factors significantly influence sleep conditions.

---

## Conclusion
Machine learning models can effectively classify sleep health conditions and identify key contributing factors. This study demonstrates how lifestyle and physiological variables are strongly associated with specific sleep disorders such as insomnia and sleep apnea.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Author
Sleep Health Machine Learning Project (Class Assignment)
