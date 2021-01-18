# Team 8 - Project Proposal

Our project is build an algo trading machine which rely on 3 different indicators: Sentiment Analysis, Technical Analysis, and Candlestick Pattern Recognition.
The three indicators will be feed through Recurrent Neuron Network and train with data from Alpaca-API, TwitterText-API to learn to predict the next trading period whether we should buy or sale the stock.

### Files

[Integrated Notebook](Integrated.ipynb) - Main file for this project contains code for Candlestick patterns, Technical Analysis signals and Machine Learning models. 

[News_API Notebook](News_API/news_api.ipynb) - Generate sentiment data to use in Integrated Notebook. This file create sentiment data csv files and place them in Sentiment_data folder.