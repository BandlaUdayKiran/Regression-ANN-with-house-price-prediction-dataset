#  Boston House Price Prediction Using Deep Learning

**Overview**

This project aims to predict the median value of owner-occupied homes (MEDV) in the Boston area using various features of the houses and their surroundings. The dataset used is the Boston Housing Dataset, which contains information about different houses in Boston.

**Objectives**

Preprocess the data to prepare it for modeling.
Build and train a neural network model using TensorFlow and Keras.
Evaluate the model’s performance using appropriate metrics.
Visualize the training process to assess model performance.

**Steps Involved**

*Import Required Libraries:-* Load essential libraries for data manipulation, visualization, preprocessing, model building, and evaluation.

*Load the Dataset:-* Load the Boston Housing Dataset into a pandas DataFrame.

*Data Exploration and Cleaning:-* Check for missing values in the dataset.

> Identify numerical and categorical features for preprocessing.

*Preprocessing:-* Use ColumnTransformer to scale numerical features and one-hot encode categorical features.

* Split the data into training and testing sets (80% training, 20% testing).

*Model Building:-* Define a neural network model with two hidden layers using the Sequential API from Keras.

? Compile the model with sgd optimizer and mean squared error loss function.

*Model Training:-* Train the model on the training data with validation split to monitor performance on validation set.

? Train for 100 epochs with a batch size of 32.

*Model Evaluation:-* Evaluate the model on the test set and print the Root Mean Squared Error (RMSE).

> Visualize the training and validation loss over epochs to understand the learning process.

*Predictions and Performance Metrics:-* Make predictions on the test set.

> Calculate and print the Mean Squared Error (MSE) and R² score.
