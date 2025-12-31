# Healthcare Cost Prediction Using Linear Regression

This is a simple machine learning project where I built a model to predict healthcare costs using linear regression. The goal was to learn how regression works with real-world data and to follow a full ML workflow — from loading the dataset to training a model and checking its performance.

In this project, I used a dataset with features like age, BMI, smoking status, etc., and tried to predict the insurance charges for each person. The challenge was to get the model to perform reasonably well (mean absolute error below a threshold), and in the process I learned a lot about preprocessing, modeling, and evaluation.

---

## Project Summary

This project uses **linear regression** to build a model that predicts medical insurance costs based on patient data. The dataset has several features, including:

- **age** – Age of the person  
- **sex** – Gender  
- **bmi** – Body mass index  
- **children** – Number of dependents  
- **smoker** – Whether the person smokes  
- **region** – Location area  
- **charges** – Insurance cost (target variable)

The final model’s performance is evaluated using **Mean Absolute Error (MAE)** and must have an MAE less than **3500** to pass the challenge. :contentReference[oaicite:0]{index=0}

---

## What You’ll Find Here

This repo contains:

- A notebook with the full implementation
- Visualizations and evaluation metrics
- Instructions on how to run the code

---

## What I Did

Here’s a quick breakdown of the steps:

### 1. Loaded the Data
Loaded the dataset (CSV) into a Pandas DataFrame and inspected it for missing values and overall structure.

### 2. Data Preprocessing
Converted categorical features (like `sex`, `smoker`, `region`) into numeric format using techniques like `pd.get_dummies()` so the model can work with them.

### 3. Train-Test Split
Split the data into a training set and a testing set so we can evaluate the model on unseen data.

### 4. Built the Model
Built a simple **Linear Regression** model using TensorFlow/Keras or scikit-learn (depending on implementation) to learn the relationships between features and costs.

### 5. Trained the Model
Trained the model on the training data.

### 6. Evaluated the Model
Used the testing data to check how well the model can predict costs compared to actual values, and calculated MAE.

## How to Run This Project

This project was developed and tested using Google Colab.

### Steps:
1. Open the notebook file in Jupyter Notebook or Google Colab.
2. Run the cells in order from top to bottom.
3. The model will train automatically and print the evaluation metrics at the end.
