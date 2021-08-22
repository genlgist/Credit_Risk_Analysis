# Credit_Risk_Analysis

Regina Negrycz 
genglist@yahoo.com 
Module 17 Challenge 
Submitted 22 Aug 2021 
credit_risk_ensemble.ipynb
credit_risk_resampling.ipynb
Resources
Images
README

## Overview

The goal of this project was to apply machine learning to solve credit card risk. The data was first analyzed using the RandomOverSampler and SMOTE algorithms, then analyzed using the ClusterCentroids algorithm and a combined oversampling and subsampling approach using the SMOTEENN algorithm.

Two additional models, BalancedRandomForestClassifier and EasyEnsembleClassifier were used to predict credit risk.

The data was evaluated to classify the credit risk for individuals as "high risk" or "low risk".

## Results

The results were analyzed using the six different machine learning models used.
For each sample it was evaluated:
balanced accuracy score,
the accuracy score
the recall score.

1. RandomOverSampler

Accuracy:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/Random_Accuracy.PNG

Classification:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/Random_Classification.PNG

2. SMOTE

Accuracy:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/SMOTE_Accuracy.PNG

Classification:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/SMOTE_Classification.PNG


3. ClusterCentroids
Accuracy: https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids_Accuracy.PNG

Classification: 
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids_Classification.PNG

4. SMOTEENN

Accuracy:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/SMOTEENN_Accuracy.PNG

Classification:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/SMOTEENN_Classification.PNG


5. BalancedRandomForest

Accuracy:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForest_Accuracy.PNG

Classification:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForest_Classification.PNG


6.EasyEnsemble

Accuracy:
https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble_Accuracy.PNG

Classification:

https://github.com/genlgist/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble_Classification.PNG


## Summary

Of the six machine learning models evaluated, the best appears to be EasyEnsembleClassifier.  This algorithm proved a balanced accuracy score = 0.93, a mean accuracy score = 0.99, and a mean recall score = 0.94. It showed the best score over the models.

The disadvantage of using these models is that the accuracy scores of the high_risk prediction are significantly lower than the accuracy scores of the low_risk prediction which could potentially cause errors in the overall accuracy of the credit card risk assessment.
