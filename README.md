# task6
# 🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset

This project is part of an AI & ML Internship task focused on understanding and implementing the **K-Nearest Neighbors (KNN)** algorithm for classification problems using the **Iris dataset**.

---

## 📌 Task Objectives

- Load and explore a classification dataset
- Normalize features for distance-based learning
- Train and evaluate a KNN model using `scikit-learn`
- Experiment with different values of `K`
- Visualize decision boundaries in 2D

---

## 📂 Dataset

**Source**: [Iris Dataset from UCI via GitHub](https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv)  
- 150 samples
- 4 features: sepal length, sepal width, petal length, petal width
- 3 classes: Setosa, Versicolor, Virginica

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📊 Steps Performed

1. **Load dataset** from a public URL
2. **Encode class labels** using `LabelEncoder`
3. **Split** into training and test sets (80:20)
4. **Standardize** features using `StandardScaler`
5. **Train KNN** model using `KNeighborsClassifier`
6. **Test with different K values** (1 to 10) and evaluate accuracy
7. **Generate confusion matrix** for best K
8. **Visualize decision boundaries** in 2D (using 2 selected features)

---

## 🔍 Model Evaluation

- **Accuracy** is computed for each value of `K`
- **Confusion matrix** visualizes correct and incorrect classifications
- Best `K` found to be **3** in this implementation


### ✅ Accuracy per K

| K | Accuracy |
|---|----------|
| 1 | 1.00     |
| 2 | 0.97     |
| 3 | 1.00     |
| 4 | 1.00     |
| 5 | 1.00     |
| 6 | 1.00     |
| 7 | 1.00     |
| 8 | 1.00     |
| 9 | 1.00     |
| 10| 1.00     |

> **K = 3** was chosen for detailed evaluation.

---

### 🧾 Confusion Matrix (K = 3)

---

## 📉 Decision Boundary

To visualize decision regions, a 2D subset (`sepal_length` and `sepal_width`) was used. The KNN model was trained and plotted to show how it separates the three flower species in feature space.

![image](https://github.com/user-attachments/assets/d6ee2862-37d8-424b-af65-e82a8f1ce5f1)



---

## 🧠 Key Learnings

- KNN is a **distance-based, instance-based** learning algorithm.
- **Normalization** is critical to ensure fair distance calculations.
- Choosing the right **value of K** is crucial — try multiple K values and use validation data.
- Visualizing decision boundaries helps understand how the model separates classes.

---


