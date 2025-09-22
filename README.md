# Task 1 - Data Preprocessing & Visualization

## 📌 Overview
This task focuses on the fundamental steps of **data preprocessing** that are essential before applying any machine learning model.  
The notebook [`main.ipynb`](main.ipynb) demonstrates how to clean and prepare a dataset by handling missing values, dealing with categorical features, removing outliers, and performing basic visualizations.

## 🔑 Key Steps
1. **Handling Missing Values**  
   - Detecting missing data  
   - Imputing with mean/median/mode or dropping rows/columns  

2. **Dealing with Categorical Variables**  
   - Encoding categorical values (Label Encoding / One-Hot Encoding)  
   - Converting categorical features into numerical representations for ML models  

3. **Removing Outliers**  
   - Identifying outliers using statistical methods (IQR, Z-score)  
   - Dropping or capping outliers to make data more robust  

4. **Visualization**  
   - Distribution plots, histograms, and boxplots  
   - Correlation heatmaps for understanding feature relationships  

## 🛠️ Requirements
- Python 3.x
- Jupyter Notebook / Jupyter Lab
- Libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
