# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to employ different techniques to train and evaluate models with unbalanced classes, using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Results
- Naive Random Oversampling
  - Balanced accuracy score: 67.4%
  - Precision: 1%
  - Recall: 74%
- SMOTE Oversampling
  - Balanced accuracy score: 66.2%
  - Precision: 1%
  - Recall: 69%
- Undersampling
  - Balanced accuracy score: 66.2%
  - Precision: 99%
  - Recall: 41%
- Combination (Over and Under)
  - Balanced accuracy score: 54.7%
  - Precision: 99%
  - Recall: 57%
- Balanced Random Forest Classifier
  - Balanced accuracy score: 79.2%
  - Precision: 99%
  - Recall: 88%
- Easy Ensemble AdaBoost Classifier
  - Balanced accuracy score: 91.8%
  - Precision: 99%
  - Recall: 94%

## Summary
We oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm and compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. The ensemble classifiers had the highest accuracy scores - I would recommend to use the Easy Ensemble AdaBoost Classifier due to its accuracy, precision, and recall scores.
