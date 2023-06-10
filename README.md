# STOCK-MARKET-FORECASTING-WITH-TRADING-STRATEGY

In this stock market project I have used Spotify stock dataset to analyze its trend and find investement opportunities and it's risk using 2 trading strategy 
1) Buy-and-hold Strategy
2) Labelling Based Strategy

you can use any stock data for this project and make necessary changes to see appropriate results.

I have written 2 python scripts (compute weekly return File1 & Stock dataplot File2) to first gather the stock data and plot weekly stock price. To download any stock data first run File 1 it will generate 2 csv file name "Detailed" & "Volatility", then to generate weekly plots run File 2 make sure to change the ticker name with stocks name. The next procedure was to label the data, I manually labelled the "Volatility" dataset from the weekly plots of the stock (if you are using another stock data make sure you have to run the plot_batch_File2.py to generate the plots first) to train various Machine Learning models based on this labels. Green indicates the stock is going up for that that particular week and red indicates  the stock is going down for that particular week. 

I performed Exploratory Data Analysis (EDA) to understand the stock data and it's trend and then performed Price forecasting with linear regression of different window sizes as well. Inaddition I have build 14 different classification Machine Learning models to get trained on 2018 year labelled data and make predictions for 2019 year data, I then used the predicted labels & performed Trading strategy on those labels and find insights of investment opportunities and risk if invested with $100.

Below is the result table of each model's accuracy and returns on the investment
![Capture](https://github.com/Ravisheel/STOCK-MARKET-FORECASTING-WITH-TRADING-STRATEGY/assets/49792350/100853ab-59e6-45d0-a963-1e78166033a2)



Indepth details I have already provided in the jupyter notebook!!
Happy Coding!!

