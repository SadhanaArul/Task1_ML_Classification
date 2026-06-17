# Breast Cancer Classification

## Problem Statement
Predict whether a breast tumor is Malignant or Benign using cell nucleus features.

## Dataset
- Scikit-learn Breast Cancer Dataset
- 569 samples, 30 features

## Models Used
1. Logistic Regression - 98.25% accuracy
2. Random Forest - 95.61% accuracy

## Best Model
**Logistic Regression**
- Accuracy: 98.25%
- F1-Score: 98.61%
- ROC-AUC: 99.54%

## Results
- Only 2 misclassifications out of 114 test samples
- Top features: area, radius, and concave points

## How to Run
```bash
jupyter notebook "ML Classification.ipynb"
