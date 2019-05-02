### Sentiment_Analysis:

Our job is to analyze the sentiment of the customer's tweets and predict the category of the sentiment as "positive","negative","neutral"

##### Part1. Model used: Random Forest, Support Vector Machine in Scikit-learn

First I have utilized scikit-learn's Random Forest and SVM model for predicting the sentiments.

Performed Gridsearch over parameters and cross-validation.

##### Part2: Embednet: Word embedding and avg, maxpool 2d in Pytorch

Test accuracy:
SVM - 78%
Random Forest - 75%
Embednet - 86%

