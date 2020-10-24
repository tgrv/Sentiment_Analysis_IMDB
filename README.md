# Text Sentiment Analysis on IMDB dataset

This notebook contains a sentiment analysis model to classify movie reviews as **positive** or **negative**. We will use the IMDB movie review dataset (https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz) for developing the model. 

It contains 50000 reviews, which is divided into train and test sets of 25000 reviews each.

Following steps are performed:

1. Load the dataset using Tensorflow datasets, and split into Train and Test sets.
2. Tokenize sentences into numeric sequence vectors of fixed length, with padding if required.
3. Define our Neural Network model consisting of Embedding, Pooling and Dense layers, with Sigmoid activation in the output layer, and `Binary CrossEntropy` as loss function.
4. Train the model.
5. Get Model Accuracy.
6. Visualize Training and Validation Accuracy and Loss.
7. Run model on new custom data to get predictions.