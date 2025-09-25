Task 3 - Linear Regression Model

📌 Overview

This task focuses on building a Linear Regression model to predict house prices based on features such as Age, Bedrooms, and Area. The notebook first_ML.ipynb demonstrates the full workflow from data preprocessing to model evaluation and visualization.

🔑 Key Steps

1. Data Import and Preprocessing

Load the dataset using pandas.

Handle missing values and ensure the dataset is clean for modeling.

2. Train-Test Split

Divide the dataset into training and testing sets using train_test_split from sklearn.model_selection.

Ensures proper evaluation on unseen data.

3. Model Training

Fit a Linear Regression model using sklearn.linear_model.LinearRegression.

Train the model on the training set to learn the relationship between features and target.

4. Model Evaluation

Evaluate the model performance using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

Understand how well the model predicts house prices.

5. Visualization and Interpretation

Plot scatter plots of features (e.g., Area vs Price) and overlay the regression line.

Interpret coefficients to see how each feature affects the target variable.

🛠 Requirements

Python 3.x

Jupyter Notebook / Jupyter Lab

Libraries:

pip install numpy pandas matplotlib seaborn scikit-learn