# CREDIT-WISE-LOAN-SYSTEM
Intelligent Loan Approval System

This is an Intelligent Loan Approval System powered by Machine Learning that can automatically analyse applicant details and predict whether a loan should be Approved or Rejected before final human verification.

It focuses on two main challenges that come with manual verification process
1) Good Customer Sometimes get rejected,leading to loss of business.
2) High-risk Customers sometimes get approved,leading to financial losses.

to solve the above problem system uses historical loan application data the system finds the best supervised (classification) machine learning models that can learn hidden patterns from previous customer records and provide accurate ,fast and unbaised loan approval decision  

# Working of project 
In this project we uses a dataset which contain the historical loan application data 

1) Read dataset : used import pandas as pd
2) get dataset info :use pandas library 
3) handling missing data : from sklearn.imputer import SimpleImputer
4) EDA(Exploratory Data Analysis) : to understand the correlation between different features, to get the outliers also plot heatmaps to do feature selection used seaborn library 
5) Categorical data: performed label encoding and one hot encoding to handle categorical data using sklearn.preprocessing import LabelEncoding ,OneHotEncoding
6) split dataset to train and test dataset
7) scaling numerical features :use from sklearn.preprocessing import standardscaler

here the model is trained in two phase before performing the featured engineering and after performing featured engineering 

used 3 supervised (clasification) machine learning model KNN,Naive Bayes and logistice regression .imported the models from sklearn 

to check the performance of the model we have calculated precision_score,acurracy_score,recall_score ,f1-score and also calculated confusion matrix for each model 

before featured engineering and after featured engineering the 

# best model is Naive bayes based on the precision value 

here we focused on two values that is precision value and recall score to get the best model because 
1) precision value give how many high risk customers loan it approved 
2) recall value give how many good customer loan is approved 

and these are the two main challenges that we need to solve 
