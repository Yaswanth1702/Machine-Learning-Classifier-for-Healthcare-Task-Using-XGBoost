# Breast Cancer Classification Using XGBoost  

## Overview  
This project uses the **XGBoost** machine learning classifier to predict breast cancer based on the **Breast Cancer Wisconsin dataset**. The model is trained using **k-fold cross-validation** and optimized with **GridSearchCV** for hyperparameter tuning.  

## Features  
- **Dataset**: Breast Cancer Wisconsin dataset from `sklearn.datasets`  
- **Model**: XGBoost Classifier  
- **Hyperparameter Tuning**: GridSearchCV  
- **Evaluation Metrics**: Accuracy, Precision, Recall (Sensitivity), Specificity, and F1-score  
- **Confusion Matrix**: Analyzes model performance  

## Installation  
Ensure you have Python and the necessary dependencies installed:  
```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn
```  

## Usage  
Run the Python script to train and evaluate the model:  
```bash
python main.py
```  

## Results  
- **Best Hyperparameters**:  
  - Learning Rate: `0.2`  
  - Max Depth: `3`  
  - N Estimators: `100`  
  - Subsample: `0.8`  
- **Performance Metrics**:  
  - Accuracy: `94.74%`  
  - Precision: `94.59%`  
  - Recall (Sensitivity): `97.22%`  
  - Specificity: `90.48%`  
  - F1-Score: `95.89%`  

## Confusion Matrix  
```
[[38  4]  # True Negatives | False Positives  
 [ 2 70]] # False Negatives | True Positives  
```

## Team  
- **Your Name** - XGBoost Model Implementation  
- **Teammate 1** - Random Forest Implementation  
- **Teammate 2** - SVM Implementation  
