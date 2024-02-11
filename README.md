<h1 align="center">Backtesing Logs</h1>
<h5 align="center">"Stock markert Prediction based on deep learning and blockchain"</h5>
https://cdni.iconscout.com/illustration/premium/thumb/man-trading-stocks-7113747-5783456.png?f=webp
<hr>

<img align="right" height="300px" src="!(https://github.com/TakudzwaChoto/Enhancement-of-backtesting-logs-based-on-Blockchain-and-Deep-learning/assets/56199912/0bfb143d-fd12-4582-9038-528cb92fc582)
">

# Project Overview

The project aims to provide stock price predictions for a given ticker symbol using historical stock data. The web application allows users to input a ticker symbol, and it retrieves the corresponding stock data using the Yahoo Finance API. The application then utilizes two models to predict future stock prices: a traditional machine learning model and a bi-directional LSTM model. The predicted prices are displayed on a web page along with historical price charts and other stock information.

# Web Application

The Flask web application provides a user interface for interacting with the stock prediction models. It uses HTML templates to render the web pages and accepts user inputs for the ticker symbol. It retrieves stock data using the Yahoo Finance API and displays the historical price chart, including moving averages. It also displays the predicted prices from both models, along with other stock information such as the today's high, close, and open values. The application provides additional pages for FAQs, contact information, about section, user registration, and news. It also includes a global chat feature and a login page. Overall, the project combines traditional machine learning techniques with deep learning (LSTM) to predict stock prices. The Flask web application serves as a user-friendly interface to interact with the models and view the predictions, historical data, and other stock-related information.

<img align="left" height="290px" src="https://github.com/TakudzwaChoto/Enhancement-of-backtesting-logs-based-on-Blockchain-and-Deep-learning/assets/56199912/482a2d07-cac3-4672-b78d-b62d55d6780a
">

# Machine Learning Model

The traditional machine learning model used in the project is a regression model trained on historical stock price data. The model is loaded and the data is preprocessesd by scaling it using MinMaxScaler and splitting it into training and testing sets. The model is trained on the training set and used to predict prices on the testing set. The predicted prices are then inverse-transformed using the scaler to obtain the actual predicted values.

# Bi-directional LSTM Model

The bi-directional LSTM model is implemented using the Keras library.The Data_fetch_transform function is responsible for fetching the stock data, preprocessing it, and splitting it into training and testing sets. The model is trained on the training set using the LSTM architecture with a time step of 100. The training and testing sets are reshaped to fit the model's input shape. The model is used to predict prices on the testing set, which are then inverse-transformed using the scaler. Additionally, the code includes an evaluate_predictions function that calculates the difference and ratio between the predicted and actual prices and identifies outliers based on a given threshold. The model also predicts the next day's closing price.

<hr>

# Backtesting Logs Features

_Precise Predictions:_ Leverage the power of artificial intelligence to make data-backed investment decisions confidently.

_Real-time Insights:_ Access real-time market data, customizable charts, and personalized alerts for up-to-the-minute information.

_Comprehensive Analysis:_ Gain in-depth insights into market trends, economic indicators, and news that impact investment opportunities. Each indicator and factor is explained in detail, providing educational value.

_Collaborative Community:_ Connect with a vibrant community of like-minded investors to share insights, discuss strategies, and enhance your financial knowledge.

_Blockchain-Powered Accuracy:_ Utilizing blockchain technology, we create immutable logs of predicted data and actual outcomes, ensuring untampered accuracy verification.

_User-Friendly Interface:_ Our intuitive platform ensures seamless navigation and ease of use for investors of all levels.

_Research and Learning Resources:_ Dive into our comprehensive FAQ documentation to learn more about various indicators, factors, and strategies. It serves as a valuable resource for new investors to expand their knowledge.

Author:
Takudzwa Choto








