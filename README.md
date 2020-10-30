# Sentiment Analysis on Code Mixed Text

This project is aimed at performing sentiment analysis on unconventional text data, ie. "Hinglish" which is a combination of Hindi and English.
The practical viabiliy of this implementation rests in understanding the popularity of support of policy decisions in Indian Politics via social media platform.

## Dataset
The data used in this research consists of manually collected set of tweets on various political domains. These tweets were fetched using the Twitter API.

## Preprocessing
The data preprocessing stage includes
* Lowercase
* removing special characters
* reference names to respective political party (eg: Modi ke plan mast hai!! ---> <BJP> ke plan mast hai!!
* Lemmatization
* Stopword Removal
* Tokenization
* Padding
* Token to Embedding

## Classification Algorithms

* GRU
* LSTM
* CNN

