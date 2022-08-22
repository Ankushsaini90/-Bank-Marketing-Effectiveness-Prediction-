# -Bank-Marketing-Effectiveness-Prediction-
## Summary
One of the industries that is being transformed the most by the recent Machine learning advances is the finance industry. Be it predicting the stock prices, or in our case predicting, a customer willingness to subscribe to a term deposit. Therefore, in our project we have come up with a solution that increases the efficiency by making fewer calls but improves the success rate.

Our experiment can help understand what could be the reason for the classification of such labels by feature selection, data analysis and prediction with machine learning algorithms taking into account previous trends to determine the correct classification.

## Problem Statement
The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe to a term deposit (variable y).

## Steps involved:
Exploratory Data Analysis 
After loading the dataset we performed this method by comparing our target variable that is y (deposit) with other independent variables. This process helped us figuring out various aspects and relationships among the target and the independent variables. It gave us a better idea of which feature behaves in which manner compared to the target variable.

Null values Treatment
Our dataset contains no null values which is very good because null values might tend to disturb our accuracy.

Encoding of categorical columns 
We used One Hot Encoding and Label Encoding to produce binary integers of 0 and 1 to encode our categorical features because categorical features that are in string format cannot be understood by the machine and needs to be converted to numerical format.

Standardization of features
Our main motive through this step was to scale our data into a uniform format that would allow us to utilize the data in a better way while performing fitting and applying different algorithms to it. 
The basic goal was to enforce a level of consistency or uniformity to certain practices or operations within the selected environment.

## Conclusion:

That's it! We reached the end of our exercise.
Starting with loading the data so far we have done EDA , null values treatment, encoding of categorical columns, feature selection and then model building.
In all of these models our accuracy revolves in the range of 79 to 94%.
And there is no such improvement in accuracy score even after hyperparameter tuning.
So the accuracy of our best model is 92% which can be said to be good for this large dataset. This performance could be due to various reasons like: no proper pattern of data, too much data, not enough relevant features.
