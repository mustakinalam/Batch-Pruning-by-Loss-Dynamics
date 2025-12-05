# Loss-Dynamics-Based Batch Pruning Experiments

This repository contains a Jupyter notebook implementing **loss-dynamics-based batch pruning** for CNN training. The notebook includes a series of experiments demonstrating how batch pruning can reduce training time while maintaining accuracy.

## Contents

1. **Delta Tuning Experiments:**  
   - Three empirical experiments on CIFAR-10 using ResNet-18.  
   - Purpose: to tune the pruning threshold (`delta`) values for effective batch pruning.

2. **Pruning Experiments:**  
   - Training ResNet-18 on CIFAR-10, CIFAR-100, and SVHN.  
   - Comparison of training **with and without batch pruning** to evaluate efficiency and accuracy gains.

## Requirements

- Python 3.8+  
- PyTorch  
- torchvision  
- NumPy, Matplotlib, Pandas, thop, sns

## Usage

Open the notebook and run the cells sequentially to reproduce the experiments.  

