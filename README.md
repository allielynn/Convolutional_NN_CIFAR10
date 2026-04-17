# Convolutional Neural Networks on CIFAR10

## Approach:
- Inspired by established literature on convolutional neural networks for image classification, we explored advanced methods such as DARTS, Neural Architecture Search (NAS), and Bayesian Optimization, while prioritizing computational efficiency.
- Structured the methodology into two stages: architecture design and hyperparameter tuning. We first evaluated a subset of architectural components to identify the most effective network structure, then optimized its hyperparameters to produce the best-performing model for evaluation on test data.

## Findings:
- Designed and optimized convolutional neural networks for CIFAR-10 image classification by implementing Neural Architecture Search (NAS) and Differentiable Architecture Search (DARTS), achieving up to 85% validation accuracy and 81.1% test accuracy.
- Applied Bayesian Optimization to tune hyperparameters (learning rate, batch size, optimizer), improving training stability and generalization, while evaluating trade-offs between model performance and computational cost using GPU-based experiments.
