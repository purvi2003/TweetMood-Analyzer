# TweetMood-Analyzer
TweetMood Analyzer is a way of identifying sentiments and opinions expressed in tweets on X.

The main computational steps in this process are determining the polarity or sentiment of the tweet and then categorising them into the positive, negative, or neutral tweet (or irrelevant = doesn't specify anything). 

The primary issue is the identification of the most suitable sentiment classifier that can correctly classify the tweets. 

Sentiment analysis is one of the emerging tasks in the field of Natural Language Processing and Data Science. Generally, base classification technique like Naive Bayes classifier, Random Forest classifier and Logistic Regression are being used. In this project, an ensemble classifier has been proposed that combines the base learning classifier to form a single classifier, with an aim of improving the performance and accuracy of sentiment classification technique. 

Introduction:

X (formerly Twitter) is a fast growing online platform where people can create, post, update and read short text messages called tweets. Through tweets, users can share their opinions, views and thoughts about a specific topic. In general, Sentiment Analysis (SA) is the way of identifying and categorizing the polarity of a given text at document, sentence and phrase level. 

This technique is being used in many fields like e-commerce, health care, entertainments and politics, to name a few. As an example, Sentiment Analysis is useful for companies to monitor consumer opinions regarding their product, and for consumers to choose the best products based on public opinions. The main task in Twitter SA is to determine the opinion of the tweet is either positive, negative or a neutral opinion. 

The main challenges of twitter sentiment analysis are:

1. tweets are generally written in informal language 

2. short messages show limited cues about sentiment 

3. acronyms and abbreviations are widely used on twitter. 
