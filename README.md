# stock-predictor

This dashboard app aims to predict the stock prices over the next few days. It uses a Recurrent Neural Network with 5 layers of Gated Recurrent Units and one dense layer for prediction. The RNN is trained on a dataset that contains the stock prices of Kotak Mahindra Bank. This dataset can be easily obtained from Yahoo Finance for a specific range of dates. The results are displayed in the form of a candle stick plot. 

The main challenge is that there is a lot of noise in the data on which the RNN is trained on. So, the predicted prices generally don't match the actual ones. 

Do check out the dashboard app at https://future-stock-predictor.herokuapp.com/. You need to drag the left cursor in the range slider towards the right to view the predictions.

<h3> Packages specific to the app that need to be installed</h3>
1.Keras 
2.Scikit Learn
3.Plotly
4.Dash
5.Dash Bootstrap Components
  
<h3>Files in this repository</h3>
stock_market_train_2.py - For training the model 
stock_market_test_2.py - For getting the predictions
dashboard_stock_market.py - For building the dashboard



