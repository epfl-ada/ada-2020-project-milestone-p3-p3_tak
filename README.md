# Title: Future predictions using Google Trends data

## Abstract

The original paper focuses on proving that search engine data (Google Trends more specifically) can help predict near term indicators by building simple baseline models with and without the search data.
We propose as a first step to further investigate that claim by building better models, hopefully obtaining a stronger proof of the Google Trends data. The idea is to build a better baseline model as the choice of lag 1 and 12 seems to be 'arbitrary'. Analyzing autocorrelations plots will enable us to create a better model using only economic index data. Through statistics and timeseries analysis will be able to test for causality between economic index and trends data.
A better baseline model is very relevant as through the process descibed before we will be able to infer with strong confidence the added value of google trends.

Secondly we'd like to determine if trends data has future predictive power on a relevant financial index. The fear and uncertainty in the financial market can be caused by several event (elections, Covid-19...) and Trends data represents an alternative data source on topics that are hard to quantify.
The VIX is a volatility (implied volatility) measure of  the S&P 500, it represents the volatility expected by the market and it is called the 'fear index'.
Several baseline models are widely used to predict VIX (ARIMA, Garch). After a selection of relevant trends topics we are going to explore their predictive power.

## Research Questions

- Can we improve the baseline models proposed in the paper ?
- Do Google Trends really improve the predictions or was it just due to a bad model ?
- Can we predict the VIX index ?
- Does Google Trends have future predicting power ?

## Proposed Datasets

[Yahoo Data for VIX](https://finance.yahoo.com/quote/%5EVIX/history?p=%5EVIX) is available to download as a .csv for daily, weekly or monthly frequencies.
