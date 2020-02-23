# Portfolio-Projects

## Classification of Haptik user queries into right Business Verticals using NLP and ML techniques

[HAPTIK PROJECT](https://github.com/nitikagoel01/haptik_project)

The goal of the project was to detect the user intent and classify the user chat into the following categories - food,recharge,support,reminders,travel,nearby,movies,casual and other.

A chat can be classified into multiple categories Ex. “Remind me to book a flight” This query could belong to all the domains in which transactions are possible ( travel, reminder, etc) Thus it was a Multiclass and multilabel problem.

Implemented a multi-label classifier using the training data. The classifier tagged all the possible domains (food, support etc) for each query using Decision Tree, Logistic Regression and Random forest algorithms.
Achieved a label accuracy of 94% and subset accuracy of 74%


## Recommender System for Reddit users - HDFC LIFE
[Recommender System](https://github.com/nitikagoel01/Recommender-System)

The goal of the project is to to predict possibly interesting subreddits to a user based on their comment history. The hypothesis of the recommender model is, given an ordered sequence of user subreddit interactions, patterns will emerge that favour the discovery of paticular new subreddits given that historical user interaction sequence.

Implemented the recommendor system using Collaborative Filtering.
