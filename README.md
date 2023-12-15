Topic: Prediction of Stock Market Closing Prices using Recurrent Neural Networks with Long Short Term Memory

The following is the description and the explanation of the project
1. I used three different stock market datasets from Kaggle for this project. I started off by employing various plots using matplotlib and seaborn to analyse and understand the relation between the features and the target variable.
2. Further, I performed feature engineering to make sure that the dataset is optimal for the custom LSTM model.
3. I standardized each of the datasets using the MinMaxScaler() to make sure that all the features are on the same scale.
4. To start with the implementation of RNN with LSTM, firstly, I initalized the LSTM class using Xavier Initialization to mitigate the vanishing gradient problem. The sigmoid and tanh activation function were also implemented for non-linearities.
5. I executed both the forward proagation and backward propagation methods of the LSTM class. The weights were updated in the backward propagation using Gradient Descent.
6. The model was evaluated using the RMSE score and the R2 score.
7. I tested the model with various hyperparameter settings such as the learning rate, neuron count, and epoch count, to optimize the model performance. 
8. I conducted my evaluation and an in-depth analysis of the LSTM model on the effect of different hyperparamter settings on the RMSE score and the R2 score.

The following are the steps to run the code:
1. Login into Databricks Community Edition.
2. Create a Compute (cluster) and wait for it to start.
3. Import the python notebook and attach the cluster.
4. Run the notebook and wait for the outputs.
