# Time-Series Forecasting using RNN
This project involves using Recurrent Neural Networks (RNN) to forecast household power consumption based on a time-series dataset. The dataset provides detailed measurements of various power consumption metrics within a household, allowing us to predict future consumption patterns.

## RNN Architecture
The RNN model used for this task consists of three LSTM layers followed by four fully connected layers.

#### Architecture Breakdown
- LSTM Layers:
-- First LSTM Layer: Input size, hidden size, and number of layers with bidirectional processing.
-- Second LSTM Layer: Same hidden size and number of layers, takes output of the first layer.
-- Third LSTM Layer: Hidden size of 32, same number of layers, bidirectional processing.
- Fully Connected Layers:
-- Four layers with decreasing hidden units (128, 64, 32, 1).
-- ReLU activation function and 0.25 dropout applied between layers.
-- Sigmoid activation function for the final output.

## Code

You can find the code for the entire project in the Time_Series_Forecasting_RNN.ipynb file.
## Detailed Report

A comprehensive report detailing the model architecture, training process, evaluation metrics, and performance graphs is available in `report.pdf`.

For questions or feedback, please [email](mailto:gayatriwalke@gmail.com).

