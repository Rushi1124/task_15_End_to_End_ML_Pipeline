# Breast Cancer End-to-End ML Pipeline

## Description
This project demonstrates a complete machine learning workflow on the Breast Cancer dataset. The pipeline includes:  
- Data preprocessing (scaling, encoding) using `ColumnTransformer`  
- Training a `RandomForestClassifier` within a `Pipeline`  
- Splitting data into train and test sets  
- Model evaluation using Accuracy, Precision, Recall, and F1-score  
- Saving the entire pipeline for deployment  

This approach ensures **no data leakage**, easier reproducibility, and a deployment-ready ML model.

## Tools
- Python  
- Pandas, NumPy  
- Scikit-learn (Pipeline, ColumnTransformer, RandomForestClassifier)  
- Joblib  

## Steps
1. Load dataset and inspect features  
2. Preprocess data (drop irrelevant columns, encode target, scale/encode features)  
3. Create ML pipeline combining preprocessing and classifier  
4. Split data into train and test sets  
5. Train pipeline and generate predictions  
6. Evaluate model performance  
7. Save the trained pipeline as `.pkl`  

## Deliverables
- Trained ML pipeline  
- Evaluation metrics (Accuracy, Precision, Recall, F1-score)  
- Saved pipeline model (`breast_cancer_ml_pipeline.pkl`)  

## Author
**Rushita Bhosale**
