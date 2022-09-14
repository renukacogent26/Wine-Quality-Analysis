# Wine-Quality-Analysis

Categorize the target variable "Quality" as 0 (bad) and 1 (good)

The target variable has positive correlation with the feature varaiables 'alcohol','sulphates','citric acid','pH', and 'fixed acidity'

All the feature variables have been used since they are importatnt in determining the quality of wine

Splitting the dataset into train and test data

Various models have been used to find the best accuracy

1. Decision Tree
2. Decision Tree with Bagging
3. Logistics Regression
4. Random Forest
5. Support Vector (SVC)
6. Voting Classification for type "Hard"
7. Voting Classification for type "Soft"
8. GridSelection method for Random Forest
9. GridSelection method for SVC


The accuray score of Decision Tree is 85.9% 

The accuray score of Decision Tree with Bagging is 85.6% which is more equivalent to Decision Tree

The accuray score of LogisticRegression is 87%

The accuray score of RandomForestClassifier 89%

The accuray score of SVC is 85%

The accuray score of VotingClassifier for type "Hard" is 87%

The accuray score of VotingClassifier for type "Soft" is 85.6% which is lesser than Hard type


From the above analysis, Random Forest model has the highest accuracy among all (89%)

To increase the accuracy of the model, GridSearch method has been used to tune the hyperparameters

The accuracy of Random Forest after using GridSearch has been reduced to 86.8%

The accuracy of SVC after using GridSearch has been increased from 85% to 89%

The accuracy of Random Forest after using Cross Validation Score has been increased from 89% to 90%
