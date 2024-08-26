# Convolutional Neural Network for Breast Cancer Detection
This project implements a Convolutional Neural Network (CNN) to classify breast histopathology images as cancerous or non-cancerous. The dataset used is highly relevant for medical imaging and cancer research, providing a crucial resource for developing automated cancer detection algorithms.

Overview

    Dataset: Breast histopathology images labeled as 0 (cancerous) and 1 (non-cancerous).
    Model Architecture: CNN with multiple convolutional layers, batch normalization, max-pooling, and dense layers. The model uses ReLU activation in hidden layers and Sigmoid in the output layer.
    Training: The model was trained using Stochastic Gradient Descent (SGD) with Adam optimizer over 20 epochs. Various setups were tested, including balancing the dataset and adjusting the number of epochs.

Results

    Accuracy: The original setup achieved 89% accuracy. Balancing the dataset improved performance, as the model had equal opportunities to learn from both classes.
    Future Work: Further improvements could be made by augmenting the dataset with rotated or flipped images to reduce bias and enhance model accuracy.
