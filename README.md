# Credit_Risk_Analysis



## Overview
The purpose of this analysis was to build and evaluate various machine learning models to evaluate individual customer credit risk. The dataset used to train the models was from LendingClub, "a peer-to-peer lending services company." After being cleaned, the dataset consisted of 68,817 entries, and was heavily unbalanced, with only 0.5% of entries being classified as "high-risk." 

![loan_status.png](https://github.com/klkanchi/Credit_Risk_Analysis/blob/main/images/loan_status.png)


The machine learning algorithms used were:

RandomOverSampler
SMOTE
ClusterCentroids
SMOTEENN
BalancedRandomForestClassifier
EasyEnsembleClassifier
The models were run and then evaluated for performance and accuracy at predicting credit risk.

Credit risk analysis using scikit-learn and imbalanced-learn on sample credit data.

In examining the results we will look at the Balanced Accuracy Score as well as the Imbalanced Classification Report (ICR) from each model. Of particular interest in the ICR are two figures from the "f1" (F-score) column - the number from the bottom "avg / total" row, as well as the f-score from the "high risk" row, since we're primarily interested in our ability to detect high credit risk individuals.

The following results are presented in ascending levels of performance, based on their Balanced Accuracy Scores, starting with the worst-performing model and moving to the best.

Cluster Centroids **Undersampling** gave us the worst results, with an accuracy score of 0.5295. That means that it did little better than 50%, or a 50/50 coin-toss, at accurately predicting credit risks.



