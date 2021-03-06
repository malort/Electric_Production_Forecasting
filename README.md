# Electric_Production_Forecasting

This project is a univariate analysis of an electric production series. The objective is to predict the electric production given prior observations. 
Several models such as ARIMA, Prophet, Exponential Smoothing or Theta method have been used to measure its performance.

Requirements:

```pandas:``` Data analysis and manipulation tool.

```matplotlib:``` Visualization library.

```seaborn:``` Data visualization library based on matplotlib, it enhances the style of matplotlib plots.

```Numpy:``` Numerical analysis library.

```scikit-learn:``` Machine Learning library.

```pmdarima:``` Statistical library for time series analysis in Python.

```darts:``` Python library for easy manipulation and forecasting of time series.

```prophet:``` Prophet is a forecasting procedure implemented in R and Python.

```statsmodels:``` Python module that provides classes and functions for the estimation of different statistical models.


### FIRST PART: 
After some visualizations, the components of the series are analyzed and the stationarity checked. As the result of the previous analysis, 
the series is transformed into stationary.

### SECOND PART | Arima model and Prophet: 
An autoregressive integrated moving average (ARIMA) model is used to predict future points in time series data. In this project, the optimal order of the model is identified using the auto-Arima process (pmdarima library). 

![imagen](https://user-images.githubusercontent.com/20369543/159540003-025f5e2f-bdd7-4ad9-bdf0-86d9e36a09a3.png)





Prophet is a forecasting package in both R and Python that was developed by Facebook’s data science research team. 





![imagen](https://user-images.githubusercontent.com/20369543/159540206-f14bc623-6e1e-41b4-8b97-fa5aadec9984.png)





### THIRD PART | Darts models: 
Darts embeds most of the widely used time series forecasting methods, its primary goal is to simplify the whole time series machine learning experience. 
In this part, a single function is used to fit the data, predict future observations, evaluate the model and plot the results. 
Several models have been tested using this function.

![darts](https://user-images.githubusercontent.com/20369543/159538760-8d0f490b-9fa0-4316-b019-464fb9c96818.jpg)


