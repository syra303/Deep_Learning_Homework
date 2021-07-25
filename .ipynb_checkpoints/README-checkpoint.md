# Deep Learning Homework

After plotting the real vs predicted values on a line chart, it is evident that both models performed poorly just by looking at how the predicted lines barely even fit the shape of the real value lines. 

![lstm_closing](LSTM_Closing.jpg)
![lstm_fng](LSTM_FNG.jpg)

Despite both LSTM models seeing some success by reducing the loss error when running model.fit on our trainding data, that loss was not significant enough for the models to predict values remotely close to the actual when it came to predicting the test set. 

In conclusion, it did not matter what values went in as our target value (y) as both produced similar results. The issue lies in either how I configured my LSTM model, or that the LSTM model may not be the best model to use when predicting this type of data. 


