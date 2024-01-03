## [Homesite Quote Conversion, Which Customers Will Purchase A Quoted Insurance Plan?]

### ㆍ Summary
Experimented 5 ML algorithms with SMOTE, stacking, and hyperparameter tuning that predict which customers will purchase a given quoted price.
<br/>
<br/>
### ㆍ Process
Basic Models &nbsp;➔&nbsp; Implement SMOTE with Different Ratios &nbsp;➔&nbsp; Perform Stacking and Hyperparameter Tuning &nbsp;➔&nbsp; Conclusion
<br/>
<br/>
### ㆍ Used Algorithms/Methods
▸&nbsp; Basic Model : DecisionTreeClassifier, RandomForestClassifier, LinearSVMClassifier, MultiLayerPerceptron, KNeighborsClassifier
<br/>
▸&nbsp; Improving Model : SMOTE(ratio=0.5, 0.7, 0.9), RandomizedSearchCV
<br/>
<br/>
### ㆍ Conclusion
▸&nbsp; The original dataset is highly imbalanced, as shown by the score difference between the basic model and the one after
<br/>
&nbsp;&ensp; implementing SMOTE.
<br/>
▸&nbsp; In terms of RandomForestClassifier score, the model before stacking and parameter tuning is higher than after the <br/>
&ensp; &nbsp;implementation
<br/>
<br/>
### ㆍ Reference
<img width="461" alt="image" src="https://github.com/jwhm7/MS-Business-Analytics-Projects/assets/82855650/0b3b35a0-50a3-4241-b90a-0bbc9e3051a2">
