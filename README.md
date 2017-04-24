# Word2Vec-for-The-Big-Short
 A two-layer neural networks that are trained to reconstruct linguistic contexts of words from Michael Lewis's book, The Big Short

# Introduction
Since I am a big fan of Michael Lewis, I have transformed his book the big short into a large corpus of text which will then produce a vector space of unique word.
By using gensim, nltk, glob, scipy and etc., several hundred dimensions can be compressed into just 2 dimensions. 

# Content
In this python notebook, we will first load the data from the book and tokenize it. Then we will build and train the model with an amazing tool word2vec. After dimensionality reduction, data can be plotted as below.

# Result
Here is an sample of the graph.

Here is another example of linear relationship of words.
As male is related to female, as doctor is related to nurse.
1. careful is related to positive, as derogatory is related to negative
2. fools is related to lacked, as Atlantic is related to powerful
3. weak is related to American, as succinct is related to Chinese
4. action is related to Chinese, as settled is related to American

# Acknowlegement 
This python notebook is based on Siraj Ravel's Game of Throne word2vec notebook. 
