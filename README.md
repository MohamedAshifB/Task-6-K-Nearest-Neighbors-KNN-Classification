# 🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset

This project implements the K-Nearest Neighbors (KNN) algorithm to classify flowers in the popular Iris dataset. It includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

## 📌 Task Objective
- Understand and implement the KNN algorithm.
- Normalize features and evaluate the classifier.
- Visualize decision boundaries using the first two features.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository - Iris](https://www.kaggle.com/datasets/uciml/iris)
- **Features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target**: Iris-setosa, Iris-versicolor, Iris-virginica

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 Steps Performed

1. **Data Loading**  
   Loaded `Iris.csv` using Pandas.

2. **Data Preprocessing**  
   - Dropped unnecessary columns (like `Id`).
   - Normalized feature values using `StandardScaler`.

3. **Model Training**  
   - Used `KNeighborsClassifier` from Scikit-learn.
   - Trained with different values of `K` (starting with K=3).

4. **Evaluation**  
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

5. **Visualization**  
   - Plotted decision boundaries using the first 2 features.

---

## 📈 Output Examples

### 📊 Confusion Matrix
