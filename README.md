# Classification Assignment Project

## Overview
This project demonstrates a complete machine learning classification workflow using the Breast Cancer Wisconsin dataset. The goal is to classify tumors as malignant or benign using supervised learning models.

## Dataset
The dataset is publicly available through `sklearn.datasets.load_breast_cancer()`.

## Models Used
- Logistic Regression
- Random Forest Classifier

## Project Steps
1. Load and inspect the dataset
2. Clean the data by checking missing values and duplicates
3. Perform exploratory data analysis (EDA)
4. Split data into training and testing sets
5. Train classification models
6. Evaluate models using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC
7. Visualize results using confusion matrices and ROC curves
8. Discuss deployment and monitoring strategies

## Requirements
Install the following Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
