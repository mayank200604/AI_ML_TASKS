Task 5 - Decision Trees & Random Forests

📌 Overview

This task applies Decision Tree and Random Forest classifiers to the Heart Disease dataset.
It explores overfitting control, model comparison, feature importance interpretation, and reliable evaluation using cross-validation.



🔑 Key Steps


1. Train a Decision Tree Classifier and Visualize the Tree

Built a Decision Tree using DecisionTreeClassifier.

Visualized splits and rules with plot_tree() for interpretability.


2. Analyze Overfitting and Control Tree Depth

Compared unrestricted trees (deep, prone to overfitting) vs limited-depth trees.

Observed the trade-off between bias (shallow trees) and variance (deep trees).


3. Train a Random Forest and Compare Accuracy

Implemented RandomForestClassifier with 100 estimators.

Compared accuracy with a single Decision Tree.

Random Forest achieved better generalization and stability.


4. Interpret Feature Importances

Extracted feature_importances_ from the Random Forest.

Visualized most important medical features (cp, thalach, oldpeak, ca, thal).


5. Evaluate Using Cross-Validation

Applied 5-fold cross-validation to ensure robust accuracy estimation.

Provided a more reliable performance measure than a single train-test split.



🛠 Requirements

Python 3.x

Jupyter Notebook / Jupyter Lab



Libraries:

pip install numpy pandas matplotlib seaborn scikit-learn