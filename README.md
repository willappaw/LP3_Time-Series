## Improving Store Sales Prediction for Favorita through a Time Series Forecasting Model

## Project Description 
The aim of this project is to assess and forecast the sales of a store by utilizing time series data obtained from Corporation Favorita, a major grocery retailer headquartered in Ecuador. The objective is to construct a predictive model capable of accurately anticipating future sales across the extensive range of products available at various Favorita outlets. This model will aid store management in formulating inventory and sales strategies. As part of this investigation, we will utilize historical data analysis to develop models, formulate scientific hypotheses based on time-stamped historical data, and employ these models to inform future strategic decision-making and observations. Our goal is to assist Favorita Corporation's management in gaining insights from their data to enhance operations and ultimately boost sales.

## Methodology
Cross-Industry Standard Process for Data Mining (CRISP-DM) was used as a guide your data mining efforts.

## CRISP-DM Data mining life cycle
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment


## Business Understanding
This project aims to enhance sales by delving into long-term sales patterns. It aims to identify past occurrences, their effects on sales, potential corrective measures, and, if necessary, the subsequent steps. To offer predictive insights, this research explores various regression techniques.

Hypothesis: Multiple factors such as day of the week, season, promotional offers, and external variables influence the store's sales. Through the analysis of these factors and the development of a time series forecasting model, accurate predictions of the store's future sales can be made.

Null Hypothesis (H0): Promotional activities, oil prices, and holidays do not exert a significant impact on store sales for Corporation Favorita.

Alternative Hypothesis (H1): Promotional activities, oil prices, and holidays have a significant impact on store sales for Corporation Favorita.

## Analytical Questions
1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. Are sales affected by promotions, oil prices and holidays?
6. What analysis can we get from the date and its extractable features?
7. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)

## Data Set details
1. The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
2. store_nbr identifies the store at which the products are sold.
3. family identifies the type of product sold.
4. sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be * * sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
5. onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.
6. the column names of oil dataset t includes information about the daily price of oil .
7. the column names of holidays events data Index(['date', 'type', 'locale', 'locale_name', 'description', 'transferred'], dtype='object')
8. the column names of stores data Index(['store_nbr', 'city', 'state', 'type', 'cluster'], dtype='object')
9. the column names of sample submission data Index(['store_nbr', 'city', 'state', 'type', 'cluster'], dtype='object')
10. the column names of test data Index(['id', 'date', 'store_nbr', 'family', 'onpromotion'], dtype='object')
11. the column names of train data Index(['id', 'date', 'store_nbr', 'family', 'sales', 'onpromotion'], dtype='object')
12. the column names of stores data Index(['date', 'store_nbr', 'transactions'], dtype='object')