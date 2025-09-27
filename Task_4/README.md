Task 4: 🧪 Breast Cancer Classification using Logistic Regression

📌 Overview



This project focuses on building a Logistic Regression model to classify breast cancer tumors as Benign or Malignant.

Beyond model training, it also covers Threshold Tuning and ROC Curve analysis to improve performance, followed by custom predictions on unseen tumor samples.



🔑 Key Steps

1\. Data Import and Preprocessing



Loaded the Breast Cancer dataset.



Dropped the target column diagnosis to separate features (X) and labels (y).



Standardized features using StandardScaler to normalize scales.



2\. Train-Test Split



Split dataset into 70% training and 30% testing using train\_test\_split.



Ensured fair evaluation on unseen data.



3\. Model Training



Trained a LogisticRegression model from scikit-learn.



Learned the decision boundary to classify tumors as Benign (0) or Malignant (1).



4\. Probability Predictions \& Threshold Tuning



Used predict\_proba() to get class probabilities.



Applied a custom threshold of 0.3 instead of default 0.5.



Converted probabilities to labels (y\_pred\_custom).



Increased sensitivity for Malignant tumor detection.



5\. Model Evaluation



Metrics used:



✅ Accuracy



✅ Confusion Matrix



✅ Classification Report (Precision, Recall, F1-score)



6\. ROC Curve and AUC



Plotted the ROC Curve (TPR vs FPR).



Calculated AUC score to measure model robustness.



7\. Custom Predictions



Scaled new unseen inputs.



Predicted class and probabilities.



🛠 Requirements

pip install numpy pandas matplotlib scikit-learn





Python 3.x



Jupyter Notebook / Jupyter Lab

