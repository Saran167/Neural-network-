# Neural-network-
This project demonstrates how to train a neural network on the Iris dataset using TensorFlow and Keras. The Iris dataset contains 150 samples of iris flowers with 4 features: sepal length, sepal width, petal length, and petal width. The task is to classify these samples into three different species: Setosa, Versicolor, and Virginica.
Procedure
Dataset:
The Iris dataset consists of 150 samples, each with 4 features:

Sepal Length Sepal Width Petal Length Petal Width There are 3 target classes (species):

Setosa Versicolor Virginica

Preprocessing:
One-Hot Encoding: The target labels are one-hot encoded to be compatible with the softmax activation in the output layer.

Feature Scaling: The features are standardized (zero mean and unit variance) to speed up the training process and improve convergence.

Model:
A simple feedforward neural network is constructed with two hidden layers, each using the ReLU activation function.

The output layer employs the softmax activation function to perform multi-class classification.

Training:
The model is trained using the Adam optimizer and categorical crossentropy as the loss function.

Training is performed for 50 epochs with a batch size of 8, and a validation split of 20% is used to monitor the model's performance during training.
