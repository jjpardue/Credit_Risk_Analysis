# Credit Risk Analysis

## Overview of the analysis: 
Because good loans typically outweigh bad loans, evaluating credit risk is generally and unbalanced classification issue - the data is usually skewed. To analyze the data properly, we employed various models to get a more broad picture of the overall risk. 

Objectives:
- Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN Algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk

These objectives were met using the following six machine learning modules:
 * RandomOverSampler
 * SMOTE
 * ClusterCentroids
 * SMOTEENN
 * BalancedRandomForestClassifier
 * EasyEnsembleClassifier

## Results: 


### Random Oversampling

**The balanced accuracy score for this model was 65% with a precision for high risk being 1% with a recall score of 72%.**

![RandomOverSampling 1](https://user-images.githubusercontent.com/86584404/140253031-61e7a906-ad0e-4e8f-8f89-cf02306cbc12.jpeg)



### SMOTE Oversampling

**The balanced accuracy score for this model was 66% with a precision for high risk being 1% and an overall recall score of 69%.**

![SMOTE 1](https://user-images.githubusercontent.com/86584404/140253038-9a895146-ee87-4048-8152-6eaf35f7a479.jpeg)



### Cluster Centroids

**The accuracy score for this model was 66% with a precision for high risk being 1% and an overall recall score of 40%.**

![ClusterCentroids 1](https://user-images.githubusercontent.com/86584404/140253041-94af78b6-da60-490f-9849-ffb71a5ba7bf.jpeg)



### SMOOTEENN

**The accuracy score for this model was 54% with a precision for high risk being 1% and an overall recall score of 57%.**

![SMOOTEENN 1](https://user-images.githubusercontent.com/86584404/140253045-03d6d6b1-e8a6-4931-be32-fefc6c714ce1.jpeg)



### Balanced Random Forest Classifier

**The accuracy score for this model was 78% with a precision for high risk being 3% and an overall recall score of 88%.**

![BalancedRandomForestClassifier 1](https://user-images.githubusercontent.com/86584404/140253059-d9e48327-666b-4c2d-b6d1-068fab7d7d67.jpeg)



### Easy Ensemble Classifier

**The accuracy score for this model was 92% with a precision for high risk being 9% and an overall recall score of 94%.**

![EasyEnssembleClassifier 1](https://user-images.githubusercontent.com/86584404/140253064-937c0859-4926-4216-847b-bba31bc2c85a.jpeg)



## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

In looking at each model, the overall average high risk score was 2.7%, however, that average was skewed with one score coming in at 9%, vs the other five in the 1-3% range. The average overall recall score for the six models was 70%. Based on overall accuracy and in considering this is an analysis of risk, I would go with the higher high-risk scores and the models that displayed the highest accuracy and overall recall scores - that being, I would recommend pursuing the Balanced Random Forest Classifier and/or the Easy Ensemble Classifier for future forecasts. 

