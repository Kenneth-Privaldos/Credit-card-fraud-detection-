# Credit Card Fraud Detection using XGBoost

# Introduction
Credit card fraud was a serious issue that resulted in financial losses and damage to my credit rating. In this project, I built a machine learning model to detect fraudulent credit card transactions in real time.

I used the Logistic Regression and XGBoost (eXtreme Gradient Boosting) algorithms, which are popular and effective choices for a wide range of classification tasks. XGBoost is an implementation of gradient boosting designed to be highly efficient and scalable, while Logistic Regression is commonly used in binary classification. I compared the two algorithms and chose the one that was more suited for this application.


# Data
The dataset we will use for this project is the Credit Card Fraud Detection dataset from Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud). The dataset contains a total of 284,807 instances, with 492 instances (0.172% of all transactions) classified as fraudulent. Each instance has 31 features, which represent various characteristics of the transaction such as the amount, time, and location.

# Preprocessing
Before we can train our model, we will need to preprocess the data to handle missing values and scale the features to have a similar range. We will also split the dataset into training and testing sets to evaluate the performance of our model. We also did different sampling methods such as SMOTE, SMOTEK, & TOMEKLINKS.

# Training
Next, we will train our XGBoost model on the training data. We will tune the hyperparameters of the model using cross-validation to find the optimal set of parameters that gives the best performance.

# Evaluation
After training the model, we will evaluate its performance on the testing data. We will use various metrics such as precision, recall, and F1 score to assess the quality of the model's predictions.

# Conclusion
In this project, we built a machine learning model to detect fraudulent credit card transactions using the XGBoost algorithm. We preprocessed the data, trained the model, and evaluated its performance on the testing data. With the appropriate parameters and evaluation metrics, we were able to achieve good results and help protect against credit card fraud.
