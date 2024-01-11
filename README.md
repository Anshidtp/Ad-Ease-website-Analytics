# Ad Ease website Analytics

**Web Traffic Time Series Forecasting**

Forecasting the future values of multiple time series. More specifically the problem of forecasting future web traffic for approximately 145,000 wikipedia articles.

The training dataset consists of approximately 145k time series. Each of these time series represent a number of daily views of a different Wikipedia article, starting from July, 1st, 2015 up until December 31st, 2016.
For each time series, you are provided the name of the article as well as the type of traffic that this time series represent (all, mobile, desktop, spider). You may use this metadata and any other publicly available data to make predictions. Unfortunately, the data source for this dataset does not distinguish between traffic values of zero and missing values. A missing value may mean the traffic was zero or that the data is not available for that day.


### Steps :

    1. We will start by loading the data and handling the values.

    2. Then some Exploratory data analysis to get an understanding of the data and get some useful insight, based on various parameters, and visualizing them.

    3. Preparing the data for feeding to the model(checking stationary, transformations).

    4. Preparing the model and doing some predictions.

    5. Comparing with given data and calculating the accuracy of the model.


