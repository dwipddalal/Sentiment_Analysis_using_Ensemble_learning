[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
# Sentiment_Analysis_using_Ensemble_learning

## Overview:
The background of the project is around the area of Sentiment analysis. Sentiment analysis is one of the emerging tasks in the field of Natural Language Processing and Data Science. Sentiment analysis, in simple terms, helps to find the author's attitude towards a topic. Sentiment analysis tools categorize pieces of writing as positive, neutral, or negative.

## Problem Statement:
Rotten Tomatoes contains reviews of movies and thus, is a great place to get data from. As a part of our project, our NLP model will be categorizing the reviews provided by users into three sections, positive, negative, and neutral upon processing the labeled data provided by nlp.stanford.edu. The Rotten Tomatoes dataset is a large labeled dataset consisting of movie reviews. Some of the obstacles that could be a potential issue include sentence negation, sarcasm, language ambiguity, etc that make sentence prediction more difficult.

## Exploring the data:
The dataset contains tab and | separated .txt files with phrases from the Rotten Tomatoes dataset. The dataset includes four different files - datasetSentences, datasetSplit, dictionary, and sentiment\_labels.

- **datasetSentences** - It contains 11855 different sentences which have been further divided into different phrases.
- **dictionary** - It contains 239231 different phrases from the above datasetSentences. Each phrase has been given a unique phrase identifier called the PhraseID.
- **sentiment\_labels** - It contains the sentiment value of each above-mentioned phrases corresponding to their phraseID. The values range from 0.00 (most negative) to 1.00 (least positive).
- **datasetSplit** - It is an optional file that has just been made to divide the data into test, train, and validation datasets.

## Applied Approach to the problem:
Dataset visualization and data analysis.
Splitting the data into train, test, and validation sets.
Tokenization of the dictionary.
Word embedding of the reviews.
Training 3 different models: LSTM, Bidirectional LSTM, and Feedforward neural network
Integrated stacking of three different neural networks into an ensemble model.
## Various Techniques used in the model:
Feedforward neural networks
• LSTM 
• Bidirectional LSTM
• early stopping 
• tokenization
• padding 
• integrated stacking (meta learner's neural network) 
• word embeddings

