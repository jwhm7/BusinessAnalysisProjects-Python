# [Homesite Quote Conversion, Which Customers Will Purchase A Quoted Insurance Plan?]

### ㆍ Summary
Experimented 5 ML algorithms with SMOTE, stacking, and hyperparameter tuning that predict which customers will purchase a given quoted price.
<br/>
<br/>
### ㆍ Process
Basic Models ➔ Implement SMOTE with Different Ratios ➔ Perform Stacking and Hyperparameter Tuning ➔ Conclusion
<br/>
<br/>
### ㆍ Used Algorithms/Methods
▸ Basic Model : DecisionTreeClassifier, RandomForestClassifier, LinearSVMClassifier, MultiLayerPerceptron, KNeighborsClassifier
<br/>
▸ Improving Model : SMOTE(ratio=0.5, 0.7, 0.9), RandomizedSearchCV
<br/>
<br/>
### ㆍ Conclusion
▸ The original dataset is highly imbalanced, as shown by the score difference between the basic model and the one after implementing SMOTE.
<br/>
▸ In terms of RandomForestClassifier score, the model before stacking and parameter tuning is higher than after the implementation
<br/>
<br/>
### ㆍ Reference
<img width="461" alt="image" src="https://github.com/jwhm7/MS-Business-Analytics-Projects/assets/82855650/0b3b35a0-50a3-4241-b90a-0bbc9e3051a2">
