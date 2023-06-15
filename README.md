# Sentiment-Analysis-of-Amazon-Product-Reviews

### Introduction

Sentiment analysis is a natural language processing (NLP) method which is utilized to predict whether
data is positive, negative, or neutral i.e., the sentiment of the data. Sentiment analysis is often performed
on textual data.
A sentiment is an attitude, belief, or conclusion brought on by a sensation. It is commonly referred to
as opinion mining, examining how individuals feel about particular things. 

In this project, we particularly look at sentiment analysis of an Amazon product based on the customer
reviews. Each review corresponds to a rating from 1 to 5. The goal of sentiment analysis is to determine
the overall emotional tone of a review. 

### Methodology

The basic steps in a binary sentiment analysis task are:
1. Preprocessing of the text data:
• Tokenization of the review into separate words.
• Removal of stop words, punctuation, and special characters, lemmatization.
2. Use of Word2Vec pretrained word embedding from TensorFlow hub.
3. Converting ratings from 1 to 5 into binary classification. Five rating as ‘1’ and rest ratings as
‘0’ using one hot encoding technique.
4. Training a binary classifier on the represented text samples(reviews) to predict the sentiment of
new reviews using LSMT and RNN deep learning models.
5. Model testing.
