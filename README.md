# Long Short-Term Memory (LSTM) versus Gated Recurrent Unit (GRU) Neural Networks 

---

### NOTE: 

The following .ipynb file can be loaded into a Google Colaboratory (Colab) environment. 

https://research.google.com/colaboratory/

Once loaded, run the cells sequentially from top to bottom.

Alternatively, click the .ipynb file _(loading may take ~20-30 seconds)_ then click the 'Open in Colab' button.

![image](https://user-images.githubusercontent.com/17456203/170380038-98cc73e6-6472-4b7a-b9b8-1deed347396c.png)

---

The following code implementation compares LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural networks to predict the future closing price of a publically traded (NYSE) company based multivariate inputs (Open, High, and Low prices). 

All models are assessed in terms of the Root Mean Squared Error (RMSE) scores for a baseline model and optimized model (differing in terms of epochs and hidden neurons). 

After further optimization, the following implementation could theoretically be utilized for financial forecasting applications.
