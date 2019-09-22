# Reuters-newswire-topics-classification
## The Reuters dataset
We will be working with the Reuters dataset, a set of short newswires and their topics, published by Reuters in 1986. It's a very simple, widely used toy dataset for text classification. There are 46 different topics; some topics are more represented than others, but each topic has at least 10 examples in the training set.

We'll use 10,000 most frequently occurring words in the training data. Rare words will be discarded. This allows us to work with vector data of manageable size.

## Model for Multi-Class Classification using Keras
##### Hidden layers = 2 with 64 neuron in each layer
##### Relu activation is used for hidden layer and softmax for final layer.
##### Using batch_size=512, epoch = 9 We get good Accuracy of around 88%
