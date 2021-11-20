# Sentiment Analysis using LSTMs
- In this project a `word2vec` model is incorporated to capture semantic features of words and convert them into high dimentional word vectors (embeddings). 
- After that Stacked Bi-directional Long Short Term Memory (Stacked Bi-LSTM) model utilizes sequential word vectors transformed from CBOW model to represent contextual features. 
-  `Cross Entropy` is used to find the difference between predicted and real values and calculate loss for each statement. Based on the loss values, `adam optimiser` is used for optimising the paramters.
