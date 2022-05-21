# Unit 12—Tales from the Crypto

## Background

Apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. 
Apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.


### 1 - Sentiment Analysis

Used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores for each coin.

***Bitcoin News***
![Bitcoin News](Images/BitcoinNews.png)

***Ethereum News***
![Ethereum News](Images/EthereumNews.png)

***Bitcoin Sentiment score dataframe***

![Bitcoin Sentiment scores](Images/Bitcoin_sentiment_analysis.png)

***Ethereum Sentiment score dataframe***
![Ethereum Sentiment Scores](Images/Ethereum_sentiment_analysis.png)

***Bitcoin Sentiment score summary***
![Bitcoin Sentiment Summary](Images/Bitcoin_sentiment_summary.png)

***Ethereum Sentiment score summary***
![Ethereum Sentiment Summary](Images/Ethereum_sentiment_summary.png)


Answer the following questions:

> Which coin had the highest mean positive score?
***Bitcoin has the hightest mean positive score of 0.059450***
> Which coin had the highest negative score?
***Both coins has same hightest negentive score of 0.30000***
> Which coin had the highest positive score?
***Ethereum has the highest positive score of 0.269000***


### 2 - Natural Language Processing

Use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 

#### Tokenize
1. Lowercased each word.
2. Removed punctuation.
3. Removed stop words.


***Bitcoin Word Cloud***
![Bitcoin Word Cloud](Images/Bitcoin_word_cloud.png)

***Ethereum Sentiment score summary***
![Ethereum Word Cloud](Images/Ethereum_word_cloud.png)




#### N-grams

Checked the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

#### Word Clouds

Generated word clouds for each coin to summarize the news for each coin.

***Bitcoin Word Cloud***
![Bitcoin word cloud](Images/btc-word-cloud.png)

***Ethereum Word Cloud***
![Ethereum word cloud](Images/eth-word-cloud.png)

***Bitcoin and Ethereum Top Words***
![Bitcoin and Ethereum Top words](Images/Bitcoin_Ethereum_Top_words.png)


### 3 - Named Entity Recognition

Build a named entity recognition model for both coins and visualize the tags using SpaCy.

***Bitcoin NER***
![Bitcoin NER](Images/BitcoinNER.png)

***Ethereum NER***
![Ethereum NER](Images/EthereumNER.png)


