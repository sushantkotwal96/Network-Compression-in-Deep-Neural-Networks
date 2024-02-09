#  Network Compression in Deep Neural Networks Using Singular Value Decomposition (SVD)

## Overview

Welcome to the world of deep learning model compression! In this project, we delve into the fascinating realm of network compression techniques, with a special focus on leveraging Singular Value Decomposition (SVD) to achieve compact yet powerful neural networks. As a candidate passionate about data science, machine learning, and deep learning engineering, this project showcases my expertise in innovative model optimization strategies.

### Understanding Network Compression and SVD

#### Network Compression:
In the era of big data and resource limitations, the quest for efficient neural networks has never been more critical. Network compression techniques aim to reduce the size and computational complexity of deep neural networks without sacrificing performance. By pruning redundant parameters, structures, or connections, compressed networks offer streamlined models that are more efficient for deployment on resource-constrained devices.

#### Singular Value Decomposition (SVD):
SVD is a fundamental matrix factorization technique widely used across various domains, including deep learning. It decomposes a matrix into three constituent matrices: U, Σ, and Vᵀ, where U and V are orthogonal matrices, and Σ is a diagonal matrix containing the singular values. In the context of deep learning, SVD offers a powerful tool for compressing weight matrices by approximating them with low-rank representations. By retaining only the most significant singular values, SVD enables substantial reduction in model size while preserving crucial information for accurate inference.

## Project Objectives

This project is structured around three main problems, each exploring different aspects of network compression using SVD:

### Problem 1: Network Compression Using SVD
- Trained a baseline fully-connected neural network for MNIST classification.
- Applied SVD to weight matrices to achieve compression.
- Experimented with varying levels of compression by adjusting the number of singular values (D).
- Evaluated the performance of compressed networks and compare against baseline accuracy.

### Problem 2: Network Compression Using SVD (Factorization)
- Explored a novel approach to compression by factorizing weight matrices.
- Initialized factor matrices using results from Problem 1 (D = 20 case).
- Fine-tuned the network to improve performance while maintaining compression benefits.

### Problem 3: Network Compression Using SVD (Dynamic SVD)
- Implemented dynamic SVD, performing SVD at every epoch to inform training.
- Utilized SVD approximation function during feedforward and backpropagation.
- Updated weights considering the additional error introduced by compression.
- Custom derivative of SVD approximation function is defined to facilitate backpropagation.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies as specified in the requirements.txt file.
3. Run the provided scripts or notebooks to train and evaluate network compression using SVD.
4. Explore the results and experiment with different parameters to deepen your understanding.

## Acknowledgement

This project would like to thank the developers of TensorFlow, for providing the tools and libraries for Network Compression that made this project possible
## Licenses

This project is licensed under the [insert license type, e.g., MIT License]. For more information, please refer to the LICENSE.md file.

