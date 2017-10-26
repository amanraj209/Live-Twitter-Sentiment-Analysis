# Live Twitter Sentiment Analysis

This live twitter sentiment analysis marks a tweet as positive or negative by running several machine learning classifiers together.

All the machine learning classifiers cast their votes on a particular tweet and then the tweet's confidence level is marked.

## Installation

- Install Natural Language Processing Toolkit (nltk)

```
import nltk
nltk.download()
```
This will download all of the corpora.
 
- Install tweepy using pip

```
pip install tweepy
```

- Generate Consumer key, Consumer Secret, Access token and Access secret by registering an application on [Twiiter Apps](https://apps.twitter.com/).
Copy and paste these required keys in `twitter_sentiment_analysis.py` file.

## Usage

- Make a new directory **_pickled_algos_** in the root directory.

- Run `module_for_sentiment_analysis.py` file to train machine learning models on movie review texts.

- Run `twitter_sentiment_analysis.py` to stream live tweets on console and mark them as positive or negative.

- Simultaneously run `graphing_live_tweets.py` to generate live graph for the marked categories.

## Folder Structure

```
twitter_sentiment_analysis/
    README.md
    graphing_live_tweets.py
    module_for_sentiment_analysis.py
    sentiment_mod.py
    twitter_sentiment_analysis.py
    .gitignore
    short_reviews/
        negative.txt
        positive.txt
```

## Contributions

If there is any issue in the source code, send me pull request and contribute to this project.