# flower-classification
This project implements a Convolutional Neural Network (CNN) to classify images of flowers into five categories: daisy, dandelion, rose, sunflower, and tulip. Built using TensorFlow and Keras, the model is trained on a custom image dataset mounted via Google Colab.

_Project Highlights_
1. Custom dataset containing 3,555 training images and 264 test images across 5 flower categories
2. Data augmentation applied using Keras ImageDataGenerator to improve generalization
3. Sequential CNN architecture with dropout regularization to reduce overfitting
4. Achieved 83.5% training accuracy over 30 epochs
5. Model tested on new flower images for classification

_Technologies Used_
1. Python
2. TensorFlow
3. Keras
4. NumPy
5. Google Colab

Model Architecture
1. Two convolutional layers with 64 filters and 3x3 kernels
2. MaxPooling layers for downsampling
3. Dropout layer for regularization
4. Dense layer with 128 units and ReLU activation
5. Output layer with softmax activation for five-class classification
6. Loss function: categorical_crossentropy
7. Optimizer: RMSProp

Known Issues
1. Occasional errors related to reading the pickle file (currently being addressed)
2. Validation loss increases over time despite rising accuracy, indicating possible overfitting

