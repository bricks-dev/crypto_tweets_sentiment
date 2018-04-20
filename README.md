# crypto_tweets_sentiment
Transfer IMDB sentiment analysis model to crypto currency related tweets

## Problem:
Is twitter's bitcoin sentiment corellated with bitcoin's price?

## Solution:
1. Train sentiment analysis model. [100%]

2. Crawl for tweets of bitcoin thought leaders. [0%]

3. Used trained model to make sentiment prediction. [0%]

4. Compare timeline of tweets with timeline of market movement. [0%]

5. If there is some corellation on this smaller dataset, setup server to run on a long term dataset. [0%]

## Sentiment analysis with pytorch as explained in fastai lesson 4

http://forums.fast.ai/t/wiki-lesson-4/9402/1

## Setup

#### 1. Follow fastai's setup procedure, don't use `pip install fastai`, pull the github directory, this is because fastai is changing really fast.

fastai's conda environment has all the dependencies you will need.

#### 2. There will be a fastai folder that conains the fastai library code that we need, copy this folder into the project folder.

This is the folder you want:

![this is the fastai folder you want](https://github.com/mingrui/crypto_tweets_sentiment/raw/master/copy_fastai.png)

#### 3. Make a `models` folder, the `.h5` files will be put into this directory

#### 4. the `.pkl` file will be put into project directory

This is what my project folder looks like:

![project folder](https://github.com/mingrui/crypto_tweets_sentiment/raw/master/dir.png)

#### 5. have fun!
