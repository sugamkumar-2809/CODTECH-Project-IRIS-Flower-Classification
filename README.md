CODTECH INTERN ID - CT-1333

# 🌸 Iris Flower Classification using Machine Learning

A complete Machine Learning classification project that predicts the species of an Iris flower using its sepal and petal measurements.

This project demonstrates the complete Machine Learning workflow, including:

- 📂 Dataset Loading
- 📊 Exploratory Data Analysis (EDA)
- 📈 Data Visualization
- 🔀 Train-Test Splitting
- 🤖 Model Training
- 📊 Model Evaluation
- 🌸 Species Prediction

---

## 🚀 Project Overview

The Iris Flower dataset is one of the most popular datasets in Machine Learning. The objective is to classify an Iris flower into one of three species based on its physical measurements.

### 🌼 Iris Species

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

## 📂 Dataset Information

The dataset contains **150 samples** with **4 numerical features** and **1 target class**.

| Feature | Description |
|----------|-------------|
| Sepal Length | Length of sepal (cm) |
| Sepal Width | Width of sepal (cm) |
| Petal Length | Length of petal (cm) |
| Petal Width | Width of petal (cm) |
| Class Labels | Iris Species |

### Dataset Size

- Rows: **150**
- Features: **4**
- Classes: **3**

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset statistics
- Feature analysis
- Pairwise feature visualization
- Species distribution

### Visualization

- Pair Plot
- Statistical Summary
- Feature Relationships

Visualization Library:

- Matplotlib
- Seaborn

---

## 🔀 Data Preprocessing

The dataset is divided into:

- Features (X)
- Target Labels (Y)

Training and testing datasets are created using:

```python
train_test_split()
```

Split Ratio:

- Training Data: **80%**
- Testing Data: **20%**

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared.

### 1️⃣ Support Vector Machine (SVM)

- Support Vector Classifier (SVC)
- Best performing model

**Accuracy:** **96.67%**

---

### 2️⃣ Logistic Regression

A multiclass Logistic Regression classifier was trained.

**Accuracy:** **93.33%**

---

### 3️⃣ Decision Tree Classifier

Decision Tree classification model for species prediction.

**Accuracy:** **96.67%**

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Support Vector Machine | **96.67%** |
| Logistic Regression | **93.33%** |
| Decision Tree Classifier | **96.67%** |

---

## 📋 Classification Report

The project evaluates the model using:

- Accuracy
- Precision
- Recall
- F1-Score

Performance Metrics:

- Precision
- Recall
- F1 Score
- Support

---

## 🌸 Species Prediction

The trained model can classify new flower measurements.

### Example

```python
X_new = np.array([
    [3, 2, 1, 0.2],
    [4.9, 2.2, 3.8, 1.1],
    [5.3, 2.5, 4.6, 1.9]
])

prediction = model_svc.predict(X_new)
```

### Output

```text
['Iris-setosa'
 'Iris-versicolor'
 'Iris-versicolor']
```

---

## 🛠️ Technologies Used

### Programming Language

- Python 3.x

### Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 🎯 Learning Outcomes

This project helps you understand:

- Classification Problems
- Data Visualization
- Feature Selection
- Train-Test Split
- Support Vector Machines
- Logistic Regression
- Decision Trees
- Model Evaluation
- Accuracy Measurement

---

## 🔮 Future Improvements

- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Naive Bayes Classifier
- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- Confusion Matrix Visualization
- Streamlit Web Application
- Model Deployment

---


## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

**Happy Learning! 🌸🚀**
