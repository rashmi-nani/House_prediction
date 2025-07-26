# House_prediction
This project uses machine learning models to predict house prices based on historical data and various features like number of bedrooms, bathrooms, square footage, location, and more. The model is trained using the Random Forest Regressor algorithm for better accuracy.
Dataset
The dataset was provided by a mentor and includes the following columns:

date: Sale date of the house

price: Target variable (house price)

bedrooms, bathrooms, floors

sqft_living, sqft_lot, sqft_above, sqft_basement

waterfront, view, condition

yr_built, yr_renovated

street, city, statezip, country

Objective
Build a regression model to predict the price of a house given its features.

Technologies Used
Python

Pandas & NumPy

Matplotlib & Seaborn (for visualization)

Scikit-learn (for model building)

Google Colab (for development)

⚙️ Machine Learning Workflow
Data Preprocessing

Converted date to datetime and extracted year, month, and day

Removed irrelevant columns (street, country)

Extracted ZIP code from statezip

One-hot encoded the city column

Removed missing values

Model Training

Used RandomForestRegressor from sklearn

Split dataset into training and testing sets (80/20 split)

Evaluation Metrics

R² Score to measure how well the model explains the variance

Mean Squared Error (MSE) to measure prediction error

Feature Importance

Visualized the top 20 most important features in predicting house prices

Model Saving

Trained model saved as house_price_model.pkl using joblib
