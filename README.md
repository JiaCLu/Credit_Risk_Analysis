# Credit_Risk_Analysis

## Overview of the analysis:
The credit risk analysis apply machine learning to solve outnumber risky loans. I use the credit card credit dataset from LendingClub and apply the dataset using imbalanced-learn and scimitar-learn libraries to build models using resampling. I then compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results:

### Oversampling: 
Compare Naive Random Oversampling and SMOTE algorithm to determine which algorithm results in the best performance.

#### Naive Random Oversampling
- Balanced accuracy score: 64%
- Precision score: 99%
- Recall score: 62%
![Naive Random Oversampling](https://github.com/bobocomfy/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random.png)

#### SMOTE Oversampling
- Balanced accuracy score: 65%
- Precision score: 99%
- Recall score: 69%
![SMOTE Oversampling](https://github.com/bobocomfy/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

### Undersampling:
Test an undersampling algorithms to determine which algorithm results in the best performance compared to the oversampling algorithms above.

#### ClusterCentroids
- Balanced accuracy score: 54%
- Precision score: 99%
- Recall score: 40%
![ClusterCentroids](https://github.com/bobocomfy/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

#### SMOTEENN Algorithm
- Balanced accuracy score: 64%
- Precision score: 99%
- Recall score: 57%
![SMOTEENN Algorithm](https://github.com/bobocomfy/Credit_Risk_Analysis/blob/main/Resources/Combination.png)

### Ensemble Learners:
Compare two ensemble algorithms to determine which algorithm results in the best performance.

#### Balance Random Forest Classifier
- Balanced accuracy score: 79%
- Precision score: 99%
- Recall score: 87%
![BalanceRandomForest](https://github.com/bobocomfy/Credit_Risk_Analysis/blob/main/Resources/Balanced_Random_Forest.png)

#### Easy Ensemble AdaBoost Classifier
- Balanced accuracy score: 92%
- Precision score: 99%
- Recall score: 90%
![EasyEnsembleClassifier](https://github.com/bobocomfy/Credit_Risk_Analysis/blob/main/Resources/Easy_Ensemble_AdaBoost.png)

## Summary:
