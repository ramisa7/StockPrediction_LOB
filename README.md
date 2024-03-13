# Stock Prediction Using LOB(Limit Order Book) Data 

### Team Memebrs: 
1. Ramisa Tahsin Rahman
2. Ruby Sapkota

## Abstact: 


### Minimum Viable Product (MVP):

This project focuses on building a model to predict mid-price forecasting using limit order book data from the stock market. 
We use the normalized version of the LOB data from five companies over a span of 10 days to develop a model for making informed short-term trading decisions in the dynamic stock market environment. By analyzing short-term trends, we aim to forecast whether stock prices will increase, decrease, or remain unchanged over the next few milliseconds, seconds, minutes to days, which is a short-term stock prediction.

Our baseline model employs a simple logistic regression approach. We'll use this as a reference point to compare the performance of more advanced models.
The proposed model architecture involves using convolutional filters to extract intricate patterns from the LOB data,  which describes short-term trends and dynamics. These extracted patterns will be fed into Long Short-Term Memory (LSTM) modules to capture temporal dependencies, enabling the model to learn and remember market behaviors over time. 
As this is a classification problem, we'll evaluate the model's performance using standard classification metrics like accuracy, precision, recall, F1-score, and area under the ROC curve (AUC).

### Initial Setup of our Project: 
1. #### Download the data from https://etsin.fairdata.fi/dataset/73eb48d7-4dbc-4a10-a52a-da745b47a649/data
2. Setup the directory path in the ipynb file.


### Stretch Goal:

As a stretch goal, we plan to incorporate historical data combined with our LOB data. By integrating features extracted from the LOB dataset and our historical dataset to train our model, we aim to predict the long term trends in the stock market using our model. This type of prediction would be considered as a medium-term timeframe, capturing trends over a period that ranges from days to weeks. This approach ensures we're not solely focusing on immediate short-term movements (minutes or hours) or long-term predictions spanning months or years.

If we proceed with our stretch goal, our work would look like:

Combination of 2 things: 
| Short Term  | Long Term |
| ------------- | ------------- |
| Dataset: Normalized version of F-1 2010, Convolutional Filter (CNN) | Dataset: Historical Stock Price( Yahoo API)   | 

#### LSTM, Baseline: Linear Regression, Evaluation Metric: RMSE afterwards
