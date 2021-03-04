# Feed Forward Neural Network for Twitter Sentiment Analysis Dataset

Here I develop a sentiment classifier using feed-forward neural networks for the Twitter sentimentanalysis dataset [avalaible here](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view). 

I experimented and developed 3 models and compare them over F1 score, Recall and Precision. 

For the development of the models, I experimented with:
* the number of hidden layers and the number of their units
* the activation functions
* the loss function
* the optimizer, etc

I implement one model with pre-trained word embendding vectors using GloVe and the other two I selected TF-IDF vectorization.

In the end, I choose my best model and describe the reasons why I concluded to that architecture. 
For the best model I plot also the loss vs epochs and the ROC curve and explain.

#### My solution is implemented in PyTorch and the report is well documented.
