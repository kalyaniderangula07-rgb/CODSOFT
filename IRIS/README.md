# Iris Flower Classification

A machine learning project that classifies Iris flowers into three species (*Setosa*, *Versicolor*, and *Virginica*) based on their sepal and petal measurements.

## 📌 Project Overview
The goal of this project is to build a predictive model that can accurately identify the species of an Iris flower given its physical dimensions. This is a classic supervised learning problem used to demonstrate data exploration, model training, and evaluation.

## 📊 Dataset Description
The Iris dataset contains **150 samples** (50 for each of the three species) with 4 features:
* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

**Observation:** Exploratory Data Analysis (EDA) showed that *Iris-setosa* is linearly separable and distinctly clustered away from the other two species, while *Iris-versicolor* and *Iris-virginica* share a slight overlap in their measurements.

## ⚙️ Methodology & Workflow
1. **Data Preprocessing:** Loaded the dataset and split it into training and testing sets (e.g., 80% train, 20% test).
2. **Model Training:** Trained a classification algorithm (e.g., Logistic Regression / Decision Tree / KNN) on the training features.
3. **Evaluation:** Evaluated the model's performance on the unseen test data.

## 📈 Results & Performance
The model successfully learned the botanical patterns and achieved high accuracy on the test set.

* **Test Accuracy:** ~95% - 98% (Replace with your exact score, e.g., 96.67%)
* **Key Takeaway:** Petal length and petal width were identified as the most crucial features for accurately distinguishing between the species.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib/Seaborn
