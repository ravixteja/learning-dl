# Intro to Deep Learning with Python and Music Generation with RNNs

## Part 1: Intro to Deep Learning in Python - using PyTorch (PT_intro.ipynb)

### Overview

This Jupyter Notebook introduces the basics of PyTorch, a popular deep learning framework. It covers fundamental concepts such as tensor operations, computation graphs, a simple neural network construction, and training using backpropagation.

### Contents

- **1.1 What is Pytorch?**  
  - Brief overview of PyTorch and its main features.
  - Creating tensors of various dimensions (1D, 2D, 3D, 4D)
  - Initializing tensors with zeros
  - Slicing and accessing subtensors
  
- **1.2 Computation on Tensors:**  
  - Performing mathematical operations (addition, subtraction, multiplication)
  - Visualizing computation graphs

- **1.3 Neural Networks in PyTorch:**  
  - Defining custom layers using `nn.Module`
  - Using the Sequential API for simple feed-forward networks
  - Subclassing `nn.Module` for flexible architectures
  - Implementing custom behaviors in networks

- **1.4 Training the Network with Backpropagation:**  
  - Using `torch.autograd` for automatic differentiation
  - Computing gradients
  - Implementing gradient descent to minimize a loss function

### Usage

1. **Install PyTorch:**  
   Follow instructions at [PyTorch Get Started](https://pytorch.org/get-started/locally/).

2. **Run Notebook:**  
   Open `PT_intro.ipynb` in Jupyter Notebook or VS Code and execute cells sequentially.

3. **Explore:**  
   Modify code cells to experiment with tensor operations and neural network architectures.

### Requirements

- Python 3.x
- PyTorch
- NumPy
- Matplotlib

### Learning Outcomes

- Understand how to create and manipulate tensors in PyTorch.
- Learn how to build and train simple neural networks.
- Gain hands-on experience with automatic differentiation and optimization.

---