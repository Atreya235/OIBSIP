# 🌸 Iris Flower Classification using Machine Learning

This project classifies Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — based on the length and width of their petals and sepals. It's a classic supervised classification problem and a great starting point for beginners in machine learning.

---

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Format**: CSV
- **Features**:
  - `SepalLengthCm`
  - `SepalWidthCm`
  - `PetalLengthCm`
  - `PetalWidthCm`
- **Target**:
  - `Species`: Categorical (`Setosa`, `Versicolor`, `Virginica`)

---

## 📌 Objectives

- Train a machine learning model on the Iris dataset
- Predict species based on sepal/petal measurements
- Allow user input for real-time prediction
- Evaluate model using accuracy and classification report

---

## 🧠 Model Used

- **RandomForestClassifier** from Scikit-learn
- Target column (`Species`) encoded using `LabelEncoder`

---

## 🧪 Technologies

- Python 3
- Pandas
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## ✅ How to Use

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/iris-classification.git
cd iris-classification

