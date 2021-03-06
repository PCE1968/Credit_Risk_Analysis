# Credit_Risk_Analysis
## Overview
We've been asked to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Purpose
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we’ll need to employ different techniques to train and evaluate models with unbalanced classes.

### The Machine Learning Models

#### Naive Random Oversampling

![Naive Random Oversampling](images/Naive_Random.png)

#### SMOTE Oversampling

![Smote Oversampling](images/smote.png)
#### Undersampling with ClusterCentroids

![Undersampling - ClusterCentroids](images/undersampling.png)

#### SMOTEENN

![Combination - SMOTEENN](images/combination_sampling.png)

#### Balanced Random Forest Classifier

![Balanced Random Forest](images/balanced_forest.png)

#### Easy Ensemble Classifier

![Easy Ensemble Classifier](images/ensemble.png)

### Summary
When we look at the data for each method we can see that the Easy Ensemble Classifier has the highest Balanced Accuracy Score(0.932), the lowest false negative(983) and the highest F1-score(0.97), so for this particular dataset this would be the best choice of method.