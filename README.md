# Iris Flower Classification

This project uses a machine learning pipeline to classify iris flowers into three species — *setosa*, *versicolor*, and *virginica* — based on their sepal and petal measurements. It is based on the classic **Iris dataset** introduced by Ronald A. Fisher.

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Attributes**:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
  - Species (target variable with 3 classes)

## Features

- Exploratory Data Analysis with visualizations
- Data preprocessing and normalization
- Model training using Logistic Regression, KNN, Decision Trees, etc.
- Evaluation with accuracy scores and confusion matrices

## 📈 Workflow

1. **Data Loading** – Load Iris dataset using `sklearn.datasets`.
2. **Exploratory Data Analysis** – Use `pandas`, `matplotlib`, and `seaborn` to analyze feature distributions and class separability.
3. **Modeling** – Train and compare multiple models:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree Classifier
   - Support Vector Machine (SVM)
4. **Evaluation** – Measure performance using accuracy, confusion matrix, and classification report.
   
## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/iris-flower-classification.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook:
    ```bash
    jupyter notebook iris_flower_classification.ipynb
    ```
