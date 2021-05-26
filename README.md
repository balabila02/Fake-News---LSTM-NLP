# Fake-News---LSTM-NLP

Clasification of News -> whether it is a fake news or real news

Dataset: https://www.kaggle.com/c/fake-news/data#

**Data Preprocessing**

1. Stemming
2. Stopwords
3. punctuation
4. one hot for word embedding
5. lowering the words
6. word embeding -> fixing the vocab_size and n_dim

**Model**

1. LSTM
2. used Dense layer without batch normalization
3. Loss function - cross_entropy
4. Optimizer - Adam
5. Activation - Sigmoid(as it is a binary clasification)
6. Adding dropout

** Performance metrics**
1. Accuracy_score
