# Plant_Disease_Classifier
Overview
The Plant Disease Classifier is a deep learning project aimed at solving a multi-class detection problem. The classifier is designed to identify 38 different classes of plant diseases using convolutional neural networks (CNNs). This project includes data analysis, model building, hyperparameter tuning, and deployment.

Features

Data Analysis: Comprehensive data analysis to understand the distribution and characteristics of the dataset.

Model Architecture: A CNN model with 3 Conv2D layers and 2 Dense layers, culminating in a Softmax output layer for multi-class classification.

Hyperparameter Tuning: Optimization of epochs, dense layers, and convolutional layers to improve model performance.

Front-End Integration: Utilization of Streamlit for an interactive front-end interface.

Deployment: Deployment using Docker for containerized execution.


Model Details

Convolutional Layers: 3 Conv2D layers for feature extraction.

Dense Layers: 2 Dense layers for classification.

Output: Softmax layer for predicting 38 classes.

Optimization: Hyperparameter tuning to refine model performance.


Deployment
The application is deployed using Docker, ensuring easy scalability and portability. The front end is built with Streamlit, providing an intuitive user interface for interacting with the classifier.
