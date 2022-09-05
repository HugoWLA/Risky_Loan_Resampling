# Risky_Loan_Resampling

## Overview of the Analysis

The purpose of this Analysis is to bring balance to credit risk classification using various techniques to train and evaluate models
with imbalanced classes. For this analysis we will use lending data that provides loan information from over 77,000 loans. This gives
us plenty of information to get solid feedback for our analysis and how we view future loans and predict credit worthiness.
Using 'y' as our 'loan status' variable and 'X' as our variable to represent the remaining columns (loan_size, interest_rate, borrower_income,	debt_to_income,	num_of_accounts, derogatory_marks,	total_debt,	loan_status) we where able to check the balance of the variables to predict using the
'value_counts' function before spliting the data into training and testing datasets using 'train_test_split'.

The stages of our machine learning process where as follows.

* Model: A machine learning model mathematically represents a collection of untrained real world information. Creating a model of our untrained data was the first step.

* Fit: The fit or "training stage" is used to fit the model to the data. The model is adjusted to match patterns in the data learning
to adjust or "train" itself to make predictions matching the data we give it.

* Predict: Once the model has been fit or "trained" to the data we can use the trained model to predict new data. When the model is given
new data that's similar enough to the data that previoulsy recieved it can predict the outcome for that data.

Methods used to aqcuire resampled data where 'RandomOverSampler' and 'LogisticRegression'. The purpose of using 'RandomOverSampler'
is to randomly select instances of the minority class and add the to the training set until we have balanced the majority and minority classes.
'LogisticRegression' is a classification algorithm. It is designed to predict discrete ourtcomes therefor we can use it to make predictions by
analyzing available data. When presented with a new sample of data the model mathimatically determines the probability of the sample belonging
to a class. The model then assigns the sample to that class.




## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
