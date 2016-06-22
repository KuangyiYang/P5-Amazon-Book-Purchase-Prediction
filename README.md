# P5-Amazon-Book-Purchase-Prediction
Udacity: Machine Learning Nanodegree, Project 5
## Data
Assignment data is available on:
http://jmcauley.ucsd.edu/data/assignment1.tar.gz
## Define the problem
In this project, we built recommender systems to make predictions related to reviews of Books on Amazon. The dataset is 'train.json.gz’, which is 1,000,000 reviews to be used for training. The fields in this file are:
- itemID: The ID of the item. This is a hashed product identifier from Amazon.
- reviewerID: The ID of the reviewer. This is a hashed user identifier from Amazon.
- helpful: Helpfulness votes for the review. 
- reviewText: The text of the review.
- summary: Summary of the review.
- unixReviewTime: Time of the review in seconds since 1970.
- reviewTime: Plain-text representation of the review time.
- category: Category labels of the product being reviewed.
## Tasks:
Purchase prediction: predict given a (user,item) pair from ‘pairs_Purchase.txt’ whether the user purchased the item (really, whether it was one of the items they reviewed). Predictions should be labeled 1 (purchased) or 0 (not purchased). Accuracy will be measured in terms of the classification accuracy.
## Techiniques used in project:
- Python
- Pnadas
- Sklearn
- Machine Learning
- Collaborative Filtering
