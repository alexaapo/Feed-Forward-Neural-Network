# Feed Forward Neural Network for Twitter Sentiment Analysis Dataset

Here I develop a sentiment classifier using feed-forward neural networks for the Twitter sentimentanalysis dataset [avalaible here](https://drive.google.com/file/d/1dTIWNpjlrnTQBIQtaGOh0jCRYZiAQO79/view). 

I experimented and developed 3 models and compare them over F1 score, Recall and Precision. 

For the development of the models, I experimented with:
* the number of hidden layers and the number of their units
* the activation functions
* the loss function
* the optimizer, etc

I implement one model with pre-trained word embendding vectors using ***GloVe*** and the other two I selected ***TF-IDF*** vectorization.
I also have a notebook with the preprocess of the data.

In the end, I choose my best model and describe the reasons why I concluded to that architecture. 
For the best model I plot also the loss vs epochs and the ROC curve and explain.

#### My solution is implemented in PyTorch and the report is well documented. For running the notebooks, I used the Google Colab with its GPU.

You can check the Google Colab Notebooks here: 
  * Preprocessing of data: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DjBOVZ1mnOCe4rTxmfTdFhZ3CS5a7ZRC)
  * 1st model with TF-IDF: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SR_j7FUYcJ21CCsIT8fkRjGOteevQEPa) 
  * 2nd model with Glove: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HewOLQCpt033LXODfGWxBDu56ODmo1v6) 
  * 3rd model with TF-IDF: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kjoZ-wEiju0_QuOC5-_QIZ1rTEnJWuIU) 
