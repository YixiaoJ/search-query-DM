# Search-query Project

##introduction
The main target of this project is to detect anomaly online credit card transactions. I try six
different classifiers: Naïve Bayes, Decision Tree, K-Nearest Neighbor, Support Vector
Machine, Random Forest, and AdaBoosting with Decision Tree. Random Forest performs
best based on my experiments. A fine-tuning of Random Forest is performed to check if a
better performance can be achieved. 

##Data
The goal of a search engine is to return relevant documents for search queries that users enter.  Search engines typically use hundreds of signals to determine the relevance of a document and then return a list of documents in order of relevance.

You will be provided a training data set which includes 10 attributes and 80,046 observations from search engine query and  url data.  The dataset contains 10 different signals that could be used to help predict whether the url is relevant for the query.  Additionally, a test data set is provided which contains 30,001 observations.  Your goal is to make relevance predictions for each row (urls for a query) in the test data set.   Please download the data from the links provided at the bottom of the page.   

Your job is to create a text file containing one line per example in the test set.  On each line, give your prediction for the relevance (1 for relevant, 0 for not relevant) of that row in the test set.
Be careful when submitting because accidently deleting one line may have large repercussions.
