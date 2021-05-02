# Credit Risk Analysis

## Overview

This project was to familiarize me with supervised learning and the various pros/cons of different sampling techniques.

For this, we were creating a machine learning model to predict credit risk for various loan applications.

## Results

- Oversampling
  - Accuracy: 67%
  - Precision
    - High Risk: 1%
    - Low Risk: 100%
  - Recall Score: 
    - High Risk: 63%
    - Low Risk: 67%
- SMOTE Oversampling:
  - Accuracy: 66%
  - Precision:
    - High Risk: 1%
    - Low Risk: 100%
  - Recall Score: 
    - High Risk: 66%
    - Low Risk: 66%
- Undersampling:
  - Accuracy: 66%
  - Precision:
    - High Risk: 1%
    - Low Risk: 100%
  - Recall Score: 
    - High Risk: 61%
    - Low Risk: 57%
- SMOTEENN (Combonation Oversampling and Undersampling):
  - Accuracy: 59%
  - Precision:
    - High Risk: 1%
    - Low Risk: 100%
  - Recall Score: 
    - High Risk: 69%
    - Low Risk: 58%
- Balanced Random Forest:
  - Accuracy: 79%
  - Precision:
    - High Risk: 4%
    - Low Risk: 100%
  - Recall Score: 
    - High Risk: 67%
    - Low Risk: 91%
- Easy Ensemble AdaBoost:
  - Accuracy: 92%
  - Precision:
    - High Risk: 7%
    - Low Risk: 100%
  - Recall Score: 
    - High Risk: 90%
    - Low Risk: 94%

## Summary

The Ensemble Classifiers (Balanced Random Forest and Easy Ensemble AdaBoost) had higher accuracy, percision, and recall scores. These Ensemble Classifiers where the best at predicitng credit risk for both high and low risk categories.

I would recomend the Easy Ensemble AdaBoost classifier for predicting credit risk due to having the highest in accuracy. This would make it great in making sure people who apply for loans will get catagorized in the proper areas.