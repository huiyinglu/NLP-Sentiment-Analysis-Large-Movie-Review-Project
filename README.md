# NLP-Sentiment-Analysis-Large-Movie-Review-Project
This project implements a sentiment classification application for a large movie review dataset from IMDB. The dataset is the Large Movie Review Dataset often referred to as the IMDB dataset. The Large Movie Review Dataset contains 25,000 highly polar moving reviews (good or bad) for training and the same amount again for testing. The problem is to determine whether a given moving review has a positive or negative sentiment.

In this project, we will develop multiple potential solutions and pick the most suitable one for this problem. NLP problems can be solved by using simple "Bag of Words" method plus simple Machine Learning classifier like Naïve Bayes. However, the subtler way to solve the NLP problem would be using word embedding plus Deep Neural Networks such as LSTM (with optional CNN plus Maxpooling layer). This is because:

- Bag of Words method can only utilize the statistic information of the corpus (occurrence counts of words), while word embedding may capture the characteristics of each word in higher dimension vector space and better utilize word analogies;

- LSTM can learn either the short-term or long-term context/dependencies between symbols in the input sequences while simple Machine Learning classifiers won’t able to do these.

Based on the above reasons, our solution will be a model using word embedding plus RNN (using LSTM).

Text classification/sentiment analysis problem can be easily found in our daily life – Yelp review, movie review, survey for something, etc. The techniques suggested in this project can be easily applied to these applications.
