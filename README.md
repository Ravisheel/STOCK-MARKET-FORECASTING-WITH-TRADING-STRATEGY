# STOCK-MARKET-FORECASTING-WITH-TRADING-STRATEGY
Check this Stock Market project, where I gathered the data from yahoo finance website, performed indepth trend analysis and build various Machine Learning model to analyse the opportunity of investment and it's risk.

In this stock market project I have used Spotify stock dataset to analyze its trend and find investement opportunities and it's risk with 2 trading strategy written by me
1) Buy-and-hold Strategy
2) Labelling Based Strategy
you can use any stock data for this project and make necessary changes to see appropriate results.

I have written 2 python scripts (compute weekly return File1 & Stock dataplot File2) to first gather the stock data and plot weekly stock price. To download any stock data first run File 1, then to generate weekly plots run File 2 make sure to change the ticker name with stocks name. The next procedure was that I manually labelled the dataset by consistently looking into the weekly plots of the stock (if you are using another stock data make sure you have to run the plot_batch_File2.py to generate the plots first) to train various Machine Learning models by green (the stock is going up for that that particular week) and red (the stock is going down for that particular week). 

I performed Exploratory Data Analysis (EDA) to understand the stock data and it's trend and then performed Price forecasting with linear regression of different window sizes as well. Inaddition I have build 14 different classification Machine Learning models to get trained on 2018 year labelled data and make predictions for 2019 year data, then after getting the prediction I performed Trading strategy on those labels and find insights of investment opportunity and risk.




Indepth details I have already provided in the jupyter notebook!!

