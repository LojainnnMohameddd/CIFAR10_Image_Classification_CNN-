CIFAR-10 Image Classification with CNN
This project demonstrates an image classification model using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset. The model is built using TensorFlow and Keras, and it features several key techniques to optimize performance.

Features
Model Architecture: The CNN includes Conv2D, MaxPooling2D, BatchNormalization, and Dropout layers to effectively learn features and prevent overfitting.

Data Augmentation: An ImageDataGenerator is used to expand the training set and improve the model's ability to generalize.

Training Callbacks: The training process uses Early Stopping to halt training when validation accuracy plateaus, and a Learning Rate Reduction callback to help the model converge more efficiently.

