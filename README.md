# Autism Detection System
This repository contains a complete workflow for predicting Autism Spectrum Disorder (ASD) traits in toddlers using a combination of machine learning models and a graphical user interface (GUI). The system is divided into three main components:

## 1. Autism Detection Model Selection (Autism_Detection_of_Early_Childhood_Screening.ipynb)
+ In this notebook, we explore various machine learning algorithms and select the most suitable model for predicting ASD traits. The model is trained on the Toddler Autism dataset from July 2018.
+ We preprocess the data, handle missing values, and optimize the model for performance using metrics such as accuracy, precision, recall, and F1-score.
+ The selected model (e.g., Random Forest, Logistic Regression) is then used to make predictions.

## 2. Graphical User Interface (gui.ipynb)
+ The GUI allows users to input data such as age, gender, and Q-chat-10 responses in a user-friendly way.
+ The inputs are processed and prepared for the model.
+ Once the data is entered, the system forwards the input to the predictor for real-time classification.

## 3. Prediction (predictor.ipynb)
+ This script takes the preprocessed data from the GUI and runs it through the selected model to predict whether the subject shows ASD traits.
+ It outputs the final classification result based on the model's predictions.

## 4.Files Overview
+ Toddler Autism dataset July 2018.xlsx: The dataset used for training and testing the model.
+ qchat10_results.xlsx: The dataset containing the user inputs for Q-chat-10 responses.
+ predictor.ipynb: The script responsible for running predictions using the trained model.
+ gui.ipynb: The notebook for the graphical user interface, which collects user inputs.
+ Autism_Detection_of_Early_Childhood_Screening.ipynb: The main notebook that handles data preprocessing, model selection, and training.

## 5.Getting Started
To run the system:

+ Clone this repository.
+ Open Autism_Detection_of_Early_Childhood_Screening.ipynb to explore the model selection process.
+ Use gui.ipynb to input user data.
+ Run predictor.ipynb to generate predictions based on the input.

## Dataset Description
The Toddler Autism dataset contains various features related to the child's behavior, such as responses to the Q-chat-10 questionnaire, family history, and demographic details. This dataset is used to train the machine learning model for autism detection.

