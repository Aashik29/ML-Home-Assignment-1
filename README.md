Homework 1 — CS5710 Machine Learning (Fall 2025)

University of Central Missouri
Department of Computer Science & Cybersecurity
Course: CS5710 Machine Learning
Assignment: Homework 1
Semester: Fall 2025

📌 Student Information

Name: Aashik Shaik

Course ID: CS5710

Assignment: Homework 1

Assignment Overview

This assignment focuses on understanding fundamental concepts in linear regression, model fitting, gradient descent optimization, and the bias-variance tradeoff. It combines both hand-calculated problems and a programming exercise.

The tasks include:

Function Approximation by Hand

Compute predictions, residuals, squared residuals, and MSE for two models.

Compare which model fits the dataset better.

Random Guessing Practice

Evaluate cost values for given parameter guesses.

Discuss why random guessing is inefficient compared to systematic optimization.

Gradient Descent Iteration

Perform one iteration of gradient descent on a small dataset.

Show initial vs updated parameter values and cost reduction.

Random Guessing vs Gradient Descent

Compare performance of random guesses with a single gradient descent step.

Highlight the advantages and limitations of each.

Recognizing Underfitting and Overfitting

Interpret learning curves and identify underfitting vs overfitting.

Propose strategies to mitigate underfitting.

Comparing Models

Diagnose Model A (overfitting) and Model B (underfitting).

Suggest solutions to improve generalization and performance.

Programming Task — Linear Regression

Implement linear regression with both closed-form solution (Normal Equation) and gradient descent.

Plot the raw dataset, fitted lines, and gradient descent loss curve.

Compare results from both methods.

🛠️ Implementation

The programming portion (Problem 7) is implemented in Python using:

NumPy (matrix operations, gradient descent updates)

Matplotlib (data visualization, fitted lines, and loss curve plots)

Two approaches were used:

Closed-form solution (Normal Equation)

Directly solves for parameters using matrix inversion.

Gradient Descent

Iteratively updates parameters to minimize MSE.

Plotted convergence curve of loss vs iterations.

📂 Repository Structure
Homework1/
│── linear_regression_gd.py    # Python script for Problem 7
│── Homework 1.docx            # Assignment questions
│── README.md                  # This file
│── results/                   # (Optional) Plots and screenshots of outputs

Ensure dependencies are installed:

pip install numpy matplotlib


Run the Python script:

python linear_regression_gd.py


The script will:

Print closed-form and gradient descent parameter estimates.

Plot fitted regression lines against the dataset.

Show the gradient descent loss curve.

🎯 Results & Discussion

Both closed-form solution and gradient descent converge to nearly identical parameter values.

Gradient descent shows smooth convergence of loss towards the closed-form optimum.

Demonstrates how iterative optimization can match analytic solutions.
