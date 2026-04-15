# Sleep Disorder Classification Model

## Overview
This project builds a machine learning model to classify sleep disorders based on lifestyle and health-related features. Using a Random Forest Classifier, the model predicts whether an individual has:

- No sleep disorder  
- Insomnia  
- Sleep apnea  

The project also includes visualizations to better understand patterns and relationships within the dataset.

---

## Team Members
- Gia Bhatla  
- Breannah Carrero  
- Arnav Kumbham  
- Rubina Torkzadeh  

---

## AI Disclaimer
Some parts of this code were developed with the assistance of AI tools, primarily for syntax guidance and generating visualization logic.

---

## Features
- Data preprocessing and cleaning  
- Label encoding for categorical variables  
- Supervised machine learning model (Random Forest)  
- Model evaluation using accuracy and classification report  
- Data visualization with heatmaps, boxplots, and histograms  

---

## Model Details
- **Algorithm:** We used a Random Forest Classifier  
- **Train/Test Split:** For any given dataset, we designated the supervised model so that 80% of the data was used for training and 20% was used for testing the accuracy of the model.  

**Classes:**     (used for some graphs due to lack of space)
- `0` → None  
- `1` → Insomnia  
- `2` → Sleep Apnea  

---

## Visualizations

### Model Performance
- Heatmap of precision, recall, and F1-score for each class  

### Feature Relationships
- Sleep Duration vs Disorder (boxplot and distribution)  
- Stress Level vs Disorder (boxplot and distribution)  
- BMI Category vs Disorder (countplot)  
- Physical Activity vs Disorder (boxplot)  
- Heart Rate vs Disorder (boxplot)  

---

## Installation & Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
