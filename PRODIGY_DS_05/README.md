**Project 05: Handwritten Digit Recognition using Artificial Neural Networks (ANN)**

**Project Overview**
This project focuses on the implementation of a deep learning model to classify handwritten digits from the MNIST dataset. By leveraging TensorFlow and Keras, I developed an Artificial Neural Network (ANN) capable of identifying numerical patterns in unstructured image data with high precision.

**Technical Objectives**
Neural Architecture Design: Engineered a sequential model consisting of a Flatten layer for data transformation, a high-density Hidden layer with ReLU activation, and a Softmax output layer for 10-class probability distribution.

Data Preprocessing: Scaled raw pixel values (0-255) to a normalized range (0-1) to ensure stable gradient descent and faster model convergence.

Model Regularization: Integrated Dropout layers to prevent overfitting by randomly deactivating neurons during training, ensuring the model generalizes well to new, unseen digits.

Optimization & Training: Utilized the Adam optimizer and Sparse Categorical Crossentropy loss function to achieve a final validation accuracy of over 97%.

**Tools & Libraries Used**
TensorFlow / Keras: Primary framework for building and training the neural network.

NumPy: For numerical array manipulation and data handling.

Matplotlib: For visualizing the model's predictions and performance metrics.

**Key Results**
Successfully mapped 28x28 grayscale images to their corresponding numerical values.

The model demonstrated robust pattern recognition, correctly identifying 5/5 samples in the final test visualization with high confidence.
