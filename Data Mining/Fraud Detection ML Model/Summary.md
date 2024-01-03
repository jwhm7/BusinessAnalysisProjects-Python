# [Fraud Detection ML Model]

### ㆍ Summary

Identify the best working ML algorithm and hyperparameter in detecting fraud.

### ㆍ Process

Data Preprocessing ➔ Experiment Classification Models ➔ Tune Hyperparameters ➔ Conclusion

### ㆍ Used Algorithms/Methods

▸ Basic Model : DecisionTreeClassifier, RandomForestClassifier
<br/>
▸ Hyperparameter Tuning : GridSearchCV, RandomizedSearchCV

### ㆍ Conclusion

▸ The RandomForestClassification model with parameter found using GridSearchCV showed the highest model accuracy and f1-score.
<br/>
  However, the precision and recall score for 1 are both too low.
<br/>
▸ The DecisionTreeClassification model with parameter found using RandomizedSearchCV showed the most balanced score with fair accuracy.
