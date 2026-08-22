# 🌸 Iris Flower Classification

A Machine Learning project that classifies Iris flower species using a **Random Forest Classifier** based on physical measurements of the flowers.

---

## 📌 Project Overview

The objective of this project is to build, evaluate, and test a classification model on the Iris flower dataset.

The model uses four physical measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Model Details

- **Model:** Random Forest Classifier
- **Training Samples:** 103
- **Testing Samples:** 34
- **Correct Predictions:** 33 / 34
- **Test Accuracy:** **97.06%**

---

## 🧠 Machine Learning Workflow

```text
Iris Dataset
     ↓
Data Loading
     ↓
Feature Selection
     ↓
Random Forest Classifier
     ↓
Model Prediction
     ↓
Accuracy Evaluation
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset

The project uses Excel (`.xlsx`) files containing the following columns:

| Column        | Type   | Description               |
| ------------- | ------ | ------------------------- |
| `sepallength` | Float  | Length of the sepal in cm |
| `sepalwidth`  | Float  | Width of the sepal in cm  |
| `petallength` | Float  | Length of the petal in cm |
| `petalwidth`  | Float  | Width of the petal in cm  |
| `class`       | String | Target Iris species       |

The target classes are:

- `Iris-setosa`
- `Iris-versicolor`
- `Iris-virginica`

---

## 📂 Project Structure

```text
Iris-Flower-Classification/
│
├── training_on_iris_flowerdataset.ipynb
├── irisflower_train.xlsx
├── irisflower_test.xlsx
├── README.md
└── .gitignore
```

---

## 📈 Model Evaluation

The Random Forest Classifier was evaluated on **34 test samples**.

It correctly predicted **33 out of 34 samples**.

### Accuracy

```text
Accuracy = (Correct Predictions / Total Test Samples) × 100

Accuracy = (33 / 34) × 100

Accuracy = 97.06%
```

**Final Test Accuracy: 97.06%**

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Krishnabhasin98/Iris-Flower-Classification.git
```

### 2. Open the project

```bash
cd Iris-Flower-Classification
```

### 3. Install dependencies

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
training_on_iris_flowerdataset.ipynb
```

## 📁 Dataset Files

The repository contains:

- `irisflower_train.xlsx` — Training dataset
- `irisflower_test.xlsx` — Testing dataset

---

## 🔮 Future Improvements

Possible improvements to the project include:

- Comparing Random Forest with other classification algorithms
- Performing more detailed model evaluation
- Adding confusion matrix visualization
- Hyperparameter tuning
- Building an interactive interface for predictions

---

## 👨‍💻 Author

**Krishna Bhasin**

GitHub: [Krishnabhasin98](https://github.com/Krishnabhasin98)

---

⭐ If you found this project useful, consider giving the repository a star.
