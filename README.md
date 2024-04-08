# Fight Price Prediction

## What we will see in this Notebook
- Problem Statement
- Importing Libraries
- Loading the dataset
- Data Inspection
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Checking for null values
- Using Encoding to Handle categorical data
- Feature Selection
- Building Machine Learning models
- Hyperparameter Tuning
- Conclusion

### Problem Statement

I have build an ML model that predicts flight ticket prices based on various independent features, using a dataset of flight ticket prices from the Kaggle website. The dataset includes prices for various airlines and cities between March and June of 2019, with a training set of 10,683 records and a test set of 2,671 records. The prediction results can be beneficial for both travelers, who can use it to make informed decisions about their travel, and for airlines, who can use it to forecast competitors' rates and adjust their pricing strategies to maximize revenue while remaining competitive.

- Size of training set: 10683 records
- Size of test set: 2671 records
- Link of the dataset:- https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh

### Conclusion

We have used random forest regressor for training the model and improved its accuracy by doing hyperparameter tuning. As a result, we have trained our **Random Forest Regression model**, to forecast fares of flight tickets, with an R2 score of 82 %.
