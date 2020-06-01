This post is the first in two principal parts including visualization and predict the ajusted close price based on Apple stock data using Python.

Data: The dataset consists of Open, High, Low, Closing and Ajd Closing Prices of Apple Inc. stocks from 1st january 2010 to 22th May 2020 - total 2615 items (rows). Each row represents a day’s stock market attributes for the company. It includes following contents:

+ Date: Market session date
+ Open: The opening price for the market session
+ High: The highest price reached during the market session
+ Low: The lowest price reached during the market session
+ Close: The closing price for the market session
+ Adj Close: The adjusted closing price for the market session
+ Volume: The total number of trades performed on the stock during the market session

Works:
+ First, we will import useful packages, read data, check missing data, visualizing stock data (we will concentrate to the Ajusted Close price which is our predicted objectif).
+ Second, we will use two models to predict ajusted close prices: Lost-Short-Term-Memory model, Support Machine Regression model and Multiple regression models. We aim to predict the Ajusted Close price in 23th May 2020. Besides that, have not yet the anounned Adj Close in 30th May 2020, so we will apply these models to predict the Adj Close in 30th May 2020. So we will wait for the true Ajd Close in tomorrow to value our model quality.
+ Lastly, we conclude the results.
