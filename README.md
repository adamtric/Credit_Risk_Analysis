# Credit_Risk_Analysis

## Overview

The purpose of this project is to help develop a model that will help predict credit risk. By utilizing differnet algorithms and models, we can decide which model we want to use to predict credit risk. In this project we will use 6 different types of models: Random Oversampling, SMOTE, Undersampling, Combination (Oversampling and Undersampling), Random Forest Classifier, and AdaBoost.

## Results

### Naive Random Oversampling- 
* Balanced Accuracy: 0.64 
* Precision: 0.99 (99% of True Positives were actually correct)
* Recall: 0.68 (68% of actual positives were identified correct)

![image](https://user-images.githubusercontent.com/102189324/183317668-1b158eee-1e87-4f3f-983d-a441225793a6.png)

### SMOTE Oversampling- 
* Balanced Accuracy: 0.64 
* Precision: 0.99 (99% of True Positives were actually correct)
* Recall: 0.68 (68% of actual positives were identified correct)

![image](https://user-images.githubusercontent.com/102189324/183317830-06c0e581-d8b3-4ea9-8fca-43b06adf5778.png)


### Undersampling- 
* Balanced Accuracy: 0.51 
* Precision: 0.99 (99% of True Positives were actually correct)
* Recall: 0.44 (44% of actual positives were identified correct)

![image](https://user-images.githubusercontent.com/102189324/183317870-e63473b6-634c-4465-ae5c-97008ea7244f.png)


### Combination Sampling- 
* Balanced Accuracy: 0.62 
* Precision: 0.99 (99% of True Positives were actually correct)
* Recall: 0.55 (55% of actual positives were identified correct)

![image](https://user-images.githubusercontent.com/102189324/183317893-ec8de4c2-82f4-4cc5-b150-5c350d0609df.png)


### Balanced Random Forest Classifier- 
* Balanced Accuracy: 0.80 
* Precision: 0.99 (99% of True Positives were actually correct)
* Recall: 0.93 (93% of actual positives were identified correct)

![image](https://user-images.githubusercontent.com/102189324/183317915-967bb650-a563-4761-a7d9-fa76a02d7660.png)


### AdaBoost- 
* Balanced Accuracy: 0.92 
* Precision: 0.99 (99% of True Positives were actually correct)
* Recall: 0.94 (94% of actual positives were identified correct)

![image](https://user-images.githubusercontent.com/102189324/183317927-f4599271-bade-423d-b51d-4a21b7a3315c.png)

## Summary

We can tell from our analysis and testing of the six different models, each model had a Precision of 99%. This mean's that each model was highly accurate in predicting True positives. However, we see more accurate numbers in Recall and Balanced Accuracy score when we tested Ensemble models (AdaBoost and Balanced Random Forest Classifier). The AdaBoost had a recall of 94% while the Balanced Random Forest Classifier had a recall of 93%, meaning they were more accurate in identifying credit risks that ended up being true. True accuracy scores of thes two models did differ by 12%, however.

Based on these results I would reccommend using the AdaBoost. This model had the highest Recall and Balanced Accuracy scores, showcasing a truly accurate model when it comes to predicting credit risk.
