Diagnostic Models for Ovarian Lesions
This repository contains the code implementation for the project titled "Diagnostic models of low-grade serous carcinoma, borderline serous tumor, and serous cystadenoma of the ovary: Model development and validation based on radiomics".

Overview
The goal of this project is to develop and validate diagnostic models for distinguishing between low-grade serous carcinoma, borderline serous tumor, and serous cystadenoma of the ovary using radiomics features.

File Description
Cystadenoma_ExtractFeatures.ipynb: This notebook is used to extract radiomics features from serous cystadenoma lesions.
SVM_Model.ipynb, RandomForest_Model.ipynb, XGBoost_Model.ipynb: These notebooks contain implementations of Support Vector Machine (SVM), Random Forest, and XGBoost models respectively for distinguishing between different ovarian lesions.
Cystadenoma_Diagnostic_Model.ipynb: This notebook includes the development of a diagnostic model for serous cystadenoma. It utilizes a combination of radiomics and clinical features. Two modeling approaches are explored: one where clinical features are directly added and another where clinical features are added after feature selection.
Usage
To use this code, follow these steps:

Open the desired notebook (Cystadenoma_ExtractFeatures.ipynb, SVM_Model.ipynb, RandomForest_Model.ipynb, XGBoost_Model.ipynb, or Cystadenoma_Diagnostic_Model.ipynb) in a Jupyter Notebook environment.
Execute the code cells sequentially.
Adjust parameters or experiment with different settings as needed.
Requirements
Python 3.x
Jupyter Notebook
Required libraries (numpy, pandas, scikit-learn, xgboost, etc.)
