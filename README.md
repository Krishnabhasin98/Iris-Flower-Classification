# 🌸 Iris Flower Classification

## Calculating and Analyzing the Accuracy of Iris Flower Dataset

A Machine Learning project that classifies Iris flowers using three different classification algorithms and analyzes their prediction accuracy.

---

## 📌 Project Overview

The project uses the Iris dataset to predict the species of a flower from four physical measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable is the flower class:

- `Iris-setosa`
- `Iris-versicolor`
- `Iris-virginica`

The project also includes data exploration and visualizations before training the Machine Learning models.

---

## 📊 Dataset Information

The dataset contains:

- **150 samples**
- **5 columns**
- **4 numerical input features**
- **1 target class column**
- **No missing values**

| Column | Description |
|---|---|
| `Sepal.Length` | Length of the sepal |
| `Sepal.Width` | Width of the sepal |
| `Petal.Length` | Length of the petal |
| `Petal.Width` | Width of the petal |
| `class` | Iris flower species |

---

## 📈 Data Visualizations

### 1. Class Distribution

A count plot is used to visualize the distribution of the three Iris flower classes.

### 2. Violin Plots

Violin plots are used to visualize the distribution of:

- Petal Length
- Petal Width
- Sepal Length
- Sepal Width

across the different flower classes.

These visualizations help analyze how the physical characteristics vary between Iris species.

---

## 🔄 Machine Learning Workflow

```text
Iris Dataset
      ↓
Data Loading
      ↓
Data Exploration
      ↓
Data Visualization
      ↓
Feature and Target Selection
      ↓
Train-Test Split
      ↓
Train Machine Learning Models
      ↓
Generate Predictions
      ↓
Calculate Accuracy
      ↓
Compare Model Performance
```

---

## 🧪 Train-Test Split

The dataset is divided using an **80/20 split**:

```text
Total Samples:    150
Training Samples: 120
Testing Samples:   30

Training Features: (120, 4)
Testing Features:   (30, 4)
```

The split uses:

```python
train_test_split(data, test_size=0.2, random_state=42)
```

---

## 🤖 Machine Learning Models

Three classification algorithms are trained and evaluated.

### 🌲 Random Forest Classifier
### 📊 Gaussian Naive Bayes
### 🌳 Decision Tree Classifier


## 🏆 Model Accuracy Results

All three models are evaluated using the same 30-sample test dataset.

| Model | Test Accuracy |
|---|---:|
| 🌲 Random Forest Classifier | **100.0%** |
| 📊 Gaussian Naive Bayes | **100.0%** |
| 🌳 Decision Tree Classifier | **100.0%** |

For this particular train-test split, all three models correctly classified all **30 out of 30** test samples.

> **Note:** Model accuracy can change with a different train-test split because different samples may be selected for testing.

---

## 🔮 Sample Prediction

The Random Forest model is also used to predict the species of a new flower:

```python
model1.predict([[5.4, 3, 4.5, 1.5]])
```

### Prediction Result

```text
Iris-versicolor
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```text
Iris-Flower-Classification/
│
├── training_on_iris_flowerdataset.ipynb
├── iris_main.csv
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Krishnabhasin98/Iris-Flower-Classification.git
```

### 2. Open the project folder

```bash
cd Iris-Flower-Classification
```

### 3. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

```text
training_on_iris_flowerdataset.ipynb
```

Run all cells from top to bottom.


---

## 👨‍💻 Author

**Krishna Bhasin**

GitHub: https://github.com/Krishnabhasin98

---

⭐ If you found this project useful, consider giving the repository a star!
