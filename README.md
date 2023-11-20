# MNIST
MNIST Image Classification with PyTorch

Overview
The script implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. It includes the following key components:

Loading necessary PyTorch libraries and datasets.
Downloading and preparing the MNIST dataset.
Defining the CNN architecture.
Training and testing the model.
Prerequisites
Python 3.x
PyTorch
torchvision
Dataset
The script uses the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits (0-9).

Model Architecture
The CNN, defined as Net, includes two convolutional layers, dropout layers, batch normalization, and fully connected layers.

Steps to Run
Install Libraries: Ensure all required libraries are installed.
Load Dataset: The MNIST dataset is downloaded and loaded using torchvision.
Define the CNN: The Net class defines the CNN architecture.
Train the Model: The model is trained over 10 epochs.
Test the Model: The trained model's accuracy is evaluated on the test dataset.
Code Structure
import statements: Importing necessary libraries.
Dataset preparation: Downloading and loading the MNIST dataset.
Net class: Defines the CNN architecture.
Training loop: Includes loss computation and backpropagation.
Testing loop: Evaluates the model's performance.
Output
![image](https://github.com/BnbKe/MNIST/assets/112658393/505b991c-dfa6-4390-8e63-566501b7fede)

After training, the model's accuracy on the test dataset is printed.

![image](https://github.com/BnbKe/MNIST/assets/112658393/8798ebc8-8d1f-4268-a754-02e471f08063)



