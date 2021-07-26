# LSTM_Bitcoin_Prediction
This notebook performs predicts the Bitcoin price using the "CryptoCurrency TimeSeries 2020" dataset using an RNN based on LSTM.
<br/>
Link to the Kaggle Post: https://www.kaggle.com/pouyashiri/bitcoin-price-prediction-using-lstm/edit
<br/>
Link to the Kaggle Dataset used: https://www.kaggle.com/roopahegde/cryptocurrency-timeseries-2020
<br/>

Steps:
<br/>
* Extracting "Mid" values using "Low" and "High" values and dividing the dataset into 95% training and 5% testing splits.
* Creating the input/output data for training and testing splits (sequencing), and scaling the training set region-by-region.
* Using exponential smoothing to remove noise from the training data.
* Training, and predicting the Bitcoin value using a 4 layer LSTM network with dropout. 


# Requirements
tensorflow, keras, scikit-learn, pandas, matplotlib, seaborn, numpy, category_encoder
