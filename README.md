# Project_2

## Project Proposal
### USD/CNY Exchange Rate Time Series Analysis

Our project aims to predict movements in the value of the Chinese Yuan versus the U.S. Dollar. We’ll analyze the trend rate throughout the time series. To create a possible forecast, we will also fit a regression model to the historical Yuan and Dollar pairing. 

### Goals
1. Develop a machine learning model that will learn the data's movement pattern.
2. Identify predictable patterns in currency value trends and create a forecast.

### Datasets to be used
Our dataset comes from TradingView as a CSV file. There is a limited selection of currency exchange APIs that support free time-series calls, so we’re choosing the CSV file route.

### Extra library to be used
**Statsmodels** for Linear Regression models.

### Predictions and Conclusions
We’ll give a summary and a visualization of our summary. We will also give a forecast after we perform successful model predicting.

### Breakdown of Tasks
#### Hunt for Data
- Data will come from TradingView
- We’ll download the desired files and convert them to CSV files

### Data Preparation & Model Training
#### Data Cleanup
- Use Pandas to retrieve the files/data, explore the data, and clean it up
- Remove nulls/rebuild missing data with the .dropna() method when the amount of missing data is relatively small
- Find duplicate values and remove them if they’re not necessary
#### Model Training
- Use Jupyter to prepare a training and testing dataset and to train the machine-learning model
- Pick a machine learning model used for regression and forecasting
- Use our training data to fit the model
#### Model Evaluation
- Use the data and predicted values to evaluate the model
- Create statistical analysis to report the model performance
- Analyze the patterns that correlate with certain periods/times

