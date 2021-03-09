# Image Classification using Pytorch and Convolutional Neural Networks

## Table of Contents: 
* Overview of Project

* Data Description 

* Libraries used

* Structure of the Approach

* Conclusion



## Approach:

* Extract Sentiment Scores from given newspaper headlines data, with the help of nltk's SentimentIntensityAnalyzer

* For this problem statement, I took inspiration from this [awesome paper](https://www.researchgate.net/publication/306925671_Deep_learning_for_stock_prediction_using_numerical_and_textual_information) and decided to carry out Multivariate Time Series Forecasting using Keras' LSTM.

* I used LSTM (Long Short-Term Memory), to model the temporal effects of past events(both Textual, i.e the sentiment scores and Historical stock data) on opening prices

* Achieved Training loss: 0.0479 and Validation loss: 0.0254

* Achieved RMSE on the Test data : 475.102


## Data used to analyze and predict: 
* Historical stock prices(SENSEX (S&P BSE SENSEX)) from https://finance.yahoo.com/

* Textual (News) data from https://bit.ly/36fFPI6

## References:
[Deep learning for stock prediction using numerical and textual information](https://www.researchgate.net/publication/306925671_Deep_learning_for_stock_prediction_using_numerical_and_textual_information)- Ryo Akita, Akira Yoshihara, Takashi Matsubara, Kuniaki Uehara
