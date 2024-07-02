
Fashion Image Classifier

This project is a full machine learning pipeline for classifying fashion images using the Fashion MNIST dataset. The pipeline includes training the model, saving the trained model, deploying it with a Streamlit app, and containerizing the application with Docker.

Table of Contents

->Introduction
->Dataset
->Model Training
->Streamlit App
->Dockerization

Introduction
The goal of this project is to build a fashion image classifier that can recognize different types of clothing items from the Fashion MNIST dataset. This project covers the entire machine learning workflow from data preprocessing and model training to deployment and containerization.

Dataset
The Fashion MNIST dataset consists of 70,000 grayscale images of 28x28 pixels each, with 10 different categories of clothing items. The dataset is split into 60,000 training images and 10,000 testing images.

Model Training
The model is trained using a convolutional neural network (CNN) architecture. 

The training process includes:
Data preprocessing: Normalizing the pixel values and reshaping the images.
Building the CNN model.
Compiling the model with appropriate loss function and optimizer.
Training the model on the training dataset.
Evaluating the model on the testing dataset.
Saving the trained model for future use.

Streamlit App
The trained model is deployed using a Streamlit app. The app allows users to upload an image and get predictions about the type of clothing item in the image. 

Key features of the app include:
User-friendly interface for uploading images.
Real-time prediction display.
Visualization of the uploaded image and prediction results.

Dockerization
To ensure the application is portable and can be easily deployed, it is containerized using Docker. 

