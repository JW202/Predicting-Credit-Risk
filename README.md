# Predicting-Credit-Risk

## Supervised Machine Learning

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. 

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

The data is located in the Resources folder.

* `lending_data.csv`

Import the data using Pandas.

## Consider the models

You will be creating and comparing two models on this data: a logistic regression, and a random forests classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook or in a separate document) your prediction, and provide justification for your educated guess.

## Fit a LogisticRegression model and RandomForestClassifier model

Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. You may choose any starting hyperparameters you like. Which model performed better? How does that compare to your prediction? Write down your results and thoughts.

## Results and Predictions

The machine learning algorithms random forest and logistic regression are used for various disciplines for classification and regression purposes.

Logistic regression is a parameter based model and random forest is a non-parametric model. Logistic regression will perform better since it mapsqualitative or quantitative imput features to a target variable. It is used to predict financial, biological or socialogical data in supervised machine learning.

Random Forest however is ensemble-based learning algorithm, comprised of n collections of de-correlated decision trees.

Results:

Logistic Regression model training data score = 0.9921240885954051 
Logistic Regression model testing data score = 0.9918489475856377

Random Forest Classifier model training data score = 0.9975409272252029 
Random Forest Classifier model testing data score = 0.991642591828312
