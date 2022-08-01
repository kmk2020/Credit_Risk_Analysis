# Credit_Risk_Analysis

![image](https://user-images.githubusercontent.com/89704371/182047198-9171280b-440b-43d2-a583-d90ca3fcc0ba.png)

# Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:

* BalancedRandomForestClassifier  
* EasyEnsembleClassifier  
* imbalanced-learn
* SMOTE algorithms
* ClusterCentroids algorithm
* RandomOverSampler
* scikit-learn
* SMOTEENN algorithm

## Purpose of the Analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk

This analysis included the following tasks ;

* Use Resampling Models to Predict Credit Risk
* Use the SMOTEENN Algorithm to Predict Credit Risk
* Use Ensemble Classifiers to Predict Credit Risk


* A Written Report on the Credit Risk Analysis (README.md)

# Results
The results for the six (6) machine learning models including their respective balanced accuracy, precision, and recall scores are as follows

### Naive Random Oversampling

![image](https://user-images.githubusercontent.com/89704371/182048744-a9de9450-2008-4f3a-a03c-956cc66a30f4.png)

### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/89704371/182048761-d3ee9d25-502d-4d7d-a69f-196a71e7358e.png)

### Undersampling

![image](https://user-images.githubusercontent.com/89704371/182048776-a1cec7ae-d175-405d-9fe2-921addf0d172.png)

### Combination Over and Under Sampling

![image](https://user-images.githubusercontent.com/89704371/182048799-8eceb765-2c3f-435f-92c7-2dcee51ce4a8.png)


### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/89704371/182048661-703720c2-a3cc-4cab-9c59-2f413247c9ce.png)

### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/89704371/182048628-74785ff1-896d-4047-b450-b7dac5c307d4.png)

# Summary

## Recommendation
