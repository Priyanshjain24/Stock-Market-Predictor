# Stock Market Predictor
This is a self project done by me on Machine Learning.
The motive of this project is to create a Stock Market Price Prediction using Machine Learning.
This github repo has 4 files:

We will be working on the Google Stock Prices Dataset (taken from the SOC project on "Stock Market Prediction using ARIMA Model").

In the first file (Basic_Tasks), we analyse the dataset and the statistics of ecah coloumn. We also make sure that no null enteries are present in our dataset and if there are, we assign the average of that entire coloumn to that particlaur entry of that cell.

The second file is only about EDA (Exploratory Data Analysis). We plot the values of different variables in coloumns using matplotlib to try to get some information and insights from the plots. This helps us in extracting some key features that our model should also obey to check the correctness of our model visually.

From the third file (Regression), we start with building our machine laerning models. We start with amongst the most basic machine learning algorithms, linear regression. We prepare our dataset to so that it can be fed into the linear regression model. We plot the predicted and actual values after training the model. The plot shows very clearly that linear regression has a very low accuracy and is not the best model for this dataset.

We then to the fourth file (LSTM), which has our deep learning model. We use the LSTM (Long short-term memory) deep learning neural netowrk for this. We prepare our dataset, feed them into the model and plot the predicted and actual stock prices with time. We also plot the loss function v/s epochs. We observe that this model is way better than linear regression and the predicted outcomes are quite close to actual prices.

Lastly in the fourth file (ARIMA), we test the ARIMA model. We proceed as before and find out that that the best model is LSTM amongst all the 3 models we tried.
