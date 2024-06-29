# PRODIGY_ML_01
Task-01
Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

Approach:
To implement a linear regression model for predicting house prices, you can follow these steps:

Data Preparation:
Loaded the dataset from Kaggle.
Load the dataset into a pandas DataFrame.
Check for and handle any null values.

Feature Selection:
Choose relevant features for your model. In this case, consider ‘Square Footage,’ ‘Number of Bedrooms,’ and ‘Number of Bathrooms.’
Split data into training and testing sets.

Outlier Analysis and Treatment:
Detect and handle outliers in the ‘Price’ and ‘Area’ variables.

Data Splitting:
Split the data into training and testing sets.

Model Building:
Utilized scikit-learn’s Linear Regression model.
Trained the model on the training data.
Made predictions on the test data.

Linear Regression Model:
Train a linear regression model using scikit-learn.
Evaluate the model’s performance using the R-squared score.

Evaluation:
Calculated the R-squared score to assess model performance.

Technologies Used:
Python 🐍
pandas 🐼
matplotlib 📈
seaborn 🌟
scikit-learn 🤖
