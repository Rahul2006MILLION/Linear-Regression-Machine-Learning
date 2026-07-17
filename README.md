# Linear-Regression-Machine-Learning
Linear Regression from scratch using Python, NumPy, and Matplotlib. Implements the cost function, gradient descent, parameter optimization, convergence detection, and cost visualization without using Scikit-Learn to understand the fundamentals of Machine Learning.

# Linear Regression from Scratch using Gradient Descent

A beginner-friendly implementation of Linear Regression in Python without using machine learning libraries such as Scikit-Learn. This project demonstrates the complete training process by manually implementing the cost function, gradient computation, parameter updates, and convergence visualization using Gradient Descent.

## Features

- Built completely from scratch using Python and NumPy
- Manual implementation of the Linear Regression hypothesis
- Cost Function (Mean Squared Error)
- Gradient computation for both `w` and `b`
- Gradient Descent optimization
- Configurable learning rate (`alpha`)
- Adjustable number of training iterations
- Divergence detection when the cost increases
- Cost history tracking during training
- Cost vs. Iterations graph using Matplotlib

## Project Workflow

1. Define the training dataset.
2. Initialize parameters (`w` and `b`).
3. Compute predictions using:

   ŷ = wx + b

4. Calculate the Cost Function.
5. Compute gradients:
   - ∂J/∂w
   - ∂J/∂b
6. Update parameters using Gradient Descent.
7. Repeat until convergence.
8. Plot the cost reduction over iterations.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Learning Objectives

This project was created to understand the mathematics and programming behind Linear Regression rather than relying on high-level machine learning libraries. Every component of the algorithm is implemented manually to build a strong foundation in Machine Learning.

## Future Improvements

- Feature Scaling
- Multiple Linear Regression
- Polynomial Regression
- Vectorized Gradient Descent
- Real-world datasets
- Interactive visualizations

## Output

- Optimized values of `w` and `b`
- Final minimum cost
- Cost vs. Iterations convergence graph

---

This project is part of my Machine Learning learning journey, where every algorithm is implemented from scratch to gain a deep understanding of how machine learning works internally.
