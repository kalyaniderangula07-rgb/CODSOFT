# Movie Rating Prediction

## Project Overview

The Movie Rating Prediction project aims to build a machine learning model that can predict the rating of a movie based on its characteristics such as genre, director, and actors. By analyzing historical movie data, the model learns patterns and relationships between movie features and their ratings.

This project demonstrates the use of machine learning regression techniques to estimate movie ratings and understand the factors that influence audience and critic opinions.

---

## Objective

The primary objective of this project is to develop a machine learning model that predicts movie ratings using information related to the movie's genre, director, and cast members.

---

## Dataset Description

The dataset contains information about various movies, including:

* Movie Name
* Year of Release
* Duration
* Genre
* Rating (Target Variable)
* Votes
* Director
* Actor 1
* Actor 2
* Actor 3

Target Variable:

* Rating (Numerical value representing the movie's rating)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Methodology

### 1. Data Collection

The movie dataset was loaded into a Pandas DataFrame and examined to understand its structure, features, and available information.

### 2. Data Exploration

Initial analysis was performed to:

* Understand dataset dimensions.
* Examine data types.
* Identify missing values.
* Analyze rating distributions.
* Explore movie genres and other features.

### 3. Data Cleaning

Data preprocessing steps included:

* Handling missing values.
* Removing incomplete records where necessary.
* Selecting relevant features for prediction.
* Preparing the dataset for machine learning algorithms.

### 4. Exploratory Data Analysis (EDA)

Various visualizations were created to understand:

* Distribution of movie ratings.
* Most common movie genres.
* Relationships between different movie attributes.
* Trends present in the dataset.

### 5. Feature Engineering

Since machine learning models require numerical input:

* Categorical features such as Genre, Director, and Actors were transformed into numerical representations using One-Hot Encoding.
* Relevant features were selected for model training.

### 6. Data Splitting

The dataset was divided into:

* Training Set (80%)
* Testing Set (20%)

This ensures that the model is evaluated on unseen data.

### 7. Model Training

A Random Forest Regression model was trained using the processed dataset. The model learned patterns from historical movie information and corresponding ratings.

### 8. Prediction

After training, the model was used to predict ratings for movies in the testing dataset.

### 9. Model Evaluation

The model's performance was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics helped measure the accuracy and effectiveness of the prediction model.

---

## Results and Findings

The machine learning model successfully learned relationships between movie characteristics and ratings. The analysis showed that factors such as genre, director, and cast members contribute significantly to predicting movie ratings.

The model demonstrated good predictive performance and provided reliable rating estimates for unseen movies.

---

## Conclusion

In this project, a Movie Rating Prediction model was developed using machine learning techniques. The dataset was cleaned, preprocessed, and transformed into a suitable format for model training. A Random Forest Regression model was trained to predict movie ratings based on movie attributes such as genre, director, and actors.

The model was evaluated using standard regression metrics and demonstrated its ability to estimate ratings with reasonable accuracy. This project highlights the practical application of machine learning in the entertainment industry and shows how data can be used to predict audience preferences and movie success.

---

## Future Improvements

* Use larger and more diverse movie datasets.
* Experiment with advanced machine learning algorithms.
* Include additional features such as budget, revenue, and user reviews.
* Optimize model parameters for improved accuracy.
* Develop a web application for real-time movie rating prediction.

---


