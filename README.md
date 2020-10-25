# Text Sentiment Analysis on IMDB dataset

In this notebook, we will be working with the IMDB Moview Review dataset, which contains a text review alongwith its corresponding label - positive (1) or negative (0). The dataset has contains 50000 reviews, which is divided into train and test sets of 25000 reviews each. 
Original dataset can be found at following link:
https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

We will perform following activities:
* Build a classifier to perform Sentiment Analysis on the given data 
* Explore the performance of various Neural Network based models (DNN, LSTM, GRU, Ensemble model)
* Visualize the relationship between Words based on their Embeddings using Tensorboard

Tensorboard Projections:

![word_clusters.jpg](https://github.com/tgrv/Sentiment_Analysis_IMDB/blob/master/word_clusters.jpg)

We can see dense clusters at the opposite ends of the sphere, indicating **positive** and **negative** word clusters

![enthralling.jpg](https://github.com/tgrv/Sentiment_Analysis_IMDB/blob/master/enthralling.jpg)

#### Positive word like "Enthralling" is nearby other positive words such as Excellently, Astounding, Engrossing

![disappointing.jpg](https://github.com/tgrv/Sentiment_Analysis_IMDB/blob/master/disappointing.jpg)

#### Negative word like "Disappointing" is near other negative words such as Awful, Cartoonish, Obscene etc.
