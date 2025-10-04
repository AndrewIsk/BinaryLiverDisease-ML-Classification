# Liver Disease Classification Using Machine Learning

This repository contains machine learning models for the binary classification of liver disease using various datasets and preprocessing techniques. The goal is to compare the performance of different classifiers — including Random Forest (RF), XGBoost (XGB), Gradient Boosting (GB), and Support Vector Machines (SVM) — across unedited, normalized, SMOTE-augmented, and normalized SMOTE datasets.

This project is attempting to replicate a published article by Ganie et al.:

Ganie, S.M., Dutta Pramanik, P.K. & Zhao, Z. Improved liver disease prediction from clinical data through an evaluation of ensemble learning approaches. BMC Med Inform Decis Mak 24, 160 (2024). https://doi.org/10.1186/s12911-024-02550-y

---

## Project Overview

Liver disease classification is critical for early diagnosis and treatment. This project explores different machine learning approaches to predict liver disease status, utilizing:

- **Data Preprocessing**: Normalization, SMOTE oversampling to balance classes  
- **Classification Models**: Random Forest, XGBoost, Gradient Boosting, and SVM  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC, Matthews Correlation Coefficient (MCC)  
- **Visualization**: Confusion matrices and ROC curves for detailed performance insights

---

## Repository Structure

- `data/` - Dataset file
- `notebooks/` - Jupyter notebooks or scripts with model training and evaluation code   
- `README.md` - This file  

---

## Getting Started

### Prerequisites

- Python 3.7+  
- Libraries:  
  - `numpy`  
  - `pandas`  
  - `scikit-learn`  
  - `xgboost`  
  - `imblearn` (for SMOTE)  
  - `matplotlib`  
