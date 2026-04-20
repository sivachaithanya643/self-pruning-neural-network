# Self-Pruning Neural Network

This project implements a neural network that learns to prune its own weights during training using learnable gates.

## Key Features
- Custom PrunableLinear layer
- L1 sparsity regularization
- Dynamic pruning during training
- CIFAR-10 classification

## Results

| Lambda | Accuracy | Sparsity |
|--------|---------|----------|
| 1e-5   | 46.87%     | 1.13%      |
| 1e-4   | 46.24%     | 1.55%      |
| 1e-3   | 42.05%     | 1.71%      |

# How to Run
Open the notebook in Google Colab and run all cells.

# Author
Krishnam Bharath