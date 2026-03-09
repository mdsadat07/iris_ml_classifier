# Iris Flower Classification using Python

This is a simple machine learning project built in Python using the famous Iris dataset.  
The model predicts the type of iris flower based on four flower measurements.

## Project Overview

The model uses:

- Sepal length
- Sepal width
- Petal length
- Petal width

It predicts one of the following flower types:

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Google Colab

## Dataset

This project uses the built-in IRIS dataset from `sklearn.datasets`.

It contains 150 flower samples with measurements and labels for 3 species of iris flowers.

## Machine Learning Workflow

The project follows these steps:

1. Load the Iris dataset
2. Split the data into training and testing sets
3. Train a Decision Tree Classifier
4. Make predictions on test data
5. Evaluate model accuracy
6. Predict a custom flower sample

## Example Prediction

Custom input used:

```python
my_flower = [[6.5, 3.0, 6.0, 2.2]]
