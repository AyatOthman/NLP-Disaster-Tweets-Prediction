# NLP-Disaster-Tweets-Prediction
Introduction
Twitter has grown to be a crucial communication tool during emergencies. Smartphones are so common that anyone can instantly report an emergency they are witnessing. As a result, more organisations are interested in automating Twitter monitoring.

Brief about dataset
The Dataset Contain Three csv files:

train
test
sample_submission
Also it Contains Four Columns which are:

The text of a tweet
A keyword from that tweet (although this may be blank!)
The location the tweet was sent from (may also be blank!)
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
🎯 Goal: The objective of this notebook is to build a model that predicts which Tweets are real disasters and which are not.

The Notebook seeks to compare the performance of Machine Learning Models and Deep Learning Models and determine the most accurate one for this task. It also presents text pretreatment techniques used in Natural Language Processing (NLP) at a single point for better comprehension.

Why do we perform text preprocessing
Machine learning models can only interpret numerical numbers, They cannot comprehend text in its natural form. Therefore, all textual information must be represented using numerical values. Additionally, textual information derived from natural language may contain noise and must be cleaned, for as by deleting stopwords and other meaningless text elements.

Methods used for Text Preprocessing
Lower Casing
Remove HTML Tags
Contractions Expansion
Twitter Mention Removal
Remove URLs
Remove Email IDs
Handling Diacritics
Removing Unicode Characters
Handling Digits or Words with Digits
Handling Currency
Handling Abbreviations
Removing Brackets
Filtering Words that represent Emotions
Replacing Logical Operators in Text
Removing Proper Nouns
Handling Compound Words
Handling Idioms and Figurative Language
Spell Checking
Handling Emojis
Remove Stopwords
Remove Extra Spaces
Stemming or Lemmatization
Each method is briefly described in the subsections, and the order of these preprocessing procedures is reviewed at the conclusion. Here is a combined function with all the preprocessing stages stated if you just want to copy it and use it in your code. You can remove the lines for the steps you don't want to do and rearrange the steps in the order necessary.
