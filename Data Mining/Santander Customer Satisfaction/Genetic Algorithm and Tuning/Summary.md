## [Santander Customer Satisfaction, Which Customers Are Happy Customers?_Genetic Algorithm and Tuning]

### ㆍ Summary
Derived the best working model by selecting features and comparing the score of basic model and tuned model.
<br/>
<br/>
### ㆍ Process
Data Preprocessing &nbsp;➔&nbsp; Feature Selection &nbsp;➔&nbsp; i) Top 25 &nbsp;➔&nbsp; Basic Model &nbsp;➔&nbsp; Tuned Model
<br/>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ii) Top 50 &nbsp;➔&nbsp; Basic Model &nbsp;➔&nbsp; Tuned Model &nbsp;➔&nbsp; Conclusion
<br/>
<br/>
### ㆍ Used Algorithms/Methods
▸ &nbsp;Basic Model : RandomForestClassifier, GradientBoostingClassifier
<br/>
▸ &nbsp;Feature Selection Method : GeneticSelectionCV
<br/>
▸ &nbsp;Hyperparameter Tuning Method : RandomizedSearchCV
<br/>
▸ &nbsp;Preprocessing Method : OneHotEncoding, Undersampling
<br/>
<br/>
### ㆍ Conclusion
▸ &nbsp;Classifiers with Hyperparameter tuning have higher scores.
<br/>
▸ &nbsp;+) Models with undersampling method have higher Kaggle score than SMOTE.
