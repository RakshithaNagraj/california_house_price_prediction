California Housing Price Prediction
This project explores the California Housing dataset and builds a linear regression model to predict median house values.

Dataset
The dataset used in this project is the California Housing dataset, which contains information about median house values in California districts based on the 1990 U.S. census. The dataset includes the following attributes:

MedInc: median income in block group
HouseAge: median house age in block group
AveRooms: average number of rooms per household
AveBedrms: average number of bedrooms per household
Population: block group population
AveOccup: average number of household members
Latitude: block group latitude
Longitude: block group longitude
The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).

Project Structure
The project is organized as a Jupyter Notebook (or Google Colab notebook) with the following steps:

Data Loading and Exploration: Load the California Housing dataset and perform initial data exploration, including checking the shape and exploring the dataset description.
Data Preparation: Create a pandas DataFrame from the dataset and add the target variable. Display the first few rows of the DataFrame.
Data Visualization: Generate visualizations to understand the distribution of the target variable and the relationships between features.
Feature Selection: Select the features to be used for training the linear regression model.
Model Training: Split the data into training and testing sets and train a linear regression model.
Model Evaluation: Evaluate the performance of the linear regression model using metrics like Mean Squared Error (RMSE) and R-squared.
Polynomial Regression: Explore a polynomial regression model to see if it improves performance.
Dependencies
The project requires the following libraries:

pandas
numpy
seaborn
matplotlib
scikit-learn
You can install the dependencies using pip:# california_house_price_prediction
