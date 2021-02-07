# Credit_Risk_Analysis

## Purpose:

The purpose of this analysis is to compare six different types of decision making algorithms on how well they predict high risk loans. The six types we are comparing are:
1. Naive Random Oversampling
2. SMOTE Oversampling
3. Undersampling
4. Combination Sampling
5. Balanced Random Forest Classifier
6. Easy Ensemble AdaBoost Classifier

## Results:

The balanced accuracy scores for the six types were:
1. Naive Random Oversampling: 0.660
2. SMOTE Oversampling: 0.654
3. Undersampling: 0.654
4. Combination Sampling: 0.544
5. Balanced Random Forest Classifier: 0.996
6. Easy Ensemble AdaBoost Classifier: 0.942

The Precision results for the high risk category were:
1. Naive Random Oversampling: 0.01
2. SMOTE Oversampling: 0.01
3. Undersampling: 0.01
4. Combination Sampling: 0.01
5. Balanced Random Forest Classifier: 0.95
6. Easy Ensemble AdaBoost Classifier: 0.09

The recall results for the high risk category were:
1. Naive Random Oversampling: 0.74
2. SMOTE Oversampling: 0.62
3. Undersampling: 0.67
4. Combination Sampling: 0.72
5. Balanced Random Forest Classifier: 0.36
6. Easy Ensemble AdaBoost Classifier: 0.92

![Random Oversampling](https://github.com/ccastanette/Credit_Risk_Analysis/blob/main/pics/random.png)
![SMOTE Oversampling](https://github.com/ccastanette/Credit_Risk_Analysis/blob/main/pics/SMOTE.png)
![Undersampling](https://github.com/ccastanette/Credit_Risk_Analysis/blob/main/pics/Undersampling.png)
![Combo Sampling](https://github.com/ccastanette/Credit_Risk_Analysis/blob/main/pics/combo.png)
![Balanced Random Forest](https://github.com/ccastanette/Credit_Risk_Analysis/blob/main/pics/Forest.png)
![AdaBoost Classifier](https://github.com/ccastanette/Credit_Risk_Analysis/blob/main/pics/AdaBoost.png)

## Summary

At first glance both the Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifier have a high enough accuracy score to make it look like they are good candidates. The next step would be to find a method that has both a high precision and high recall and since none of the methods can manage a more than .5 in both of those I do not feel like any of these methods can be recommended.
