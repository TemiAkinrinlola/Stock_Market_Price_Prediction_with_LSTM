# Stock_Market_Price_Prediction_with_LSTM
Using LSTM to predict stock market prices.
### Motivation
Since its inception, stock markets have served many purposes, the most being to provide companies with a source to raise capital for investment and expansion ,the most important being to provide companies with a source to raise capital for investment and expansion. Recently, much effort has gone into the study of stock markets and how prices vary with time. This is because the stock markets have had a significant impact on the personal wealth of individuals and the wider economy at large. Successful prediction of a stock’s future price could yield significant profit.This project evaluates the performance of the LSTM model in the prediction of stock prices.

An LSTM (Long-Term-Short-Term) network is a type of recurrent neural network (RNN) that can learn long-term dependencies between time steps of sequence data.The core components of an LSTM network are a sequence input layer and an LSTM layer. A sequence input layer inputs sequence or time series data into the network. An LSTM layer learns long-term dependencies between time steps of sequence data.This diagram illustrates the architecture of a simple LSTM network for regression. The network starts with a sequence input layer followed by an LSTM layer. The network ends with a fully connected layer and a regression output layer.

![image](https://user-images.githubusercontent.com/67794705/89719928-27ef4b80-d9c5-11ea-8299-56093bbc923a.png)


To create an LSTM network for sequence-to-one regression, create a layer array containing a sequence input layer, an LSTM layer, a fully connected layer, and a regression output layer.Set the size of the sequence input layer to the number of features of the input data. Set the size of the fully connected layer to the number of responses. You do not need to specify the sequence length.For the LSTM layer, specify the number of hidden units and the output mode.

### Dataset
For this analysis ,we obtained freely available daily stock price data from Yahoo Finance.

### Result/Conclusion
While LSTM is well noted for its high performance in time series forecasting.Its performance has alot to do with the particular type of data being analysed.Stock prices are often cited as the quintessial example of a naturally occuring random walk.

### References
-Practical Time Series Analysis by Aileen Nielsen

_https://uk.mathworks.com/help/deeplearning/ug/long-short-term-memory-networks.html
