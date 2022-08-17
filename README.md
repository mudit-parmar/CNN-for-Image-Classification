# CNN-for-Image-Classification


Using your tensorflow and keras library, train a small convolutional network (CNN) to classify images from the CIFAR10 dataset


Using the API for loading the dataset will readily divide it into training and testing sets. Randomly sample 20% of the training set and use that as your new training set for the purposes of this problem. Use the test set for validation. Implement the following in one .ipynb with all the output shown (already run).



- MLP: Build a multi-layer perceptron with the following layers:

• Fully connected layer with 512 units and a sigmoid activation function

• Fully connected layer with 512 units and a sigmoid activation function

• Output layer with the suitable activation function and number of neurons for the classification task



2- CNN1: Build a Convolutional neural network with the following architecture:

• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function

• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function

• Fully connected (Dense) layer with 512 units and a sigmoid activation function

• Fully connected layer with 512 units and a sigmoid activation function

• Output layer with the suitable activation function and number of neurons for the classification task



3- CNN2: Build a Convolutional Neural network with the following architecture:

• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function

• 2x2 Max pooling layer

• 2D Convolutional layer with 64 filters (size of 3x3) and ReLU activation function

• 2x2 Max pooling layer

• Fully connected layer with 512 units and a sigmoid activation function

• Dropout layer with 0.2 dropout rate

• Fully connected layer with 512 units and a sigmoid activation function

• Dropout layer with 0.2 dropout rate

• Output layer with the suitable activation function and number of neurons for the classification task

Use a batch size of 32, utilize Adam as the optimizer and choose an appropriate loss function while
monitoring the accuracy in both networks. Train each network for 5 epochs.
