# Tesla Stock Price Prediction using SimpleRNN and LSTM

## Developed By

**Dharminder Singh Virk**


---

## Project Overview

This project focuses on predicting Tesla (TSLA) stock closing prices using Deep Learning models such as **SimpleRNN** and **LSTM (Long Short-Term Memory)**.

Historical Tesla stock market data was analyzed, preprocessed, and transformed into time-series sequences. Both models were trained and evaluated using Mean Squared Error (MSE). Hyperparameter tuning was performed using Keras Tuner to improve model performance.

A Streamlit web application was also developed to visualize stock trends and generate future stock price predictions.

---

## Problem Statement

Stock prices are highly dynamic and influenced by various market factors. Traditional statistical methods often struggle to capture complex sequential patterns in stock market data.

The objective of this project is to leverage Deep Learning techniques to forecast Tesla stock prices using historical market data and compare the performance of SimpleRNN and LSTM models.

---

## Project Objectives

* Analyze Tesla historical stock market data
* Perform data preprocessing and feature scaling
* Build a SimpleRNN model
* Build an LSTM model
* Compare model performance
* Optimize model parameters using Keras Tuner
* Predict future stock prices
* Develop an interactive Streamlit application

---

## Dataset Information

### Dataset

Tesla Stock Market Dataset (TSLA)

### Features

| Feature   | Description             |
| --------- | ----------------------- |
| Date      | Trading Date            |
| Open      | Opening Price           |
| High      | Highest Price           |
| Low       | Lowest Price            |
| Close     | Closing Price           |
| Adj Close | Adjusted Closing Price  |
| Volume    | Number of Shares Traded |

### Target Variable

* Close Price

### Total Records

* 2416 Records

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Data Scaling using MinMaxScaler
6. Time Series Sequence Creation
7. Train-Test Split
8. SimpleRNN Model Training
9. LSTM Model Training
10. Model Evaluation
11. Hyperparameter Tuning
12. Future Price Prediction
13. Streamlit Application Development

---

## Technologies Used

### Programming Language

* Python

### Data Analysis Libraries

* Pandas
* NumPy

### Visualization Libraries

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn

### Deep Learning

* TensorFlow
* Keras
* SimpleRNN
* LSTM

### Hyperparameter Tuning

* Keras Tuner

### Deployment

* Streamlit
* Pyngrok
* Ngrok

### Development Environment

* Google Colab

---

## Model Performance

Two Deep Learning models were implemented:

### SimpleRNN

* Captures short-term sequential dependencies
* Faster training

### LSTM

* Captures long-term dependencies
* Better prediction performance
* Lower prediction error

The LSTM model outperformed the SimpleRNN model based on Mean Squared Error (MSE).

---

## Future Improvements

* Add Open, High, Low, and Volume features
* Integrate technical indicators such as RSI, MACD, and Moving Averages
* Implement GRU and Bidirectional LSTM models
* Explore Transformer-based architectures
* Integrate real-time stock market APIs
* Extend forecasting horizon to 30, 60, and 90 days
* Add sentiment analysis using financial news and social media
* Deploy the application on cloud platforms

---

## Business Use Cases

* Stock Market Forecasting
* Investment Decision Support
* Financial Analytics
* Risk Management
* Portfolio Planning
* Algorithmic Trading Systems
* Financial Advisory Services

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Time Series Forecasting
* Deep Learning
* Hyperparameter Tuning
* Model Evaluation
* Data Visualization
* Streamlit Deployment

---

## Project Structure

```bash
├── TSLA.csv
├── Tesla_Stock_Prediction.ipynb
├── app.py
├── lstm_model.h5
├── tesla_tuning/
├── README.md
```

---

## Conclusion

This project successfully demonstrates the application of Deep Learning techniques for stock price forecasting. The LSTM model achieved better performance than the SimpleRNN model by effectively capturing long-term dependencies in Tesla stock price data.

The project provides a strong foundation for future enhancements such as real-time prediction, advanced forecasting models, and cloud deployment.

