# Credit_Risk_Analysis

## OVERVIEW
The objective of this analysis is to predict the Credit Risk. We are using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Envirnment
 - Juyoter notebook
 - Python

## Results

- Naive Random Oversampling - 68%
- SMOTE Oversampling - 64%
- Undersampling - 52%
- Combination (Over and Under) Sampling -62%
- Balanced Random Forest Classifier - 89%
- Easy Ensemble AdaBoost Classifier -94%
