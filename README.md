# Kaggle's-Quora-Question-Pairs-competition

Predicting whether a pair of questions is duplicates or not and develop machine learning and natural language processing systems to automatically identify when questions with the same intent have been asked multiple times. To solve this we used the Long Short Term Memory network (LSTM) variant of RNNs, which are better at capturing long-term dependencies. We trained word embeddings using Google’s word2vec embeddings, combined them to generate question embeddings for the two questions, and then fed those question embeddings into a representation layer. We then concatenated the two vector representation outputs from the representation layers and fed the concatenated vector into a dense layer to produce the final classification result. 
 
 RNN:  RNN called Recurrent Neural Network because they perform the same task for every element of a sequence and the output being depended on previous computation. It is advanced ANN that involves directed cycles in memory.  

LSTM:  it is special kind of RNN, all RNN network have the form of a chain of repeating module of Neural Network. LSTM is capable of learning long term dependencies for more about LSTM visit http://colah.github.io/posts/2015-08-Understanding-LSTMs/ 

Embedding: Word embedding is a modern way to represent words in deep learning models,  here i use the Google’s word2vec for embedding, to know more about word2vec visit  https://code.google.com/archive/p/word2vec/ 
 
 
