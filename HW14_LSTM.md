Evaluating the Performance of Each Model
(Note: The performance of each model was made using different notebook because their convenience. The notebooks lstm1 stock predictor fng, and the lstm5 stock predictor price are about fng and closing price models with a window of 10 and nodes or number of units of 10. The rest of notebooks are almost the same changing or the window or the nodes)

The evaluation should answer if FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

FNG indicator as predictor:
window size = 10
number units = 10
loss = 0.11232622

window size = 10
number units = 30
loss = 0.129012

window size = 5
number units = 10
loss = 0.1125916

window size = 5
number units = 30
loss = 0.1158

Closing Prices as predictor:
window = 10
number units = 10
loss = 0.05162761

window = 10
number units = 30
loss = 0.05548784

window = 5
number units = 10
loss = 0.04331346

window = 5
number units = 30
loss = 0.0496984

Which model has a lower loss?
    RNN LSTM Closing Price has a lower loss than FNG model, using same parameters for comparison. Making comparison between the clossing price, the model with a window 5 had the lower loss.

Which model tracks the actual values better over time?
    RNN LSTM Closing Price  tracks the actual values better over time. In order to ge a better track a model with 30 nodes were trying , but the loss increased and the plotting did not improve (see plotting)

Which window size works best for the model?
    RNN LSTM Closing Price with window size of 5 was the best.

The result of the evaluation was closing price data provides better signal for cryptocurrencies than the FNG indicator data. 
The closing price model using as window 5 and node of 10 was the best model for prediction.


