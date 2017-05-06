# Deep Learning Models for MNIST
Deep learning is very hot in many fields, although the computation process seems quite complex for non-professionals, fortunately many free platforms are available,   such as Tensorflow, MXNET, Pytorch. With those tools, it's convenient to focus on our models instead of writing codes to do back propagation calculation.

In order to demonstrate how to design deep learning models using Tensorflow, based on some reference of others' work, I created some toy examples including fundamental linear model, fully connected deep neural network, convolutional neural network, (bi)recurrent neural network and generative adversial network and etc. 

The dataset was MNIST, a popular dataset for beginners. In addition, methods to prevent against overfitting such as dropout, regularization were taken into consideration.

Generally, to leverage Tensorflow, we need four steps: 
- Define a graph including nodes of variables, computations
- Define optimizer(like stochastic gradient descending) and loss function(like cross entropy)
- Train the model with feeding batches of data samples to the model
- Validate and test the model with testing datasets

Including:
- Linear model
- Multi-layer deep neural network, fully connected
- Convolutional neural network
- Recurrent neural network, LSTM cell, single layer
- Recurrent neural network, LSTM cell, multi-layer with dropouts
- Bidirectional recurrent neural network, LSTM cell, it works pretty well.
- Generative adversarial network

Using variable name to wrap those variables.
