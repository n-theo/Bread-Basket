# Bread-Basket
Breadbasket Bakery Sales Prediction

For this open ended task, we will examine the [Bread Basket Dataset](https://www.kaggle.com/datasets/mittalvasu95/the-bread-basket), which contains all transactions from an Edinburgh bakery between 30th October 2016 and 9th April 2017. We we will also use a weather dataset for the same period to gain more insights.

In the following notebook I've outlined my thought porcess (and mistakes) and performed two main tasks:

- I have built a classifier that predicts whether a hot beverage will be sold given the time and weather conditions of a sale (More of a proof of concept).
**Disclaimer:** From the first stage of building the classifier I was aware that the task is too optimistic as the data is very granular. However, I still outline my methodology and main steps.

- I have built a regression model that predicts the number of sales for a given hour of day and some whether conditions at that hour.
