# 🌸 Iris Species Classification - Machine Learning Project

This project focuses on the classic **Iris dataset**, applying **data visualization** and **machine learning classification models** to predict the species of iris flowers based on flower measurements.

---

## 📂 Dataset Used

The dataset (`Iris.csv`) contains 150 rows with 5 key features:

- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species` (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)

- Visualized distribution of sepal/petal dimensions using histograms.
- Created scatter plots to observe relationships between dimensions.
- Used heatmaps to understand feature correlation.
- Checked for null values and class balance (each species has 50 samples).

---

## 📊 Data Preprocessing

- Encoded `Species` using `LabelEncoder` for ML modeling.
- Split data into training (70%) and testing (30%) sets using `train_test_split`.

---

## 🤖 Models Applied

Three different models were trained and tested:

| Model                  | Accuracy (%) |
|-----------------------|--------------|
| Logistic Regression   | 13.33        |
| K-Nearest Neighbors   | 31.11        |
| Decision Tree         | 88.88        |

All models provided digfferent performance on the test set.
Decision Tree as compare to others is the most accurate one.

---

## 🧰 Technologies & Libraries

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📌 Project Purpose

This project was built to:

- Understand the basic ML pipeline (EDA → Preprocessing → Model Training → Evaluation).
- Practice working with a popular dataset using visualization and classification techniques.


---

## ✨ Author

**Ahmad Rasool**  
Master's Student – Software Web & Cloud  
Tampere University


