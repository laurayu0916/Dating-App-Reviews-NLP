# DSO560 Project: NLP in Dating App Reviews 

## Text Preprocessing

**Toolkit:** NLTK, Textacy, langdetect, Regex

1. Remove hastages, Emoji, URL, etc.
2. Lowercase all the characters
3. Lemmatization
4. Use Regex to group semantically similar words

## Regression Model

**Toolkit:** TF-IDF + LightGBM, Word2Vec + Neural Network, DistillBERT, ALBERT

**Goal:** Build a regression model to predict the reviewers' rating based on reviews they provided. 

**Business Use Case:** This model is able to adjust rating scores for apps and correct errors caused by malicious scoring and mismatch between reviews and rating. For instance, some users who have negative feelins about the app may incorrectly give the highest scores and this model can be used to find it.

## Classification Model

**Toolkit:** Word2Vec + RandomForest, GloVe + RNN, GloVe + LSTM

**Goal:** Build a classification model to predict whether an App review will get more than 1 Thumbup. We assume those reviews with many Thumbups are the "key opinions" from users and deserve more attention from the publisher or developer of the Dating App.

**Business Use Case:** It may take up to a month for an "important" review to accumulate to 100 Thumbups. This model is able to predict how many Thumbups a review will get in the future immediately. 

## Topic Modeling

**Toolkit:** DistillBERT Embeddings + umap-learn + hdbscan + C-TF-IDF

**Goal:** Use a pre-trained BERT model to identify underlying topics respectively for negative reviews and positive reviews. 

**Business Use Case:** Topic Modeling helps the company to filter meaningless information and keep important "topics", which enables the app analytics teams to get insights more efficiently. 
