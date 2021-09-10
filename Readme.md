# Basic Bitcoin's Tweeet Sentiment Analysis

`Summary` → Sentiment analysis of bitcoin's tweets. Data extracted directly from Twitter.

`Requirement` → Twitter API, you can create one from [twitter developer page](https://apps.twitter.com/).

__GO TO:__ [`Problem Description`](#ProblemDescription) [`Project Summary`](#Project-summary)
[`Library Used`](#Requirements) 

---
## Problem Description
![Bitcoin](https://images.unsplash.com/photo-1591994843349-f415893b3a6b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80)

The price of Bitcoin is very volatile and depends on various factors. One of the main factors that affect the price of bitcoin price is social media. Different groups of people share their thoughts on social media which affects the sentiment of bitcoin which in turn affects its price.  And if you are making any investment in bitcoin then it becomes very much important to stay aware of these sentiments. To track the sentiment of bitcoin one can follow social media such as Twitter and Reddit where millions of users discuss about bitcoin. 

---
## Project Summary
In this baisc project I have tried to demonstrate how one can
* Extract tweets of any keyword such as `#Bitcoin` directly from twitter.
* Perform text cleaning, such as removing punctuations, hashtags, retweet tags, emojis, hyperlink, etc.
* Calculate tweet's subjectivity, polarity, and sentiment.
* Filter out +ve, neutral and -ve tweets.
* Visualize most used word related to bitcoin by creating 

---

## Library Used
| Languguage & Library | version|
| :-------- | :------- |
| `python` | `3.7.11` | 
|re|2.2.1
|nltk|3.2.5
|cv2|4.1.2
|tweepy|3.10.0
|string|--
|numpy|1.19.5
|pandas|1.1.5
|textblob|0.15.3
|wordcloud|1.5.0
|matplotlib|3.2.2

| Enviroment | Used|
| :-------- | :------- |
| `Editor`  |`JupyterLab`| 
| `Runtime type` | `CPU`|