# Iris-Prediction-Model
This repository contains a neural network model built with PyTorch to classify iris flowers using Fisher's Iris dataset. The model has two hidden layers and predicts the iris species based on input features: sepal length, sepal width, petal length, and petal width. Future updates will include image processing capabilities for data extraction.

### Iris Prediction Model

My Iris Prediction Model leverages a neural network architecture to classify the variety of an iris flower based on data derived from images. This model is built upon the renowned Iris dataset, introduced by R.A. Fisher in his seminal 1936 paper, which has become a cornerstone in the field of pattern recognition and classification.

#### Model Architecture

The neural network consists of a simple yet effective architecture with the following features:

- **Input Layer**: Takes in four features representing the physical dimensions of the iris flower: sepal length, sepal width, petal length, and petal width.
- **Two Hidden Layers**: Each layer contains neurons that process the input features through weighted connections, enabling the network to learn complex patterns and relationships within the data.
  - **First Hidden Layer**: Comprises [specify the number] neurons with [activation function], capturing primary patterns.
  - **Second Hidden Layer**: Comprises [specify the number] neurons with [activation function], refining the patterns recognized by the first layer.
- **Output Layer**: Utilizes a softmax activation function to output probabilities corresponding to the three iris species: Iris-setosa, Iris-versicolor, and Iris-virginica.

#### Functionality

Currently, users can predict the variety of an iris flower by uploading the relevant data points. The model processes these inputs through the network layers, leveraging learned weights and biases to deliver a precise classification.

#### Future Enhancements

While the model presently requires users to input data points manually, I am working on integrating image processing capabilities. This forthcoming feature will allow users to upload images of iris flowers directly, with the model automatically extracting the necessary data points for classification.

#### Key Benefits

- **Accuracy**: The two-layer neural network structure is optimized to achieve high accuracy in classifying iris species.
- **Simplicity**: Despite its power, the model maintains simplicity, ensuring quick and efficient predictions.
- **Educational Value**: Based on Fisher's classic dataset, the model serves as an excellent educational tool for understanding neural network-based classification.

This model exemplifies the power of neural networks in pattern recognition and showcases the enduring relevance of Fisher's Iris dataset in modern machine learning applications. The addition of image processing capabilities will further enhance its usability and accuracy.
