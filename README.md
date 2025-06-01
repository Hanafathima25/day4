## Overview
This project uses the Breast Cancer Wisconsin dataset to build a Logistic Regression model 
that predicts whether a tumor is benign or malignant based on various features.
The model is trained, evaluated, and metrics such as confusion matrix, precision, recall, and ROC-AUC are reported.

## Dataset
The dataset is sourced from kaggle 
It contains numerical features extracted from digitized images of fine needle aspirate (FNA) of breast masses.
- The target variable is `diagnosis` with two classes:  
  - **B** = Benign  
  - **M** = Malignant
##  Data Preprocessing
- Missing columns like `Unnamed: 32` were removed.
- The target column `diagnosis` was label encoded (`B` → 0, `M` → 1).
- Numerical features were standardized using `StandardScaler`.

## Model
- Logistic Regression classifier was trained on 80% of the data.
- The model predicts whether the tumor is benign or malignant.

 ## Evaluation Metrics
- Confusion Matrix
- Precision
- Recall
- ROC-AUC Score 
  
