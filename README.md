# Student Grade Prediction: Linear Regression Model 

## Overview
Welcome to the Student Grade Prediction repository. This repository contains a robust linear regression model built with the purpose of predicting student grades based on a variety of relevant factors. 

## Dataset
The model is trained using a dataset that comprises of several factors that might impact a student's final grade including weekly study time, number of past class failures, number of school absences and more. The 'G3' column, which the model will predict, represents the final grade of the student on a scale of 0-20.

You can find the data source at [Student Performance - UCI](https://archive.ics.uci.edu/dataset/320/student+performance).

## Model
The Linear Regression model provided here is implemented using Python via the Scikit-learn library. It takes advantage of the linear relationship between the attributes and the grade in order to predict grades of future students. 

## Files
1. `linear_regression.ipynb`: This Jupyter notebook contains the code for implementing the Linear Regression model, as well as the exploratory data analysis of the dataset.
2. `student-mat.csv`: This contains the dataset used to train and test the machine-learning model.

## Getting Started
You need Python 3.x and the following libraries installed to run the notebook:
- numpy
- pandas
- matplotlib
- pickle
- scikit-learn

Clone this repo to your local machine and you can run the Jupyter notebook from the terminal.

```bash
git clone https://github.com/<user>/<repo>.git
cd <repo>
jupyter notebook linear_regression.ipynb
```

## Contribution
Kindly feel free to contribute to improve the model or data exploratory analysis. If there are any issues or if you want to start a discussion, feel free to open an issue or start a pull request.