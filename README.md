In this project, we will are implementing chatbot from Cornell University's Project.this chatbot using conversations from  Movie Dialogue Corpus . The main features of our model are LSTM cells, a bidirectional dynamic RNN, and decoders with attention.
The conversations will be cleaned rather extensively to help the model to produce better responses. As part of the cleaning process, punctuation will be removed, rare words will be replaced with "UNK" (our "unknown" token), longer sentences will not be used, and all letters will be in the lowercase.
With a larger amount of data, it would be more practical to keep features, such as punctuation. However, I am using FloydHub's GPU services and I don't want to get carried away with too training for too long
