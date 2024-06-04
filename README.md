# CODSOFT
CREDIT CARD FRAUD DETECTION -  
This project focuses on detecting fraudulent transactions using machine learning models. The primary goal is to classify transactions as either fraudulent or legitimate.
## Project Overview
Fraud detection is a critical task for financial institutions to prevent losses and protect customers. This project utilizes various machine learning algorithms to detect fraudulent transactions. The models used include:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
## Dataset
The dataset used in this project contains transaction data with features such as transaction amount, time of transaction, location, etc. The target variable is `is_fraud`, indicating whether a transaction is fraudulent (1) or legitimate (0).
## Models and Evaluation
The models are evaluated based on accuracy, ROC-AUC score, and other relevant metrics. The following steps outline the process:

1. Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features.
2. Feature Selection: Select relevant features for training the models.
3. Model Training: Train Logistic Regression, Decision Tree, and Random Forest models on the training data.
4. Model Evaluation: Evaluate the models on the test data using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score.
## Visualizations
The project includes visualizations to compare the performance of different models:
- ROC Curve: Plots the ROC curves for Logistic Regression, Decision Tree, and Random Forest models.
- Precision-Recall Curve: Plots the precision-recall curves for all models.
- Confusion Matrix Heatmap: Displays confusion matrices for each model.
