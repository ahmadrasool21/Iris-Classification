## 🌸 Iris Species Classification - Machine Learning Project

This project focuses on the classic Iris dataset, applying data visualization and machine learning classification models to predict the species of iris flowers based on flower measurements.

## 📂 Dataset Used

The dataset (Iris.csv) contains 150 rows with 5 key features:

SepalLengthCm
SepalWidthCm
PetalLengthCm
PetalWidthCm
Species (target variable)
## 🔍 Exploratory Data Analysis (EDA)
Visualized distribution of sepal/petal dimensions using histograms.
Created scatter plots to observe relationships between features.
Used heatmaps to analyze feature correlations.
Verified there are no missing values.
Confirmed balanced dataset (each species has 50 samples).
## 📊 Data Preprocessing
Correctly encoded Species using LabelEncoder (target variable).
Separated features (X) and target (y).
Split dataset into training (70%) and testing (30%) sets using train_test_split.
## 🤖 Models Applied

Three classification models were trained and evaluated:

Model	Accuracy (%)
Logistic Regression	~93.33
K-Nearest Neighbors	~95.56
Decision Tree	~95.56

👉 KNN and Decision Tree achieved the highest accuracy, showing strong performance due to clear feature separability in the dataset.

## 📈 Key Insights
PetalLengthCm and PetalWidthCm are the most important features for classification.
Iris-setosa is easily separable, while the other two species are slightly overlapping.
Proper label encoding of the target variable is crucial for correct model performance.
Model comparison helps identify the most suitable algorithm for the dataset.
## 🧰 Technologies & Libraries
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
## 📌 Project Purpose

This project was built to:

Understand the complete machine learning pipeline (EDA → Preprocessing → Model Training → Evaluation).
Compare different classification algorithms on the same dataset.
Learn the importance of correct data preprocessing and feature analysis.
## ✨ Author

Ahmad Rasool
Master's Student – Software Web & Cloud
Tampere University
