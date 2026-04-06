**🐶🐱 Cat vs Dog Image Classification Using TinyCNN**

**📌 Project Overview**

This project implements an image classification system that identifies whether an uploaded image belongs to a cat or a dog. A lightweight Convolutional Neural Network (TinyCNN) is used to extract visual features from images and perform binary classification.
The model is designed to be efficient, making it suitable for learning purposes and scalable for deployment in real‑world applications.

**🎯 Objective**

To build and train a deep learning model capable of classifying images into Cat or Dog categories with good accuracy using convolutional neural networks.

**🧠 Machine Learning Approach**

**Model Used:** Tiny Convolutional Neural Network (TinyCNN)
**Problem Type:** Binary Image Classification

Why TinyCNN?

Lightweight and fast to train
Suitable for small to medium‑sized image datasets
Helps understand CNN fundamentals such as convolution, pooling, and feature extraction


**🗂️ Dataset Description**

The dataset consists of labeled images belonging to two classes:

Cat
Dog

Images are preprocessed before training to ensure consistency and efficient learning.

**⚙️ Data Preprocessing**

Images resized to a fixed input shape
Pixel values normalized for better convergence
Dataset split into training and validation sets
Labels encoded into numerical format


**🧪 Model Training**

The TinyCNN architecture includes:

Convolutional layers for feature extraction
Pooling layers for dimensionality reduction
Fully connected layers for classification
Sigmoid activation function for binary output

The model is trained using a supervised learning approach with an appropriate loss function (binary cross‑entropy) and optimizer.

**📈 Model Evaluation & Prediction**

Model performance is evaluated on validation data
Accuracy and loss metrics are monitored during training
The trained model predicts whether a user‑uploaded image is a Cat or a Dog

✅ The system outputs a clear prediction based on learned visual patterns.

**🛠️ Technologies Used**

Python
NumPy
TensorFlow / PyTorch (depending on your implementation)
OpenCV / PIL (for image preprocessing)


**🚀 Future Enhancements**

Improve accuracy using data augmentation
Replace TinyCNN with transfer learning models (VGG16, ResNet)
Deploy the model as a web application (Streamlit / Flask)
Add confidence score to predictions


**👤 Author**

Santhosh P
Application Support Engineer | Aspiring Machine Learning Engineer
