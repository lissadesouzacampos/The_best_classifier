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

The following table summarizes the accuracy metrics obtained for each model (with parameters chosen to maximize accurary but avoid overfitting).

Model               | Jaccard	  | F1 score	 | Log loss
--------------------|-----------|-----------| --------
KNN	                | 0.814286  |	0.897638	 | NA
DecisionTree        |	0.846154	 | 0.916667	 | NA
SVM                 |	0.814286	 | 0.730934	 | NA
LogisticRegression	 | 0.814286	 | 0.730934	 | 0.578891

## Conclusion
The best model is the Decision Tree. It presented the highest Jaccard and F1 scores, and it predicted less wrong payoffs. Check out its confusion matrix:

![image](https://user-images.githubusercontent.com/65967699/187067645-484f959c-f1a7-4c49-a64b-875070c5e9de.png)


## Obs
This is the Capstone Project of the course *Machine Learning with Python*, an online non-credit course authorized by IBM Skills Network and offered through Coursera.
