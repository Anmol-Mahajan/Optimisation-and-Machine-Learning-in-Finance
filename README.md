# Optimisation-and-Machine-Learning-in-Finance

Consider the .csv file available with 1700 observations of 26 financial and accounting metrics for a set of firms in several different industries. For each observation, the last column denotes the rating according to Moody’s, while the second-to-last column denotes whether the assets are of investment grade or not; ratings in the set {Aaa, Aa1, Aa2, Aa3, A1, A2, A3, Baa1, Baa2, Baa3} are in an investment grade.
The task is to classify a firm’s credit rating into one of the 16 categories and to predict whether a firm is considered investment grade or not. To do so, you should split the dataset in a training set and a test set in a 80%:20% ratio. You are asked to implement
- a linear regression approach with Ridge (or L1) and Lasso (or L2) regularisation to predict whether a firm is in an investment grade or not
- a logistic regression approach with Ridge (or L1) and Lasso (or L2) regularisation to predict whether a firm is in an investment grade or not
- a Neural Networks based approach to classify the firm’s rating into one of the rating categories and predict if it is in an investment grade
