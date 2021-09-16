# Stock-predection
Stock Prediction using machine learning
## Abstract
Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit. The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not based on newly revealed information thus are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to gain future price. With the advent of the digital computer, stock market prediction has since moved into the technological realm. The most prominent technique involves the use of artificial neural networks. ANNs can be thought of as mathematical function approximators. The most common form of ANN in use for stock market prediction is the feed forward network utilizing the backward propagation of errors algorithm to update the network weights. These networks are commonly referred to as Backpropagation networks. Also in recent year there is a significant improvement in SVM (Support vector machine Algorithm) implementation for stock prediction. Another form of ANN that is more appropriate for stock prediction is the time recurrent neural network (RNN) or time delay neural network (TDNN). One of the modified version of RNN is LSTM which memorize history data for prediction. Keeping this details in mind in this project I tried to predict stock trend. Also to the result includes conclusion for what algorithm performs well compare to the other two.
## Background
Previously SVM and Backpropagation were used for many classification problem and there were many instances where reasonable accuracy was achieved. Keeping that in mind our given problem statement was addressed to achieve as much accuracy as possible with tweaking algorithm. LSTM was used for many time series problems and the same approach is used to predict trend for stock by memorizing history data.

## Description
Problem statement was to predict increase or decrease in stock price for next day. I addressed this as classification problem. There are many classification algorithms in neural network. Our main goal was to compare performance of SVM, LSTM and Backpropagation algorithm. Once I got reasonable accuracy I try to compare their results.
## Approach
Our approach to for this project consist of major steps:

1. Dataset creation
2. Implementation of algorithm
3. Comparison of result and analysis
## Conclusion:

In this project, I have demonstrated a machine learning approach to predict stock market trend using different neural networks. Result shows how I can use history data to predict stock movement with reasonable accuracy. Also, with T test result analysis I can conclude that LSTM performs better compare to Backpropagation and SVM. For this implementation, I would like to conclude that if I incorporate all the factors that affect stock performance and feed them to neural network with proper data preprocessing and filtering, after training the network I will be able to have a model which can predict stock momentum very accurately and this can result into better stock forecasting and profit for financial firms.
