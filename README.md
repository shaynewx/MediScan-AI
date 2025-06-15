# MediScan-AI: Multi-label Medical Diagnosis System

This repository hosts the code and documentation for our MediScan-AI project. Our system leverages structured machine learning pipelines to predict the presence of multiple medical conditions from clinical tabular data. By addressing challenges such as missing values and class imbalance, the system enables more accurate, early-stage diagnostics.

## Introduction

Early prediction of multiple disease risks from electronic medical records is critical for preventive healthcare. Real-world data often suffers from noise, imbalance, and missing values. MediScan-AI addresses these issues through feature cleaning, automated selection, and per-label model training using ensemble methods.

## Project Summary

Tasks: Predict 11 binary health condition labels

Models Used: Random Forest (one per label)

Key Techniques: Missing value imputation, standardization, one-hot encoding, label-wise feature selection, oversampling, custom evaluation metrics

## Models and Performance

We trained a separate Random Forest classifier for each label and evaluated them individually. The overall system achieved the following average performance across all labels:

Accuracy: 81.12%

F1 Score: 0.4913

Precision: 0.7391

Recall: 0.4266

ROC AUC: 0.7189

Custom Loss: 0.5141

The confusion matrix and metrics suggest strong precision and balanced predictive power across imbalanced tasks.

## Dataset

The dataset includes over 3,000 patient records with clinical measurements and 11 binary diagnostic labels. Due to privacy concerns, the data is not publicly available. All processing steps were performed with anonymized and cleaned data.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Citation

If you use this system or adapt any components, please cite or acknowledge this repository in your work.

