Real Estate Price Prediction Model
Overview
This repository contains a machine learning model for predicting real estate prices based on various features of properties. The model is built using a dataset that includes details such as area, number of bedrooms and bathrooms, and the year a property was built, among others. This model can be used by real estate agents, buyers, and market analysts to estimate property values.

Dataset
The dataset used for this model consists of 10,000 synthetic records of property sales. Each record includes the following features:

Property_ID: Unique identifier for each property.
Location: The city or area where the property is located.
Area_sq_ft: The size of the property in square feet.
Bedrooms: The number of bedrooms.
Bathrooms: The number of bathrooms.
Year_Built: The year in which the property was built.
Amenities: Additional features of the property, such as a pool or garden.
Price: The sale price of the property.
Features
Exploratory Data Analysis (EDA): Initial exploration of the data to understand distributions and relationships.
Feature Engineering: Transformation of data to improve model performance.
Model Training and Evaluation: Implementation of multiple regression models to predict property prices.
GUI Application: A simple graphical user interface to input property features and obtain price predictions.
Models
The following models have been implemented and compared:

Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Requirements
This project uses Python 3.8 and the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
mlxtend (for association rule mining in market basket analysis)
To install the required libraries, run:

bash
Copy code
pip install -r requirements.txt
Usage
To train the model and make predictions, run the Jupyter notebook Real_Estate_Price_Prediction.ipynb.

For the GUI application, execute python real_estate_gui.py after training the model.

GUI Application
The GUI is built using Tkinter and allows users to input property attributes and get price predictions in real-time. Ensure the trained model is in the same directory as the GUI script.
