### IBM_stock_prediction
The task aimed to perform a short-term univariate stock price prediction task for IBM. The time series data was univariate. We compared three architectures of recurrent neural networks, Vanilla RNN, LSTM and GRU.


### Data
Data can be seen in [IBM.csv](https://github.com/guolipin/IBM_stock_prediction/blob/main/IBM.csv). Latest version can be gotten from [Yahoo Finance](https://au.finance.yahoo.com/).

### Achievement
GRU had the best performance with 0. 35% testing error rate. Compared to RNN, GRU can avoid gradient vanishing problem. Compared to LSTM, GRU performed better in long term memory. For more details, please refer to [report](https://github.com/guolipin/IBM_stock_prediction/blob/main/IBM_stock_prediction.pdf).

