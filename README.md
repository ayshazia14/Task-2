# Iris Flower Classification — Decision Tree

A supervised machine learning project that classifies iris flowers into three species using a Decision Tree Classifier, built on the classic Iris dataset from scikit-learn.

---

## Overview

This project trains a Decision Tree model to classify iris flowers based on sepal and petal measurements. It demonstrates a clean end-to-end classification pipeline including model training, accuracy evaluation, and decision tree visualisation.

---

## Dataset

**Iris Dataset** — sourced from `sklearn.datasets.load_iris()`

| Feature | Description |
|---|---|
| sepal length (cm) | Length of the sepal |
| sepal width (cm) | Width of the sepal |
| petal length (cm) | Length of the petal |
| petal width (cm) | Width of the petal |
| **target** | **Species: Setosa, Versicolour, Virginica** |

150 samples, 3 classes, 4 features.

---

## Workflow

1. Load the Iris dataset from scikit-learn
2. Split into training and test sets (80/20, random state = 0)
3. Train a `DecisionTreeClassifier`
4. Predict on the test set
5. Evaluate accuracy using `metrics.accuracy_score`
6. Visualise the full decision tree using `plot_tree`

---

## Results

| Metric | Value |
|---|---|
| Test Accuracy | Printed at runtime |

The decision tree is visualised with feature names and class labels for interpretability.

---

## Technologies Used

- Python
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook Task_2.ipynb
```

The dataset is fetched automatically via scikit-learn — no manual download required.
