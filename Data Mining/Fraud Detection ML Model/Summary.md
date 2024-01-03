## [Fraud Detection ML Model]

### ㆍ Summary
Identified the best working ML algorithm and hyperparameter in detecting fraud.
<br/>
<br/>
### ㆍ Process
Data Preprocessing &nbsp;➔&nbsp; Experiment Classification Models &nbsp;➔&nbsp; Tune Hyperparameters &nbsp;➔&nbsp; Conclusion
<br/>
<br/>
### ㆍ Used Algorithms/Methods
▸&nbsp; Basic Model : DecisionTreeClassifier, RandomForestClassifier
<br/>
▸&nbsp; Hyperparameter Tuning : GridSearchCV, RandomizedSearchCV
<br/>
<br/>
### ㆍ Conclusion
▸&nbsp; The RandomForestClassifier model with parameter found using GridSearchCV showed the highest model accuracy and f1-score.
<br/>
&ensp;&nbsp; However, the precision and recall score for 1 are both too low.
<br/>
▸&nbsp; The DecisionTreeClassifier model with parameter found using RandomizedSearchCV showed the most balanced score with fair 
<br/>
&ensp;&ensp;accuracy.
