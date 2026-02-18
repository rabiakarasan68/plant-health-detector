#🌿 Plant Health Detector (Healthy vs Diseased)

This project is a Convolutional Neural Network (CNN) based image classification system that predicts whether a plant leaf is healthy or diseased. The model is trained using labeled leaf images and learns visual features to distinguish plant health conditions.

#📌 Project Overview

Plant diseases can negatively affect crop production and quality. This project uses deep learning and computer vision techniques to automatically classify plant leaves.

The model performs binary classification:

Healthy 🌱

Diseased 🍂

The notebook includes:

Dataset loading from directory

Image preprocessing and normalization

Data augmentation for training

CNN model creation

Model training and validation

Accuracy and loss visualization

Displaying sample images from dataset

#🧠 Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Jupyter Notebook

#⚙️ Model Architecture

The CNN model consists of:

3 Convolutional layers

3 MaxPooling layers

Flatten layer

Dense layer (128 neurons)

Dropout layer (0.5)

Output layer (Sigmoid activation)

Loss function:

binary_crossentropy


Optimizer:

Adam (learning rate = 0.001)

#▶️ How to Run
1. Install required libraries
pip install tensorflow numpy matplotlib

2. Make sure dataset folder is structured correctly
dataset/train
dataset/test

3. Open and run notebook
bitki_hastalığı1.ipynb

Run all cells sequentially.

#📊 Output

The notebook generates:

Training Accuracy graph

Validation Accuracy graph

Training Loss graph

Validation Loss graph

Sample dataset images

#🎯 Model Goal

Classify plant leaf images into:

✅ Healthy

❌ Diseased
