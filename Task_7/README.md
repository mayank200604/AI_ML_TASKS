# Task 7 🌸 SVM Classification on Iris Dataset with GridSearchCV

This project demonstrates **Support Vector Machine (SVM)** classification on the **Iris dataset**, including **hyperparameter tuning using GridSearchCV**, feature scaling, and **visualization of decision boundaries in 2D**. The goal is to build an accurate classifier while understanding the effect of different hyperparameters and kernels.


## 📌 Project Overview

The Iris dataset is a classic dataset in machine learning, consisting of 150 samples of three Iris species: **Setosa, Versicolor, and Virginica**. Each sample has **four features**: sepal length, sepal width, petal length, and petal width.

This project involves:

1. **Loading and preparing the dataset**  
   - Scaling features using `StandardScaler` for better SVM performance.

2. **Splitting the dataset**  
   - Train/test split (70/30) to evaluate model performance.

3. **Training an SVM classifier**  
   - Using both **linear** and **RBF kernels**.

4. **Hyperparameter tuning using GridSearchCV**  
   - Parameters tuned: `C`, `gamma`, `kernel`.  
   - Cross-validation (`cv=3`) to find the optimal model.

5. **Evaluating model performance**  
   - Test set accuracy using the best SVM model from GridSearch.  

6. **Visualizing the decision boundary**  
   - Since the dataset has 4 features, PCA is used to reduce it to **2 dimensions** for plotting.  
   - The decision boundary shows how the classifier separates different classes.


## ⚙️ Requirements

Install the following Python libraries:

pip install numpy pandas matplotlib scikit-learn mlxtend 
