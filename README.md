# MIE1624_Assignment1-2
Combination of assignment 1 and 2 for MIE1624

Dataset
Kaggle survery 2020 responses

Assignemnt 1
- Goals of assignment 1 are to perform exploratory data analysis on the data. 
- The goal is to prepare the data as necessary then report descriptive characteristics of the data. When suitable, the goal is to perform a two-sample t-test with 0.05 threshold when possible. 
- Data will be bootstrapped to compare the mean salary for two groups for 1000 iterations. The bootstrapped data between men and women will be compared with t-tests when possible. 


Assignment 2
- Goal of assignment 2 is to create an ordinal logistic regression with 10-fold cross-validation

Findings resulted that education level (e.g. Bachelor, Master, Doctorate) do have a statistically significant difference in relation to salary levels. In addition, an ordinal logistic regression model achieved a poor accuracy of 0.418 and F1 score of 0.418. Inspection of the results show that the data was skewed towards one specific label, and the model was merely predicting that one label. These results are an indication that the model is inappropriate to tackle the data imbalance. 
