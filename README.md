# K-Nearest-Neighbors-Classification

This repository contains an implementation of the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**. The task includes data preprocessing, model training, evaluation, and decision boundary visualization.

## Objective
To understand and implement the KNN classification algorithm from scikit-learn and evaluate its performance on a real-world dataset.

## Dataset
- **Source**: [`Iris.csv`](https://archive.ics.uci.edu/ml/datasets/iris)
- **Features**: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm
- **Target**: Species (Setosa, Versicolor, Virginica)

## Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- NumPy

## Steps Followed
### 1. Load and Normalize Data
- Loaded dataset using `pandas`
- Normalized features using `MinMaxScaler`

### 2. Model Training
- Split data (80% train, 20% test)
- Trained `KNeighborsClassifier` (initially with `K=3`)

### 3. Experiment with Different K Values
- Compared accuracy for `K=1` to `K=20`
- Visualized performance to find the optimal K

### 4. Evaluation
- Used `accuracy_score`, `confusion_matrix`, and `classification_report` from `sklearn.metrics`

### 5. Visualization
- Plotted decision boundaries using 2D feature pairs (Petal Length vs Petal Width)

## Results
- Model achieved high accuracy (~96% with optimal K)
- Decision boundary clearly separates different iris species using petal features
