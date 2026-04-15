Sleep Disorder Classification Model
Overview

This project builds a machine learning model to classify sleep disorders based on lifestyle and health-related features. Using a Random Forest Classifier, the model predicts whether an individual has:

No sleep disorder
Insomnia
Sleep apnea

The project also includes visualizations to better understand patterns and relationships within the dataset.

Team Members
Gia Bhatla
Breannah Carrero
Arnav Kumbham
Rubina Torkzadeh
AI Disclaimer

Some parts of this code were developed with the assistance of AI tools, primarily for syntax guidance and generating visualization logic. All core concepts, model design, and analysis were implemented and verified by the team.

Features
Data preprocessing and cleaning
Label encoding for categorical variables
Supervised machine learning model (Random Forest)
Model evaluation using accuracy and classification report
Data visualization with heatmaps, boxplots, and histograms
Model Details
Algorithm: Random Forest Classifier
Train/Test Split: 80% training / 20% testing
Classes:
0 → None
1 → Insomnia
2 → Sleep Apnea
Visualizations
Model Performance
Heatmap of precision, recall, and F1-score for each class
Feature Relationships
Sleep Duration vs Disorder (boxplot and distribution)
Stress Level vs Disorder (boxplot and distribution)
BMI Category vs Disorder (countplot)
Physical Activity vs Disorder (boxplot)
Heart Rate vs Disorder (boxplot)
Installation & Requirements

Install required libraries before running:

pip install pandas numpy matplotlib seaborn scikit-learn
How to Run
Open the notebook in Google Colab
Run all cells
Upload your dataset when prompted (CSV or Excel format)
View model performance and generated graphs
Dataset Requirements

Your dataset should include features such as:

Sleep Duration
Stress Level
BMI Category
Physical Activity Level
Heart Rate
Sleep Disorder (target column)

Optional columns like "Person ID" will be automatically removed.

Output

The model will output:

Accuracy score
Classification report (precision, recall, F1-score)
Multiple graphs for analysis and interpretation
Key Insights

This project demonstrates how lifestyle factors such as stress, sleep duration, and physical activity correlate with sleep disorders, and how supervised learning can be applied to a healthcare classification problem.

Future Improvements
Test additional models (Logistic Regression, SVM, XGBoost)
Perform hyperparameter tuning
Add cross-validation
Improve feature engineering
Deploy as a web application
