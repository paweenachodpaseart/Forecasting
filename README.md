# Forecasting
Forecasting the Number of Passengers Boarding United Airlines Flights🛫

### 📌 Project Overview  
This project studies the forecasting of the number of passengers boarding United Airlines flights using monthly data from 2004 to 2010 obtained from Kaggle. The analysis is conducted using two main techniques:

1.Holt-Winters Method (Exponential Smoothing Adjusted for Trend and Seasonal Variation)
The optimal model was selected with Alpha (α) = 0.8, Gamma (γ) = 0.1, Delta (δ) = 0.1.
The model achieved the lowest Mean Absolute Percentage Error (MAPE) of 2.2507%.
Passenger numbers were forecasted 12 months into the future.

2.Box-Jenkins (ARIMA Model)
The ARIMA(1,1,0)(1,0,0)₁₂ model was chosen.
Assumptions regarding independence, normality of distribution, and variance stationarity were verified.
The forecasting results were similar to those of the Holt-Winters method.

### 🎯 Objectives
1. To notify customers about relevant ads and promotions.
2. To recommend products based on customer interests.
3. To improve product and service efficiency.
4. To boost sales and enhance the customer experience.
5. To find ways to reduce the cart abandonment rate.

### 🛠️ Tool: MongoDB (NoSQL)
