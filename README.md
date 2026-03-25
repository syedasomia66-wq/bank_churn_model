# Bank Customer Churn Prediction

## Overview
This project builds a deep learning model to predict customer churn using a structured banking dataset. The objective is to identify customers likely to leave and support data-driven decision-making for retention strategies.

## Dataset
- Source: Bank Customer Churn dataset  
- 10,000 records with demographic and financial features  
- Target variable: `Exited` (0 = Not Churned, 1 = Churned)  

## Data Preprocessing
- Removed irrelevant features (RowNumber, CustomerId, Surname)  
- Encoded categorical variables (Gender, Geography)  
- Applied one-hot encoding for Geography  
- Normalized features using MinMax scaling  
- Split data into training and testing sets  

## Exploratory Data Analysis
- Analyzed customer distribution across features  
- Visualized churn patterns using histograms, count plots, and scatter plots  
- Identified relationships between age, balance, and churn behavior  

## Model Architecture
- Artificial Neural Network (ANN) using TensorFlow/Keras  
- Input layer: 12 features  
- Hidden layers: Dense layers with ReLU activation  
- Output layer: Sigmoid activation for binary classification  

## Training
- Optimizer: Adam  
- Loss Function: Binary Cross-Entropy  
- Class imbalance handled using class weights  
- Trained over multiple epochs with validation split  

## Evaluation
- Accuracy: ~84%  
- Precision, Recall, and F1-score for both classes  
- Confusion Matrix analysis  

### Key Metrics
- Precision (Churned): ~0.61  
- Recall (Churned): ~0.59  
- Overall Accuracy: ~0.84  

## Results
- Strong performance in identifying non-churning customers  
- Moderate performance in detecting churned customers due to class imbalance  
- Confusion matrix highlights model strengths and weaknesses  

## Key Learnings
- End-to-end machine learning pipeline development  
- Importance of feature engineering and preprocessing  
- Handling class imbalance using class weights  
- Model evaluation using multiple metrics beyond accuracy  

## Tech Stack
Python, TensorFlow, Keras, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  

## Repository
[Add your GitHub link here]
