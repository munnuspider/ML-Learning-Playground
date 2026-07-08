# ML-Learning-Playground
Everything I've learned so far regarding ML including my minor projects such as House Price Predictor and Iris species assignment. 

## Minor Project:
# Iris Assignment:
An end to end ML classification project that predicts the specific species of an Iris flower (Setosa, Versicolor and Virginia) based on its physical characteristics such as sepal length, sepal width, petal length and petal width.

Tech Stack and Key Features:
-EDA with seaborn and matplotlib to visualise key feature correlations and distinct species clusters.
-Used sci-kit learn to to train and compare multi-class classification algorithms using Logistic Regression.
-Preprocessing: Pipeline includes feature scaling with StandardScaler and train-test splitting to ensure robust evaluation without data leakage.

# House Price Predictor
A predictive regression project designed to estimate real estate market values. This model analyses residential housing data—factoring in critical variables like property size, location metrics, number of rooms, and build year—to accurately forecast house sale prices.

Tech Stack & Key Features:
-Feature Engineering: Handled missing data, managed multi-collinearity, and applied transformation techniques (like log transformations) to fix highly skewed numerical distributions.
-Encoding & Scaling: Implemented OneHotEncoding for categorical variables (neighborhoods, building types) and scaled features for optimal model performance.
-Model Pipeline: Built and tuned regression model (Linear Regression) using scikit-learn, evaluating success via Mean Absolute Error (MAE) and R2 scores.
