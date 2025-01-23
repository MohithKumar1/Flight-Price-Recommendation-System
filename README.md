#  Flight Price Prediction

This project focuses on building a machine learning model to predict flight ticket prices based on various features like airline, source, destination, and other parameters. The project demonstrates data preprocessing, feature engineering, model training, and evaluation techniques.

# Project Overview :
Flight ticket pricing is dynamic and influenced by multiple factors. This project uses machine learning to predict ticket prices and explores:

Data cleaning and preprocessing.
Feature engineering for time-based and categorical data.
Model training and hyperparameter optimization.

# Dataset
The dataset used for this project is Data_Train.xlsx, which contains features like:

Airline: Name of the airline.
Source & Destination: Origin and destination of the flight.
Total Stops: Number of stops during the flight.
Duration: Duration of the flight.
Price: Target variable for prediction.

# Key Features
Preprocessing:

Handled missing data and categorical encoding.
Extracted features from date-time columns (e.g., journey day, month).
Engineered features like flight duration in minutes.

Visualization:

Used Seaborn and Plotly for exploratory data analysis (EDA) to visualize distributions and relationships.

Modeling:

Implemented and compared models like:
Random Forest Regressor
Decision Tree Regressor
Hyperparameter tuning using RandomizedSearchCV.

# Results:

The model successfully predicts flight ticket prices with a good balance between bias and variance. Key insights include:

Top Influencing Features: Airlines, total stops, and flight duration.
Visualization Outcomes: Relationships between price and factors like airline and stops.
