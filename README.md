# Iris Flower Classification using Machine Learning

This repository contains a complete, end-to-end machine learning workflow for the classic **Iris Dataset**. The goal is to classify iris flowers into three species based on their sepal and petal measurements.

##  Project Overview
The Iris dataset is the "Hello World" of Machine Learning. This project demonstrates how to:
- Load and explore data.
- Preprocess features for training.
- Implement a **Logistic Regression** classification model.
- Evaluate model performance using Accuracy, Confusion Matrices, and Classification Reports.

##  Dataset Description
The dataset consists of 150 samples from three species of Iris:
1. **Iris Setosa**
2. **Iris Versicolor**
3. **Iris Virginica**

Each sample has four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

##  Technical Stack
- **Language:** Python
- **Libraries:** - `Scikit-learn`: For model building and evaluation.
  - `Pandas`: For data manipulation.
  - `NumPy`: For numerical operations.
  - `Matplotlib/Seaborn`: For data visualization.

##  Model Performance
The model achieves high accuracy by leveraging the distinct clusters formed by the petal and sepal dimensions.
- **Algorithm:** Logistic Regression (Multinomial)
- **Evaluation Metrics:**
  - Accuracy Score
  - Confusion Matrix (to visualize misclassifications)
  - Precision, Recall, and F1-Score

##  How to Use
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/Iris-ML-Classification.git](https://github.com/your-username/Iris-ML-Classification.git)
2. **Install Dependencies:**
   ```bash
   pip install pandas scikit-learn numpy matplotlib
3. **Run The Notebook:**  
   Open `Iris_ML_Classification.ipynb` in Jupyter Lab or Google Colab and run all cells to see the results.
