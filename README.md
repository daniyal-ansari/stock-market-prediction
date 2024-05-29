# stock-market-prediction
predicting multi-step ahead with rnn structures and evaluating which structure with how many sequence lengths is the best.
for this, we first visualize our data and then normalize it on train data. after that, we build models with simple rnn, GRU, and LSTM to define which model performs better
after finding GRU models have the best performances on the validation set and we choose to proceed with GRU and after that finding the best sequence length with evaluating models on validation set
after that, we visualized our original data and predicted data, which are for one step ahead horizon and 20 step ahead horizon, and at last, we evaluated our model on test data to have a realistic error prediction for
developing it in real situations.
