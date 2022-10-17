# Credit_Risk_Analysis
## Overview

The purpose of this analysis is to help Fast Lending, a peer to peer lending service company, to create a quicker and more reliable loan experience for the users. In turn, through this analysis, they will more easily be able to identify good candidates for loans, which will lead to lower default rates.


## Results
To assess the credit worthiness of a user, we will need to be able to distinguish good and bad candidates and be sure that that the results are precise. Therefore, in this use case, the best model will be one that will have the high precision/recall score and high F1 value.

### Native Random Oversampling
[Native Random Oversampling](/Resources/NativeRandomOversampling.PNG)

- Accuracy Score: 64.4%
- Recall: 59%
- F1: 74%

Accoding to these outputs, we can see that the Native Random Oversampling has a recall score of 59% and F1 score of 74%.

### SMOTE Oversampling
[SMOTE Oversampling](/Resources/SMOTEOversampling.PNG)

- Accuracy Score: 66.3%
- Recall: 69%
- F1: 82%

Accoding to these outputs, we can see that the SMOTE Oversampling has a recall score of 69% and F1 score of 82%.

### Undersampling
[Undersampling](/Resources/Undersampling.PNG)

- Accuracy Score: 54.5%
- Recall: 40%
- F1: 57%

Accoding to these outputs, we can see that the Undersampling only has a recall score of 40% and F1 score of 57%.

### Balanced Random Forest Classifier
[Balanced Random Forest Classifier](/Resources/BalancedRandomForestClassifier.PNG)

- Accuracy Score: 78.9%
- Recall: 87%
- F1: 93%

Accoding to these outputs, we can see that the Balanced Random Forest Classifier has a recall score of 87% and F1 score of 93%.

### Combination Sampling
[Combination Sampling](/Resources/CombinationSampling.PNG)

- Accuracy Score: 54.5%
- Recall: 57%
- F1: 72%

Accoding to these outputs, we can see that the Combination Sampling has a recall score of 87% and F1 score of 93%.

### Easy Ensemble AdaBoost Classifier
[Easy Ensemble AdaBoost Classifierg](/Resources/EasyEnsembleAdaBoostClassifier.PNG)

- Accuracy Score: 93.2%
- Recall: 94%
- F1: 97%

Accoding to these outputs, we can see that the Easy Ensemble AdaBoost Classifier has a recall score of 94% and F1 score of 97%.

## Summary
For this analysis we need to use an algorithm that will create a more reliable loan approval experience to more easility identify good candidates for loans, which will lead to lower default rates.

According to the algorithms ran here, we can see that the Easy Ensemble AdaBoost Classifier model is the best model to use. It has the highest recall score and the highest F1 score, which means that the imbalance between the sensitivity and precision is low. In addition to the high precision and and F1 score, we can see that it has a high accuracy score as well. Therefore, of the six algorithms that were tested, it would be best to use the Easy Ensemble AdaBoost Classifier.
