# Neural Network from Scratch

This project implements a **neural network built entirely from scratch in Python**, without relying on high-level deep learning frameworks like TensorFlow or PyTorch. The goal is to understand the **core mechanics** behind forward propagation, backpropagation, and gradient descent.

---

## 📌 Features

* Implementation of a custom `Value` class for **automatic differentiation** (like micrograd).
* Support for common operations: `+`, `-`, `*`, `/`, `**`, `tanh`, `exp`.
* **Backpropagation engine** using a topological sort of the computation graph.
* Visualization of the computation graph using **Graphviz**.
* Step-by-step construction of:

  * A **Neuron** class
  * A **Layer** class
  * A **Multi-Layer Perceptron (MLP)**
* Training loop using **gradient descent** on a small dataset.
* Comparison with **PyTorch autograd** to validate gradients.

---

## 🛠️ Installation

Clone this repository:

```bash
git clone https://github.com/your-username/neural-net-from-scratch.git
cd neural-net-from-scratch
```

## ▶️ Usage

Run the script to execute training:

```bash
python neural_net_training.py
```

This will:

1. Define the computation graph.
2. Train a small MLP on a toy dataset.
3. Print loss values during training.
4. Output predictions at the end.

---


## 📖 Learning Goals

This project is meant for **educational purposes**:

* Demystify how autograd engines like PyTorch work internally.
* Learn how forward pass and backpropagation are implemented at a low level.
* See how simple building blocks (neurons) can be composed into deep networks.

---

## 📈 Next Steps

* Add support for more activation functions (ReLU, sigmoid).
* Implement mini-batch training.
* Extend to more complex datasets (e.g., MNIST).
* Compare training speed and accuracy with PyTorch.

---

