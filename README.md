# Recurrent Neural Networks (RNN) - Deep Learning w/ Python, TensorFlow & Keras 

I am following the Sentdex tutorial on Recurrent Neural Networks - Deep Learning basics with Python, TensorFlow and Keras p.7

In this tutorial, we are learning on Recurrent Neural Network(RNN) which are super useful for testing a real-time datasets. However, for the sake of example, the data are imported for MNIST. 

The are only one jupyter notebook file in the repository. Will be updating soon in the future. 

# Long Short-Term Memory (LSTM) layer

I am using two LSTM layer for our model. Tensorflow is cool enough to allow CuDNNLSTM activated by running LSTM without the activation. Hence, in the code I didn't passing in activation function for the first and second layer of our RNN. 

The results are amazing! loss: 0.0825 - accuracy: 0.9774 - val_loss: 0.0611 - val_accuracy: 0.9818 on the third epochs. CuDNNLSTM is blazing fast too. 
