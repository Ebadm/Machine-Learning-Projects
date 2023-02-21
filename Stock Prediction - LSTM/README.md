#### Select any stock listed in Singapore stock exchange. Using Yahoo finance, download
#### the daily stock data (Open, High, Low, Close, Adj Close, Volume) from year 1 Jan
#### 2020 to 3 Jan 2022. Use data until 31 Dec 2020 for training and the remaining data for
#### testing. You must select the stock such that the data is available from 1 Jan 2020 to 3
#### Jan 2022. Use previous 30 days of stock information to predict the next day stock price.
#### Use the data in ‘High’ column to predict the price, i.e., the next day high price of the
#### stock. Design a LSTM network to do the predictions. You are required to use LSTM
#### with a cell state of at least 60 dimension and do at least 50 epochs of training. Rate the
#### performance of the LSTM classifier and provide necessary plots.