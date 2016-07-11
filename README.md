# P5-Amazon-Book-Purchase-Prediction
Udacity: Machine Learning Nanodegree, Project 5

### Project Summary:
Recommender Systems are to help people discover new content, find the content we were already looking for, discover which things go together, personalize user experiences in response to user feedback, recommend incredible products that are relevant to our interests and identify things that we like, which are basically to model people’s preferences, opinions and behavior. Our recommender system model in this project can be used for evaluating users’ purchase habits, predicting whether or not users may buy some items. Then we can recommend book items to users. If you have used services like Amazon, Job Board or Netflix, it is often to find some recommendations suggesting items for you to buy, jobs you may be interested or movies to watch. We will use this idea to build a similar application like them.

In this project, we will build a recommender systems to make predictions related to reviews of Books on Amazon. The dataset is 1,000,000 Amazon Book Reviews, which provided us purchase information. Our target was to predict whether the user purchased the item based on these reviews.

### Run Instruction
In a terminal or command window, navigate to the top-level project directory project 5/ and run one of the following commands:
```
ipython notebook project 5.ipynb jupyter notebook project 5.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data
Assignment data is available on:
http://jmcauley.ucsd.edu/data/assignment1.tar.gz
- itemID: The ID of the item. This is a hashed product identifier from Amazon.
- reviewerID: The ID of the reviewer. This is a hashed user identifier from Amazon.
- helpful: Helpfulness votes for the review. 
- reviewText: The text of the review.
- summary: Summary of the review.
- unixReviewTime: Time of the review in seconds since 1970.
- reviewTime: Plain-text representation of the review time.
- category: Category labels of the product being reviewed.

### Tasks:
Purchase prediction: predict given a (user,item) pair from ‘pairs_Purchase.txt’ whether the user purchased the item (really, whether it was one of the items they reviewed). Predictions should be labeled 1 (purchased) or 0 (not purchased). Accuracy will be measured in terms of the classification accuracy.

### Techiniques used in project:
- Python
- Pnadas
- Sklearn
- Machine Learning
- Collaborative Filtering

### Reference
- [1] http://cseweb.ucsd.edu/classes/fa15/cse190-a/files/assignment1.pdf
- [2] http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
- [3] https://github.com/scikit-learn/scikit-learn/blob/51a765a/sklearn/linear_model/logistic.py#L925
- [4] http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.DictVectorizer.html
