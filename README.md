# Automatic-essay-grader-using-LSTM
Project uses NLP for the cleaning of data(removal of stop words, lower casing the words), for tokenization we use punkt and regexp tokenizer. Then, convert the processed input as word vectors. Further we use the Word2Vector model for achieving the normalized word vectors. We use K-fold validation for the test and training sets. We use 2-layer LSTM with normalized word vectors as input for predicting the scores as a continuous value between 0-10 like in a regression problem.
