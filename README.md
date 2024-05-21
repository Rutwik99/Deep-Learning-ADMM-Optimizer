# ADMM as an Optimizer in Deep Learning

## Goal
This project explores the application of the Alternating Direction Method of Multipliers (ADMM) as an optimizer for deep learning models, comparing its performance with established methods such as Stochastic Gradient Descent (SGD) and Adaptive Moment Estimation (ADAM).

## Introduction
- The Alternating Direction Method of Multipliers (ADMM) is a powerful optimization technique that finds its significance in various domains, making it essential to understand its core principles. ADMM combines elements of gradient descent and dual decomposition and is widely employed to solve complex optimization problems, particularly those with constraints. It offers a versatile framework for handling both equality and inequality constraints, making it valuable for a range of applications.
- ADMM tries to combine the advantages of two methods, Dual Ascent and Augmented Lagrangian.
- ADMM (Alternating Direction Method of Multipliers) divides the problem into multiple subproblems that can be tackled in parallel, eliminating the vanishing gradient issue without the need for gradient steps. This subdivision also brings greater stability to the optimization process.

## Installation
To install the necessary dependencies, run:
```
pip install pytorch scikit-learn
```
To run the main script:
```
python main.py
```

## Conclusion

The ADMM optimizer demonstrates its potential in deep learning by providing stability and efficient constraint handling. Although it might not always outperform Adam and Adagrad, it offers a robust alternative for specific applications requiring effective constraint management.


