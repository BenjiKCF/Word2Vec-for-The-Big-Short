# Word2Vec-for-The-Big-Short
 A two-layer neural networks that are trained to reconstruct linguistic contexts of words from Michael Lewis's book, The Big Short

# Introduction
Since I am a big fan of Michael Lewis, I have transformed his book the big short into a large corpus of text which will then produce a vector space of unique word.
By using gensim, nltk, glob, scipy and etc., several hundred dimensions can be compressed into just 2 dimensions. 

# Content
In this python notebook, we will first load the data from the book and tokenize it. Then we will build and train the model with an amazing tool word2vec. After dimensionality reduction, data can be plotted as below.

# Acknowlegement 
This python notebook is based on Siraj Ravel's Game of Throne word2vec notebook. 
