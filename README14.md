# Assignment 14: Ethical AI Analysis and Explainability

## Project Overview
This project evaluates fairness and explainability in a machine learning workflow using the Adult Census Income dataset.

## Contents
- `Ethical_AI_Fairness_Explainability.ipynb` - Main notebook
- `Ethical_AI_Report.pdf` - 3-page report

## Setup
Open the notebook in Google Colab or Jupyter Notebook and run all cells.

### Required libraries
```bash
pip install fairlearn shap lime
```

## Notebook Tasks
- Load and preprocess a public dataset
- Use `sex` as the sensitive feature for fairness analysis
- Train a logistic regression model
- Evaluate performance with accuracy, confusion matrix, and classification report
- Compute fairness metrics with Fairlearn
- Visualize fairness metrics
- Apply SHAP and LIME for explainability

## Dataset
Adult Census Income dataset from `fairlearn.datasets.fetch_adult()`

## Output
The notebook generates:
- performance evaluation metrics
- fairness metrics by group
- SHAP summary and waterfall plots
- LIME local explanation
