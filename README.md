# MNIST Digit Classifier — Neural Network from Scratch

A 2-layer neural network (784 → 64 → 10) built using **only NumPy** — no PyTorch, no TensorFlow.
Every component — forward propagation, backpropagation, and gradient descent — is implemented
manually from the underlying math, to build a first-principles understanding of how neural
networks actually learn.

## Architecture

Input (784) → Hidden (64, ReLU) → Output (10, Softmax)

## Training

- Optimizer: batch gradient descent (no momentum/Adam, by design — keeps the math visible)
- Learning rate: 0.3
- Iterations: 5000
- Validation accuracy: **[fill in your number]%**

## What's in the notebook

- Data loading and preprocessing (MNIST, normalized to [0,1])
- Manual forward and backward propagation with math explained in Markdown
- Training accuracy curve
- Sample predictions with correct/incorrect highlighted
- Interactive drawing widget to test the model live (Colab canvas)

## Run it

Open `MNIST_NN.ipynb` in Google Colab. Requires a MNIST CSV dataset (label in column 0, followed
by 784 pixel columns).
