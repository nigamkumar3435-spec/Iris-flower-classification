# 🌸 Iris Flower Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![Classification](https://img.shields.io/badge/Task-Classification-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

# 📌 Project Overview

The **Iris Flower Classification** project is a supervised Machine Learning application that classifies Iris flowers into one of three species based on their physical characteristics.

The project demonstrates the complete classification workflow, including:

* Data Loading
* Data Visualization
* Feature Selection
* Train-Test Split
* Model Training
* Model Evaluation
* Species Prediction

The famous **Iris Dataset** is widely used as an introductory dataset for Machine Learning classification problems.

---

# 🎯 Objective

To build an accurate Machine Learning model capable of identifying the species of an Iris flower using four flower measurements.

---

# 🌼 Iris Species

The model predicts one of the following classes:

* 🌸 Iris-setosa
* 🌺 Iris-versicolor
* 🌷 Iris-virginica

---

# 📊 Dataset Information

### Dataset Size

* Total Samples: **150**
* Features: **4**
* Target Classes: **3**

### Features Used

| Feature      | Description          |
| ------------ | -------------------- |
| Sepal Length | Length of Sepal (cm) |
| Sepal Width  | Width of Sepal (cm)  |
| Petal Length | Length of Petal (cm) |
| Petal Width  | Width of Petal (cm)  |

### Target Variable

```text
Class_labels

• Iris-setosa
• Iris-versicolor
• Iris-virginica
```

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

### Development Environment

* Jupyter Notebook
* Google Colab
* VS Code

---

# 📂 Project Structure

```text
Iris_Flower_Classification/
│
├── IRIS.csv
├── Project3_Iris_Flower_Classification.ipynb
├── README.md
│
└── outputs/
    ├── pairplot.png
    ├── predictions.png
    └── classification_report.png
```

---

# 🔄 Machine Learning Workflow

```text
Dataset Loading
        ↓
Data Visualization
        ↓
Feature Selection
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Species Prediction
```

---

# 📈 Exploratory Data Analysis

The project performs:

* Dataset Summary
* Statistical Analysis
* Pair Plot Visualization
* Feature Relationship Analysis

The **Seaborn PairPlot** helps visualize how different flower species are separated based on feature combinations.

---

# 🤖 Machine Learning Models

Three classification algorithms were implemented and compared.

## 1️⃣ Support Vector Machine (SVM)

* Algorithm: Support Vector Classifier (SVC)

### Accuracy

```text
96.67%
```

---

## 2️⃣ Logistic Regression

### Accuracy

```text
93.33%
```

---

## 3️⃣ Decision Tree Classifier

The Decision Tree model was trained for comparison with the other classifiers.

---

# 📊 Model Comparison

| Model                        | Accuracy   |
| ---------------------------- | ---------- |
| Support Vector Machine (SVM) | **96.67%** |
| Logistic Regression          | **93.33%** |
| Decision Tree Classifier     | **96.67%** |

---

# 📋 Classification Report

The project evaluates the classification performance using:

* Precision
* Recall
* F1-Score
* Accuracy

The Logistic Regression model achieved:

* Overall Accuracy: **93%**
* Strong performance across all three Iris species.

---

# 🌸 Sample Prediction

Example Input

```python
X_new = np.array([
    [3, 2, 1, 0.2],
    [4.9, 2.2, 3.8, 1.1],
    [5.3, 2.5, 4.6, 1.9]
])
```

### Predicted Species

```text
Iris-setosa
Iris-versicolor
Iris-versicolor
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Iris-Flower-Classification.git
```

## Navigate to Project

```bash
cd Iris-Flower-Classification
```

## Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Run Notebook

```bash
jupyter notebook
```

Open:

```text
Project3_Iris_Flower_Classification.ipynb
```

---

# 📊 Visualizations Included

* Pair Plot
* Dataset Statistics
* Feature Distribution
* Model Predictions
* Classification Report

---

# 💡 Key Insights

✔ The Iris dataset contains three well-defined flower species.

✔ Petal length and petal width are the most discriminative features.

✔ Support Vector Machine achieved the highest classification accuracy of **96.67%**.

✔ Logistic Regression also performed strongly with **93.33%** accuracy.

✔ The project demonstrates a complete supervised classification workflow.

---

# 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Supervised Machine Learning
* Data Visualization
* Feature Extraction
* Classification Algorithms
* Model Evaluation
* Species Prediction
* Scikit-Learn Workflow

---

# 🔮 Future Enhancements

* Hyperparameter Tuning
* Cross Validation
* Confusion Matrix Visualization
* ROC Curve Analysis
* GridSearchCV Optimization
* Streamlit Web Application
* Flask API Deployment
* Interactive Prediction Dashboard

---

# 👨‍💻 Author

**Nigam Kumar**

🎓 B.Tech – Computer Science Engineering
🏫 Indore Institute of Science and Technology, Indore
📍 Madhya Pradesh, India

### Connect With Me

* GitHub: https://github.com/nigamkumar3435-spec
* LinkedIn: https://www.linkedin.com/in/nigam-kumar01

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

### 🌸 Exploring Machine Learning Through Intelligent Flower Classification 🚀
