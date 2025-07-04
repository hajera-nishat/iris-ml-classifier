# 🌸 Iris ML Classifier

This project is a simple machine learning classifier built using the **Iris flower dataset**. It uses a **Random Forest Classifier** from `scikit-learn` to predict the species of iris flowers based on petal and sepal measurements.

## 📊 Dataset

The [Iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set) is one of the most well-known datasets in data science and includes:

- 150 samples
- 3 flower species:
  - *Iris setosa*
  - *Iris versicolor*
  - *Iris virginica*
- 4 features per sample:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width

## 🛠️ Tools & Libraries Used

- Python 3.11
- scikit-learn
- pandas
- NumPy

## 🔍 How It Works

1. Loads the Iris dataset from `sklearn.datasets`
2. Splits the data into training and testing sets
3. Trains a Random Forest model
4. Evaluates it using accuracy score

## ✅ Accuracy

🌸 Model Accuracy: 100.00%

> Note: Accuracy may vary slightly based on random seed or data split.

## 📂 How to Run

```bash
pip install scikit-learn pandas numpy
python iris_classifier.py

