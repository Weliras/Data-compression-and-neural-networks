# Masters thesis - Data compression and neural networks
This work is aimed at demonstrating the use of deep learning in data compression. A number of experiments are conducted with artificial neural network models. The aim was to find the optimal model and architecture and also to demonstrate the use of deep learning in data compression.

The models were trained to predict the conditional probability of each byte in the input file using a softmax layer. The probability of each byte is predicted based on K bytes, where K is the experiments parameter and ranges from <0, 7>.

A number of models and architectures have been tried - DNN, RNN (GRU, LSTM) + attention mechanism.

The results are very nice.

Technologies used: python, Tensorflow, Keras, C/C++, Jupyter notebook, pandas, matplotlib, ...
