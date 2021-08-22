# CreditRiskAnalysis

## Overview

The aim of this project was to apply machine learning to solve credit card risk.
The data was first analyzed using the RandomOverSampler and SMOTE algorithms, then analyzed using the CLusterCentroids algorithm and a combined oversampling and subsampling approach using the SMOTEENN algorithm.
In order to predict credit risk, the two additional models, BalancedRandomForestClassifier and EasyEnsembleClassifier.
The data was evaluated to classify the credit risk for individuals as "high risk" or "low risk".

## Results

The results were analyzed using the six different machine learning models used.
For each sample it was evaluated:
balanced accuracy score,
the accuracy score
the recall score.

1. Cluster Centroids

![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/ClusterCentroids.png?raw=true)
![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/ClusterCentroids1.png?raw=true)

2.EasyEnsemble

![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/EasyEnsemble.png?raw=true)
![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/EasyEnsemble1.png?raw=true)

3.Naive Random

![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/Naive.png?raw=true)
![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/Naive1.png?raw=true)

4.Smote

![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/SMOTE.png?raw=true)
![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/SMOTE1.png?raw=true)

5.Random Balance

![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/Random.png?raw=true)
![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/Random1.png?raw=true)



6.PRED

![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/PRED.png?raw=true)
![alt text](https://github.com/valeria100719/CreditRiskAnalysis/blob/main/Images/PRED4.png?raw=true)

Summary

Of the six machine learning models evaluated, the best would appear to be Easy Ensemble AdaBoost Classifier.

Easy Ensemble AdaBoost classifier proved: balanced accuracy score = 0.93,

the mean accuracy score = 0.99

the mean recall score = 0.94.

It showed the best score over the others.
The disadvantage of using these models is that the accuracy scores of the high_risk prediction are significantly lower than the accuracy scores of the low_risk prediction which could potentially cause errors in the overall accuracy of the credit card risk assessment.
