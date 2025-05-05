# Convex Project

This project implements and compares several optimization algorithms — including SGD, AdaGrad, RMSProp, and Adam — using manual implementations in PyTorch.

We analyze the convergence behavior of each optimizer on both:
- Synthetic objective functions (e.g., Quadratic, Rosenbrock, and Rastrigin)
- Image classification tasks (e.g., MNIST, Fashion-MNIST)

## 📁 Files

- `convex_project-3.py`: Main script containing optimizer implementations and experimental setup.

## ⚙️ Requirements

Make sure you have Python and the following libraries installed:

```bash
pip install torch torchvision matplotlib
