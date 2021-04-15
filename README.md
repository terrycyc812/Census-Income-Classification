# Census Income Classification


### Data Source
[UCL Machine Learning Repository - Census Income Data Set](http://archive.ics.uci.edu/ml/datasets/Census+Income)


### Objective
Build machine learning models to predict whether income exceeds $50K/yr based on census data.   


### Data Cleaning and Feature engineering
- Checking for missing values (absence in this dataset)
- Removing duplicated entries
- Removing the leading blankspace for string data
- Removing entries with unknown data
- Grouping 42 categories into 4 for native_country
- Droping some columns to avoid multicollinearity


### Some visualizations
<img src='images/target.jpg' height=250>
<img src='images/education.jpg' height=250>
<img src='images/country.jpg' height=250>
<img src='images/age.jpg' height=250>


### Machine Learning models used
- Logistic Regression
- KNN
- Random Forest
- AdaBoost
- XGBoost


### Comparison of models
<img src='images/comparison.jpg' height=200>
<img src='images/comparison2.jpg' height=350>
<img src='images/ROC.jpg' height=350>
