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

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/70069730/139970539-dff82a2e-c98e-4359-bf4d-c937ca044fe4.png)
  - Accuracy: 62.4%
  - High Risk: Precision: 1% Recall: 59%
  - Low Risk: Precision: 100% Recall: 66%

### Undersampling
![image](https://user-images.githubusercontent.com/70069730/139970615-929f01c0-a62b-4230-8bb6-576d43380ae3.png)
  - Accuracy: 51.1%
  - High Risk: Precision: 1% Recall: 59%
  - Low Risk: Precision: 100% Recall: 44%

### Combination Sampling
![image](https://user-images.githubusercontent.com/70069730/139970709-c510151a-6699-4621-8a8c-d107ec644938.png)
  - Accuracy: 63.8%
  - High Risk: Precision: 1% Recall: 70%
  - Low Risk: Precision: 100% Recall: 57%
