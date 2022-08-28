# The_best_classifier

## Business problem
Predict whether a loan case will be paid off or not given data on previous loans.

## Solution strategy

1. Build classifiers using several machine learning algorithms:
 - k-nearest neighbour;
 - Decision Tree;
 - Support Vector Machine;
 - Logistic regression.
2. Use accuracy metrics to select best classifier.

## Results
 
Model               | Jaccard	  | F1 score	 | Log loss
--------------------|-----------|-----------| --------
KNN	                | 0.814286  |	0.897638	 | NA
DecisionTree        |	0.846154	 | 0.916667	 | NA
SVM                 |	0.814286	 | 0.730934	 | NA
LogisticRegression	 | 0.814286	 | 0.730934	 | 0.578891

The model that predicted less wrong payoffs was the decision tree, as shown by the confusion matrix; it is also the model with the highest Jaccard and F1 score, as seen in the table above. Yet, it is difficult to interpret this model with the large max_depth parameter chosen. Further analysis regarding the features chosen and its relation with the accuracy and predictions of the model would be necessary to grasp it. 

## Obs
This is the Capstone Project of the course *Machine Learning with Python* developed by IBM Skills Network and offered on Coursera.
