# Stock Price Prediction Using ARIMA and LSTM Models

Welcome to the **Stock Price Prediction** project! This repository demonstrates the use of **ARIMA (AutoRegressive Integrated Moving Average)** and **LSTM (Long Short-Term Memory)** models for predicting stock prices of popular companies. The goal is to compare the performance of these models using the **Root Mean Square Error (RMSE)** as a metric.

---

## Performance Overview

Below is a quick summary of the RMSE values for each company:

| **Company** | **ARIMA Model (RMSE)** | **LSTM Model (RMSE)** |
|-------------|-------------------------|------------------------|
| **Apple**   | 6.40                   | 4.82                  |
| **Tesla**   | 108.11                 | 66.40                 |
| **Google**  | 210.40                 | 115.66                |
| **Microsoft**| 7.26                  | 6.23                  |
| **Amazon**  | 113.18                 | 87.48                 |

---

## Company-Wise Analysis

### **Apple (AAPL)** 
- **ARIMA RMSE**: 6.40  
- **LSTM RMSE**: 4.82  
The **LSTM model** outperforms ARIMA with a significantly lower RMSE, showing its ability to capture trends in Apple's stock prices effectively.

---

### **Tesla (TSLA)** 
- **ARIMA RMSE**: 108.11  
- **LSTM RMSE**: 66.40  
Tesla's volatile stock is better modeled with LSTM, achieving a notable improvement in RMSE over ARIMA.

---

### **Google (GOOGL)** 
- **ARIMA RMSE**: 210.40  
- **LSTM RMSE**: 115.66  
For Google, the LSTM model shows significant performance gains, reducing RMSE by nearly 45%.

---

### **Microsoft (MSFT)** 
- **ARIMA RMSE**: 7.26  
- **LSTM RMSE**: 6.23  
Although both models perform well, LSTM delivers a slight edge over ARIMA for Microsoft.

---

### **Amazon (AMZN)** 
- **ARIMA RMSE**: 113.18  
- **LSTM RMSE**: 87.48  
The LSTM model demonstrates better accuracy in forecasting Amazon's stock prices, reducing RMSE substantially.

---

## Project Features

- **Data Collection**: Historical stock price data was sourced from Yahoo Finance.
- **Data Preprocessing**: Handled missing data, normalized values, and prepared data for modeling.
- **Model Implementation**:
  - **ARIMA**: A statistical approach for time series forecasting.
  - **LSTM**: A deep learning model well-suited for sequential data like time series.
- **Model Evaluation**: Used RMSE to measure prediction accuracy.
- **Visualization**: Displayed stock trends and prediction accuracy through graphs.
