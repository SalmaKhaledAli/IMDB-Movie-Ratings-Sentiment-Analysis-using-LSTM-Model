# IMDB-Movie-Ratings-Sentiment-Analysis-using-LSTM-Model

In this task, I utilized the IMDB Movie rating sentiment analysis dataset. The dataset underwent preprocessing steps to enhance its quality. These steps included the removal of stopwords, punctuations, and digits, as well as converting the words to lowercase and applying lemmatization using the NLTK Library.

To represent the words in vector form, I employed the word2vec technique. Specifically, I utilized the Glove model, which provides vectors of 100 dimensions. This conversion facilitated the utilization of the data in the subsequent model.

Next, I partitioned the dataset into an 80% training set and a 20% testing set. The training set was utilized to train an LSTM model with 20 epochs.

To evaluate the performance of the model, I employed the accuracy metric, which is appropriate for this binary classification problem. The model was trained using the binary cross-entropy loss function and the Adam optimizer.

Upon completion of the training process, the LSTM model achieved a training loss of 0.5751 and an accuracy of 70%. For the testing data, the model obtained a loss of 0.5832 and an accuracy of 69%.
