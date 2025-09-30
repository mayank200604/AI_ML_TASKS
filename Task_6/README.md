# Task 6 – KNN Classification on Iris Dataset

## 📌 Objective
The goal of this task is to:
1. Apply **K-Nearest Neighbors (KNN)** for classification.
2. Experiment with different values of `k`.
3. Evaluate the model using **accuracy** and **confusion matrix**.
4. Visualize **decision boundaries** for a 2D feature space.


## 📂 Dataset
We used the classic **Iris dataset** from `sklearn.datasets`.  
- Features: 4 numerical features (`sepal length`, `sepal width`, `petal length`, `petal width`).  
- Target: 3 classes (`setosa`, `versicolor`, `virginica`).  


## ⚙️ Steps Performed
1. **Load & Normalize Data**
   - Standardized features using `StandardScaler`.

2. **Train-Test Split**
   - Split into training (70%) and testing (30%) sets.

3. **Model Training**
   - Trained `KNeighborsClassifier` with different values of `k` (1, 3, 5, 7, 9).

4. **Evaluation**
   - For each `k`, computed:
     - **Accuracy**
     - **Confusion Matrix**

5. **Visualization**
   - Used only the first two features for plotting decision boundaries.
   - Plotted using `mlxtend.plotting.plot_decision_regions`.


 ### Decision Boundary (k = 5)
   - Plotted decision regions using first two features.
   - Shows how KNN separates the three Iris classes.

🛠 Requirements
Python 3.x
Jupyter Notebook / Jupyter Lab

Libraries:
pip install numpy matplotlib seaborn scikit-learn mlxtend


