# Mobile Price Prediction Using K-Nearest Neighbors (KNN)
This project focuses on predicting the price range of mobile phones using the K-Nearest Neighbors (KNN) classification algorithm. The dataset includes various features such as battery power, RAM, screen resolution, and internal memory. The goal is to classify phones into one of four price ranges based on these features.

## Key Steps in the Project:
### Data Preprocessing:

The dataset is loaded and divided into training and testing sets using train_test_split.
Features include battery_power, RAM, px_height, px_width, fc (front camera), n_cores, and more.
### Model Training:

A KNN classifier is trained using KNeighborsClassifier with n_neighbors=5 and the Minkowski distance metric (Manhattan distance).
The model is trained on the training set and tested on the test set for predictions.
### Model Evaluation:

Evaluation metrics include the confusion matrix, classification report, and accuracy score.
Visualizations like confusion matrix plots are provided to understand model performance.
### Gradio User Interface:

The project incorporates an interactive interface using Gradio, allowing users to input mobile phone features like battery power, RAM, and screen resolution.
The interface predicts the price range of mobile phones based on user input in real-time.
## Features:
Dataset: Contains mobile phone specifications including battery power, RAM, screen resolution, and other important features.
KNN Algorithm: Uses KNN to classify mobile phones into four price ranges based on feature similarities.
Performance Metrics: Evaluates model accuracy with confusion matrix and classification reports.
Interactive Interface: A Gradio interface enables users to enter mobile features and get price range predictions instantly.
This project demonstrates the application of KNN for mobile price prediction with an interactive user-friendly interface.
