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
▸ &nbsp;Basic Model : DecisionTreeClassifier
<br/>
▸ &nbsp;Finding Important Features : roc_auc_score, xgboost, plot_importance
<br/>
▸ Improving Model : SMOTE, GridSearchCV
<br/>
<br/>
### ㆍ Conclusion
▸ &nbsp;The DecisionTreeClassifier model with optimized random_state and parameter showed the highest Kaggle score among 6 models.
<br/>
▸ &nbsp;The model accuracy was the highest with the basic model.
<br/>
<br/>
### ㆍ Reference
