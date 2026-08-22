# Calculating and Analyzing the Accuracy of Iris Flower Dataset

This project implements a Machine Learning pipeline using Python to classify species of Iris flowers. It utilizes a Random Forest Classifier trained on feature dimensions (sepal length, sepal width, petal length, and petal width) to predict the flower class.

---

## 📌 Project Overview

The main objective of this project is to build, evaluate, and test a classification model on the Iris flower dataset.

* **Model Used:** Random Forest Classifier (`sklearn.ensemble.RandomForestClassifier`)
* **Training Data Size:** 103 samples
* **Testing Data Size:** 34 samples
* **Test Accuracy Achieved:** **97.06%**

---

## 🛠️ Requirements & Dependencies

To run this project, make sure you have the following Python libraries installed:

* `pandas`
* `scikit-learn`
* `matplotlib`
* `seaborn`

Install them via `pip`:
```bash
pip install pandas scikit-learn matplotlib seaborn 
```

---

## 📂 Dataset Structure

The model expects Excel files (`.xlsx`) containing the following 5 columns:

| Column Name | Type | Description |
| :---          | :---   | :--- |
| `sepallength` | Float  | Length of the sepal in cm |
| `sepalwidth`  | Float  | Width of the sepal in cm  |
| `petallength` | Float  | Length of the petal in cm |
| `petalwidth`  | Float  | Width of the petal in cm  |
| `class`       | String | Target species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`) |

---

## 🚀 How to Run

1. Place your dataset files in the project root directory:
   * `irisflower_train.xlsx`
   * `irisflower_test.xlsx`
2. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook "iris_accuracy_analysis.ipynb"
   ```

---

## 📊 Model Evaluation Results

The Random Forest model evaluated 34 test samples, correctly predicting 33 out of 34 samples, resulting in an accuracy score of **97.06%**:

```text
Accuracy = (Correct Predictions / Total Test Samples) * 100
Accuracy = (33 / 34) * 100 = 97.0588%
```
