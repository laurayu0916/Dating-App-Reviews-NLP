# DSO560 Project: NLP in Dating App Reviews 

## Text Preprocessing

### Toolkit: NLTK, Textacy, langdetect, Regex

1. Remove hastages, Emoji, URL, etc.
2. Lowercase all the characters
3. Lemmatization
4. Use Regex to group semantically similar words

## Regression Model

### Toolkit: TF-IDF+LightGBM, Word2Vec+Neural Network, DistillBERT, ALBERT

**Goal:** <br/>
<br/>
Build a regression model to predict the reviewers' rating based on reviews they provided. 

**Business Use Case:** This model is able to adjust rating scores for apps and correct errors caused by malicious scoring and mismatch between reviews and rating. For instance, some users who have negative feelins about the app may incorrectly give the highest scores and this model can be used to find it.
