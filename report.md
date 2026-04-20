# Report: Self-Pruning Neural Network

## Why L1 Encourages Sparsity
L1 regularization pushes gate values toward zero. Since gates multiply weights,
this results in many weights becoming effectively zero (pruned).

## Results

| Lambda | Accuracy | Sparsity |
|--------|---------|----------|
| 1e-5   | 46.87%     | 1.13%      |
| 1e-4   | 46.24%     | 1.55%      |
| 1e-3   | 42.05%     | 1.71%      |

# Observations
- Lower lambda → better accuracy, less pruning
- Higher lambda → more pruning, lower accuracy
- Shows clear trade-off

# Gate Distribution
       