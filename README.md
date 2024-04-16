# Autoregressive and Moving Average Time Series Model


## Overview
In this project, I delved into the world of time series analysis, focusing specifically on forecasting sensor data. Sensor data plays a crucial role in various fields, including IoT, environmental monitoring, manufacturing, and more. Accurately predicting future sensor readings is essential for proactive decision-making and optimizing system performance.

I began by gaining a solid understanding of time series analysis and its significance in uncovering patterns and trends in temporal data. I explored different types of time series, including continuous and discrete, and delve into the components that make up a time series, such as trend, seasonality, and irregularity.

To ensure reliable analysis, I familiarised myself with the concept of stationarity and learn how to test for it using techniques like the Augmented Dickey-Fuller (ADF) and Kwiatkowski-Phillips-Schmidt-Shin (KPSS) tests.

Additionally, I utilized autocorrelation and partial autocorrelation functions (ACF and PACF) to identify dependencies and correlations in the sensor data.
Building upon this foundation, I developed and apply moving average (MA) and autoregressive (AR) models specifically tailored for forecasting sensor data. These models will enable us to make accurate predictions and anticipate future readings based on historical patterns.



## Aim
The aim of this project is to provide beginners with a comprehensive introduction to time series analysis and forecasting, specifically focused on sensor data. By exploring basic concepts, developing MA and autoregressive models, and applying them to sensor data, participants will gain practical skills in analyzing and predicting future readings, enabling informed decision-making and optimization in various domains.



## Data Description 
The dataset used in this project consists of IoT sensor data from a chiller. It contains the following columns:
 


Time: This column represents the timestamp at which the sensor reading was taken. It provides the temporal information for each data point.

 


IOT_Sensor_Reading: This column represents the reading obtained from the primary sensor at the corresponding timestamp. It captures the specific measurement recorded by the sensor.

 


Error_Present: This column indicates whether an error was present while taking the sensor reading. It is a binary variable that can have a value of 1 if an error is present, or 0 if no error is detected.

 


Sensor 2: This column represents the reading obtained from a subordinate sensor at the same timestamp. It provides an additional measurement taken by a different sensor, potentially capturing complementary information.

 


Sensor_Value: This column represents the final value to be predicted. It may be derived from the primary sensor reading, considering factors such as error correction, calibration, or additional computations.




## Tech Stack

Language: Python


Libraries:   pandas, numpy, matplotlib, scipy.stats, statsmodels, seaborn




## Approach

* Read the data.


* Preprocess the data.


* Perform Exploratory Data Analysis (EDA).


* Check for stationarity in the data.


* Analyze ACF and PACF plots.


* Build the following models:



      * Moving average (MA).



      * First order autoregressive (AR).



      * Second/general order autoregressive (AR).



      * Third order autoregressive (AR).



      * Fourth order autoregressive (AR).




## Evaluate the models' performance.
