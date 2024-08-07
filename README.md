This projects contains notebooks that provides a comprehensive introduction to various deep learning techniques,
from basic neural networks to advanced convolutional neural networks (CNNs), and their applications in real-world problems

The notebooks are created as assignments while I am taking a course on Coursera
* [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning](https://www.coursera.org/learn/introduction-tensorflow/home/welcome)

Included Notebooks:
- SLNN-House-Prices-Prediction
   - This model predicts house prices based on the number of bedrooms using linear regression
- Neural-Network-Image-Classification
- Speeding-Neural-Network-With-Convolution
- CNN-Happy-Sad-Image-Classification

Model Architecture used in these Notebooks:
- SLNN-House-Prices-Prediction
Model Type: Sequential
Layers:
  Dense Layer:
  Units: 1
Input Shape: [1] (represents the number of bedrooms)
Compilation:
  Optimizer: Stochastic Gradient Descent (SGD)
  Loss Function: Mean Squared Error (MSE)
Training:
Epochs: 1000
