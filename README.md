# Twitter Sentiment Classification: Belief in Climate Change
## Project Description
This project aims to predict an individual's belief in climate change based on their tweets. It does so by training a machine learning model on a dataset of tweets labeled as either expressing belief in climate change or not. The model can then be used to classify the sentiment of new tweets on this topic.

## Data
The dataset for this project consists of tweets scraped from Twitter and labeled as either expressing belief in climate change (1) or not (-1) 0 for neutral, 2 for News. It includes both the text of the tweet and the sentiment classification.

## Model
The machine learning model used in this project is a [insert model name here]. It was trained on 80% of the data and tested on the remaining 20%. The model achieved an F1 of 0.75 on the test set.

## Usage
To use the model to classify the sentiment of a new tweet, pass the tweet text to the predict() function of the model. The function will return a prediction of 1 for belief in climate change or -1 for no belief, 0 for neutral, 2 for News.

## Requirements

