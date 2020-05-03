# Reddit Classification Project

This project analyzes a sample of posts (without their comments) from a small subset of very active subreddits. The key tasks in this project are:

1. Exploratory data analysis.
2. Automatically classifying posts to their subreddit.
3. Analyzing the sentiments in reddit post titles.

The EDA also includes data cleaning and understanding the importance of certain featueres which could be utilized in the classification of the posts. There are three algorithms implemented to do the classification:
- Logistic Regression
- Naive Bayes
- Support Vector Machine

There are different feature encoding methods used as well as cross-validation and hyperparameter tuning. The algorithms are compared using the following metrics: accuracy, precision and recall. 

The final part of the project includes using the Vader Analyzier to compute the sentiment of the various posts.
