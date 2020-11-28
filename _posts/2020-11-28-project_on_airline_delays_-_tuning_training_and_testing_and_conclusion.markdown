---
layout: post
title:      "Project on Airline delays - Tuning, training and testing and conclusion"
date:       2020-11-28 07:02:59 +0000
permalink:  project_on_airline_delays_-_tuning_training_and_testing_and_conclusion
---


In this part I mostly trained, tested and tuned different models based on arrival delays for three major airlines: Delta Airlines, United and American Airlines. The limitation in the scope of airlines to be used was due to the fact that with a high number of airlines the amount of data was humongous, impossible to process by the memory of my desktop.

I selected three models for training and testing my data: DecisionRegressor, BaggingRegressor and RandomForestRegressor; the accuracy scores for the three models were as follow:
Decision Regressor: 0.54
Bagging Regressor: 0.75
Random Forest Regressor: 0.88

Out of the three models I tried, random forest has the best score; I fine-tuned this model and use it for my prediction model. 

With the random forest model using the data from three major airlines I was able to predict that  an airplane will be delayed with an error of about  0.08 minute.

In conclusion I can use my model to compare historical delay amount airline companies and be able to advise customer on the best airlines to take if you want to avoid Arrival delay. For future work, I may study the impact of model where the departure delay is drop from my data. Given the fact that more arrival delays are caused by departure delays, the flights with arrival delays without departure delays will be considered as outliers and my models will be able to predict the arrival delays. 

