# 🌸 Multi-Class Classification Benchmark — Iris Dataset

A beginner-friendly machine learning project that implements and compares **Logistic Regression** and **Decision Tree** classifiers on the Iris dataset using Scikit-Learn. The project covers the complete supervised learning workflow, including data exploration, feature scaling, model training, evaluation metrics, and confusion matrix visualization.

---

## 🎯 Objective

Build an end-to-end multiclass classification pipeline to predict Iris flower species based on their physical measurements and benchmark the performance of two machine learning algorithms.

---

## 📊 Dataset

The project uses the built-in **Iris dataset** provided by Scikit-Learn.

* **Total samples:** 150
* **Features:** 4 numerical features
* **Classes:** 3
* **Class distribution:** 50 samples per species

### Features

| Feature      | Description               |
| ------------ | ------------------------- |
| Sepal Length | Length of the sepal in cm |
| Sepal Width  | Width of the sepal in cm  |
| Petal Length | Length of the petal in cm |
| Petal Width  | Width of the petal in cm  |

### Target Classes

* Setosa
* Versicolor
* Virginica

---

## ⚙️ ML Workflow

The project follows a standard machine learning pipeline:

1. Load the Iris dataset.
2. Perform exploratory data analysis (EDA).
3. Separate features (`X`) and target (`y`).
4. Split data into training and testing sets (80/20).
5. Standardize features using `StandardScaler`.
6. Train Logistic Regression.
7. Train Decision Tree Classifier.
8. Generate predictions.
9. Evaluate models using Accuracy, Precision, Recall, and F1-score.
10. Visualize performance using confusion matrices.
11. Compare both models.

---

## 🤖 Models Implemented

### 1. Logistic Regression

A supervised classification algorithm that estimates class probabilities and predicts the most likely class.

Feature scaling was applied using `StandardScaler` before training.

### 2. Decision Tree Classifier

A tree-based supervised learning algorithm that learns decision rules by splitting the dataset based on feature values.

Feature scaling is not required for the Decision Tree model.

---

## 📈 Model Performance

Both models achieved the same results on the test dataset.

| Metric             | Logistic Regression | Decision Tree |
| ------------------ | ------------------: | ------------: |
| Accuracy           |              93.33% |        93.33% |
| Weighted Precision |              93.33% |        93.33% |
| Weighted Recall    |              93.33% |        93.33% |
| Weighted F1-score  |              93.33% |        93.33% |

**Test samples:** 30
**Correct predictions:** 28
**Incorrect predictions:** 2

---

## 🔍 Confusion Matrix Analysis

The Logistic Regression model correctly classified:

* **Setosa:** 10/10
* **Versicolor:** 9/10
* **Virginica:** 9/10

Two misclassifications occurred:

* 1 Versicolor was predicted as Virginica.
* 1 Virginica was predicted as Versicolor.

Both models achieved **93.33% accuracy** on the selected test set.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📚 Key Concepts Learned

* Exploratory Data Analysis (EDA)
* Feature-target separation
* Train-test splitting
* Data standardization
* Supervised machine learning
* Multiclass classification
* Logistic Regression
* Decision Tree Classification
* Model prediction
* Accuracy, Precision, Recall, and F1-score
* Confusion Matrix
* Model benchmarking

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Navigate to the project directory

```bash
cd Iris-MultiClass-Classification
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open `Iris_MultiClass_Classification_Benchmark.ipynb` and execute the cells sequentially.

---

## 📁 Project Structure

```text
Iris-MultiClass-Classification/
│
├── Iris_MultiClass_Classification_Benchmark.ipynb
├── README.md
└── requirements.txt
```

---

## 📝 Conclusion

This project demonstrates a complete supervised machine learning workflow using a multiclass classification problem. Logistic Regression and Decision Tree models were trained and evaluated using the same dataset and test split.

Both models achieved 93.33% accuracy, demonstrating strong performance on this test set. This project helped build a foundational understanding of data preprocessing, feature scaling, model training, and evaluation techniques used in practical machine learning applications.

---

## 👨‍💻 Author

**Abhay Solanke**

Machine Learning | Artificial Intelligence | Data Science

---

⭐ If you found this project interesting, feel free to explore the notebook.
