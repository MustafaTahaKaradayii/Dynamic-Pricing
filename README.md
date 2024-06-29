Dynamic Pricing for Airline Cargo
This repository contains a Python script for predicting freight prices using machine learning. The code performs data preprocessing, feature engineering, and builds a neural network model for price prediction. Users can input cargo details for personalized predictions. This project is valuable for logistics and pricing decisions.

Table of Contents
  1-Installation
  2-Usage
  3-Data Preprocessing
  4-Feature Engineering
  5-Model Training
  6-Prediction
  7-Evaluation
  8-Future Work
  9-Contributing
  10-License

Data Preprocessing
  The data preprocessing steps include:
  
  Loading the data into a pandas DataFrame
  Dropping irrelevant features: 'Day of the week', 'Number of layovers', etc.
  Identifying and removing rows with NaN or empty values
  Removing columns with constant or redundant values
  Dropping features with low importance based on feature selection
Feature Engineering
  Feature engineering steps involve:
  
  Encoding categorical features using LabelEncoder
  Scaling numerical features using MinMaxScaler
  Splitting the data into training and testing sets
Model Training
  The model training involves:
  
  Creating a neural network model using Keras
  Compiling the model with Adam optimizer and mean absolute error loss function
  Training the model with training data and validating on a validation set
  Prediction
  The prediction process includes:
  
  Preprocessing user input with scaling and encoding
  Using the trained model to predict the price based on user input
Evaluation
  The model evaluation metrics include:
  
  Mean Absolute Error (MAE)
  R-squared (R2) Score
  Future Work
  Future improvements can include:
  
  Integrating more advanced feature selection techniques
  Exploring different neural network architectures
  Implementing cross-validation for model evaluation
Contributing
  Contributions are welcome! Please feel free to submit a Pull Request.

License
  This project is licensed under the MIT License.
