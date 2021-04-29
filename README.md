# Census Income Classification


### Data Source
[UCL Machine Learning Repository - Census Income Data Set](http://archive.ics.uci.edu/ml/datasets/Census+Income)


### Objective
Build machine learning models to predict whether income exceeds $50K/yr based on census data.   


### Data set overview
<img src='images/columns.jpg' height=250>
<img src='images/target.jpg' height=250>


### Data Cleaning and Feature engineering
- Removing duplicated entries
- Removing unknown data
- native_country: grouping 42 categories into 4 
- Droping some columns to avoid multicollinearity


### Some visualizations
<img src='images/education.jpg' height=250>
<img src='images/country.jpg' height=250>
<img src='images/age.jpg' height=250>


### Feature pre-processing
- One-hot encoding
- Standard scaling


### Machine Learning models used
- Logistic Regression
- KNN
- Random Forest
- AdaBoost
- XGBoost


### Comparison of models' performances
Accuracy is selected for the model evaluation metrics. After hyperparameter tuning for each model, their accuracies are as below: <br>
<img src='images/comparison.jpg' height=200><br>
<img src='images/comparison2.jpg' height=200>


The 5 models has similar performance. But in terms of accuracy, XGBoost performs the best. 




### Conclusion
- Model used: XGBoost
- Accuracy: 0.84
- F1 Score: 0.66
- ROC-AUC: 0.90


### Next steps for improvement
- Reduce the False positive/negative rate to enhance the performance
- Reduce the overfitting of Random Forest to the minimum level
- Remove the less important features and see if models' performance will improve


### Skills Acquired
- Data manipulation by Pandas
- Feature engineering
- Machine Learning with Hyperparameter tuning
- Model evaluation
