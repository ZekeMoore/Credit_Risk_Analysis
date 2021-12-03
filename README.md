# Module 17 - Credit Risk Analysis

## Overview 

#### The Credit Risk Analysis was to use apply machine learning to Q1 2019 LoanStats in order to predict credit risk. Resampling, SMOTEENN and Emsemble classifiers were methods used. 


## Results
### RandomOverSampler
 * **Balanced Accuracy Score**: 64.63%
 * **Precision Score - High Risk**: 0.01
 * **Precision Score - Low Risk**: 1.00
 * **Recall Score Difference**: 0.08%

![stacked_launch_outcomes](https://github.com/ZekeMoore/Credit_Risk_Analysis/blob/main/Resources/RandomOversampler.png)

### SMOTE
 * **Balanced Accuracy Score**: 64.68%
 * **Precision Score - High Risk**: 0.01
 * **Precision Score - Low Risk**: 1.00
 * **Recall Score Difference**: 0.06%

![stacked_launch_outcomes](https://github.com/ZekeMoore/Credit_Risk_Analysis/blob/main/Resources/SmoteOversampler.png)

### ClusterCentroids
 * **Balanced Accuracy Score**: 54.42%
 * **Precision Score - High Risk**: 0.01
 * **Precision Score - Low Risk**: 1.00
 * **Recall Score Difference**: 0.25%

![stacked_launch_outcomes](https://github.com/ZekeMoore/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

### SMOTEENN
 * **Balanced Accuracy Score**: 66.64%
 * **Precision Score - High Risk**: 0.01
 * **Precision Score - Low Risk**: 1.00
 * **Recall Score Difference**: 0.21%

![stacked_launch_outcomes](https://github.com/ZekeMoore/Credit_Risk_Analysis/blob/main/Resources/Smoteenn.png)

### BalancedRandomForestClassifer
 * **Balanced Accuracy Score**: 78.85%
 * **Precision Score - High Risk**: 0.03
 * **Precision Score - Low Risk**: 1.00
 * **Recall Score Difference**: 0.17%

![stacked_launch_outcomes](https://github.com/ZekeMoore/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifer.png)

### EasyEnsembleClassifier
 * **Balanced Accuracy Score**: 93.17%
 * **Precision Score - High Risk**: 0.09
 * **Precision Score - Low Risk**: 1.00
 * **Recall Score Difference**: 0.02%

![stacked_launch_outcomes](https://github.com/ZekeMoore/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier.png)



## Summary
#### Based on the 6 different methods, EasyEnsembleClassifier is the preferred method. It had the highest accuracy score of 93.17%. The next highest was score 14% below EasyEnsembleClassifier. It had the highest percission for high-risk at 0.09, when most other models had 0.01. And the smallest difference in recall score with 0.02%
