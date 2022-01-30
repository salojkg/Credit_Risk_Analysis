# Credit_Risk_Analysis

## Overview
The objective of this analysis is to predict the Credit Risk. We are using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. RandomOverSampler and SMOTE algorithms are used for oversample the data and ClusterCentroids algorithm is used for undersample. Combination of over and under sampling is done using the SMOTEENN algorithm. We are comparing two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Envirnment
 - Jupyter notebook
 - Python

## Results

- Naive Random Oversampling 

<img width="524" alt="Oversampling" src="https://user-images.githubusercontent.com/90934630/151718476-92e077e4-197d-42eb-9fbf-f3b95df51706.png">

Balanced Accuracy Score 68%

- SMOTE Oversampling 

<img width="551" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/90934630/151718507-53d83eb9-8705-43c3-8722-c43f97fcbffa.png">

Balanced Accuracy Score 64%


- Undersampling 

<img width="507" alt="undersampling" src="https://user-images.githubusercontent.com/90934630/151718543-fb1650c9-ffaa-470f-9aea-34445cb9df6a.png">


Balanced Accuracy Score 52%

- Combination (Over and Under Sampling) 


<img width="496" alt="combination" src="https://user-images.githubusercontent.com/90934630/151718570-c7955678-327e-4a09-af54-6b1d8cb63814.png">


Balanced Accuracy Score 62%

- Balanced Random Forest Classifier

<img width="504" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/90934630/151718592-011d7361-9753-48ed-acc7-1db5a4b850d3.png">

Balanced Accuracy Score 89%

- Easy Ensemble AdaBoost Classifier

<img width="510" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/90934630/151718612-f550c14f-5464-4acd-8a0a-611fcc54dd06.png">

**Balanced Accuracy Score 94%

## Summary

Of all the models I recommende to use the Easy Ensemble AdaBoost Classifier as it has the maximum accuracy score above 90%.


