**Fashion E-commerce Product Success Prediction**


**Overview**
This repository contains code for a machine learning application developed for a fashion e-commerce company. The application aims to predict the success or failure of potential products based on past data on the company's top and flop products.

**Problem Statement**
The fashion e-commerce company is planning its collections for the upcoming year and has gathered data on past products to estimate their success potential. The goal is to create a machine learning model that can accurately predict whether a product will be successful (top) or not (flop) based on various features.

**Dataset**
The dataset provided includes information on past years' top and flop products. It consists of features such as product attributes, customer reviews, sales data, and other relevant information.

**Models and Performance**
We have trained several machine learning models on the dataset and evaluated their performance using cross-validation. Here are the accuracy scores of the models:

Neural Network: 0.812344 (0.016980)
KNN: 0.838125 (0.018556)
XGBoost: 0.837812 (0.011834)
SVM: 0.822500 (0.015722)
Logistic Regression: 0.793125 (0.013607)
Decision Tree: 0.790000 (0.012774)


**Usage**
Clone the repository.
Install the required dependencies.
Run the main script or notebooks to train and evaluate the models.
Use the trained model to predict the success of new products.

**Dependencies**
Python 3.x
scikit-learn
XGBoost
pandas
numpy


**Contribution**
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.
