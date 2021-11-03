# Credit_Risk_Analysis by David Aduaka 

## Overview of credit Risk Analysis Challenge 
In this Challenge, I evaluate credit card risk using the concepts of Supervised machine learning. Using the provided credit card dataset, I;

  - Oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.
  - Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
  - Compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Resources 
  - Data Source: LoanStats_2019Q1.csv
  - Software: Anaconda 4.10.1, kernels mlenv, imbalanced-learn and scikit-learn libraries; Jupyter Notebook

## Results 
Below are the results of each of the machine learning models I created in this challenge.

### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/70069730/139970433-29b539b2-83ba-44ff-a3cc-304c1a92699c.png)
  - Accuracy: 66.3%
  - High Risk: Precision: 1% Recall: 66%
  - Low Risk: Precision: 100% Recall: 67%
