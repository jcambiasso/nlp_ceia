# Natural Language Processing
These series of notebooks are educational takes on various NLP strategies, from count vectors to transformers, in the context of the University of Buenos Aires Machine Learning specialization. 

The main theme for this repository is the rules text of cards from Magic: The Gathering trading card game. 

The notebooks are in order of complexity with the following contents:

## MTG - NLP - 0 - Database retrieval
Main dataset retrieval from MTGJSON and general preprocessing. When running locally, it is preferable to run this notebook first to download necessary files.

## MTG - NLP - 1 - Basic vector count
Brief explanation of motivation for the theme and usage of classic machine learning techniques with word count vectors and TF-IDF matrixes to predict card color identity.

## MTG - NLP - 2 - Embeddings
Using Gensim library to generate a Skipgram word2vec embedding of the MTG vocabulary.

## MTG - NLP - 3 - RRNs
In this notebook the usage of recurrent neural networks, specially the Long-short term memory units, is explored. The Gensim embedding is used (will be downloaded from a Google Drive location if absent) in a recurrent network to produce a simple language model capable of producing new text for cards.

## Extra NLP - 4 - seq2seq
A little sidestep from the MTG world, a seq2seq encoder-decoder model is used to train a QandA bot employing an online dataset of questions and answers pair.

## MTG - NLP - 5 - Bert and sentiment analysis
Finally, a Bidirectional Encoder Representations from Transformers (BERT) model is used to try and predict the EDHREC Saltiness score of the whole MTG cards (up to date).
