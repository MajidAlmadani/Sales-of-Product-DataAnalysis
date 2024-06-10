# Sales-of-Product-DataAnalysis
We focused on analyzing the product sales and to make predictions about future sales. The analysis involved several key tasks, each designed to systematically process the data and extract valuable insights. 

# Visualizing Relationships
Next, we created line plots for both the train and test datasets. These plots provided a clear visualization of the data trends over time, allowing us to observe any significant patterns or anomalies.
# Some line plots
# Product A
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/8b83cbcd-0a50-4788-8e44-a99b42cc63a6)
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/28e6808c-29b4-410b-a9a4-7655344d1f55)

# Product E
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/fef90617-cbe1-4581-baff-d4848b3e8728)
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/79ccc820-f095-41c2-8bf2-365cc8a065ac)


# Analyzing Seasonality and Trends
To further understand the data, we plotted the Auto-correlation Function (ACF) and Partial Auto-correlation Function (PACF), along with the variogram for each product. These plots helped us determine whether the data exhibited additive or multiplicative patterns, which was critical for selecting the appropriate forecasting models.

# Some ACF - PACF - Variogram Plots
# Product A
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/d6ff84c1-9df2-44bd-ba7c-b52c0ed29ace)
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/99a63384-118f-49b5-9b57-f629272dd7c0)

# Product E
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/cc324407-8520-48c4-9b5f-1dde310353da)
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/cc0d8b2e-be65-47d7-8c73-ee0729368856)


# Modeling and Forecasting
We then developed various forecasting models, including Exponential Smoothing, ARIMA, Support Vector Regression (SVR), Recurrent Neural Network (RNN), and Long Short-Term Memory (LSTM) models. Each model was trained and tested to predict future sales, and we compared their performances to identify the best one.

# Exponential Smoothing Models
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/1b562c79-4194-4aec-bc80-40b8224fea1d)

# ARIMA
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/44f46f88-a441-486f-94f3-be1f60438c3f)

# SVR
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/1ace5389-dc6a-4a9b-88a6-7e89f77cbd71)


# Model Comparison and Selection
The final step was to compare the prediction results from all models. We evaluated their accuracy using metrics like Mean Squared Error (MSE) and AIC. This comparison allowed us to select the model that provided the most accurate and reliable sales forecasts.

# Best Model for each product
![image](https://github.com/MajidAlmadani/Sales-of-Product-DataAnalysis/assets/125421977/0e89b6e0-c73e-48c3-9ddf-b42996582fcd)
