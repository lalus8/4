_________________________________________________
Twitter Sentiment Analysis

( Positive, Neutral or Negative Finder )
_________________________________________________
# Twitter Sentiment Analysis 


# Dataset Information

The objective of this task is to detect Negative; Neutral; Positive speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a Label: 0 -> Negative; 1 -> Neutral; 2 -> Positive sentiment associated with it. So, the task is to classify Negative;  Neutral; Positive tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '0' denotes the tweet is Negative; '1' denotes the tweet is Neutral and label '2' denotes the tweet is Positive, your objective is to predict the labels on the test dataset.

For training the models, we provide a labelled dataset of ~58M tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.

Twitter-roBERTa-base for Sentiment Analysis
This is a roBERTa-base model trained on ~58M tweets and finetuned for sentiment analysis with the TweetEval benchmark.

Labels: 0 -> Negative; 1 -> Neutral; 2 -> Positive

# Tasks
Text Classification


# Libraries used
<li>Transformers
<li>Scipy
<li>PyTorch
<li>TensorFlow
<li>JAX


# Use These Commands To install Libraries:
pip install transformers
(We Use this Package to Download the Model from the Hugging Face Website)
pip install scipy
(We're going to use it to Convert the Output of the Model into Probability Scores)




# Algorithms

<li>Logistic Regression
etc.
  
**Best Model Accuracy:** 95.00
_________________________________________________