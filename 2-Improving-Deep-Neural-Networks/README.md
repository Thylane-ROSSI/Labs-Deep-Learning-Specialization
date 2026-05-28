# Course 2: Improving Deep Neural Networks

This directory contains the core programming assignments for the second course of the specialization. These labs focus on practical techniques to improve the performance of deep learning models, covering weight initialization, regularization, optimization algorithms, and an introduction to the TensorFlow framework.

## Labs Overview

### 1. [Initialization](./Lab%201%20-%20Initialization.ipynb)
* **Objective:** Implement and compare different weight initialization methods for a new neural network to see how they impact the learning process.
* **Key Concepts:** Zero initialization, random initialization, He initialization, and the importance of breaking symmetry.

### 2. [Regularization](./Lab%202%20-%20Regularization.ipynb)
* **Objective:** Apply regularization techniques to deep learning models to address overfitting and ensure the network generalizes well to unseen data.
* **Key Concepts:** L2 Regularization, Dropout, and updating forward and backward propagation to include regularization terms.

### 3. [Gradient Checking](./Lab%203%20-%20Gradient_Checking.ipynb)
* **Objective:** Implement gradient checking to mathematically verify the accuracy of your backpropagation implementation.
* **Key Concepts:** 1-dimensional and N-dimensional gradient checking, numerical approximation of gradients, and computing relative differences.

### 4. [Optimization Methods](./Lab%204%20-%20Optimization_methods.ipynb)
* **Objective:** Use advanced optimization algorithms to accelerate the convergence of neural networks and reach a better minimum cost faster.
* **Key Concepts:** Mini-batch Gradient Descent, Momentum, RMSProp, Adam optimization, and learning rate decay scheduling.

### 5. [Introduction to TensorFlow](./Lab%205%20-Tensorflow_introduction.ipynb)
* **Objective:** Transition from pure NumPy implementations to a deep learning framework by building and training a neural network using TensorFlow 2.3.
* **Key Concepts:** Using `tf.Variable` to manage state, utilizing `tf.GradientTape` for automatic differentiation, and training on TensorFlow datasets.