# Multi_Layered_NeuralNet
This program uses the Keras library to build a multi-layer neural network for image classification. The network takes 28x28 pixel grayscale images of fashion items
and predicts the type of item based on 10 different classes. The model is trained on 60,000 iamges and tested on 10,000 images. The model is compiled using the adam 
optimizer, the sparse_categorical_crossentropy loss function, and the accuracy metric. Finally, the model is trained for 10 epochs and evaluated on the test data to assess
its performance.

The required dependencies are TensorFlow and Keras:

pip install tensorflow keras
