
# information-bottleneck - Independent Research in Probabilistic Deep Learning

This repository documents my self-directed research projects focused on the intersection of stochastic processes, Bayesian methods, and the theoretical foundations of deep learning optimization.

## Primary Research Interests

1.  **Stochastic Processes and Optimization:** Investigating the use of stochastic dynamics and principles from statistical physics (e.g., Langevin Dynamics) to enhance machine learning optimization. Research focuses on designing robust algorithms for Minimax Games.
2.  **Probabilistic Modeling and Uncertainty Quantification (UQ):** Developing and applying Bayesian Neural Networks (BNNs) and other probabilistic models to quantify model reliability. Research includes accurately measuring and visualizing epistemic uncertainty.
3.  **Information Theory and Generalization Dynamics:** Exploring the theoretical foundations of deep learning through the lens of information. Focusing on concepts like the Information Bottleneck (IB) Principle and analyzing how the dynamics of training affect generalization.

## Current Projects


### 2. Information Bottleneck Trajectory Analysis

**Project: Information Bottleneck Trajectory Analysis**

* **Goal:** To empirically explore the theoretical link between stochastic optimization and model generalization using the Information Bottleneck (IB) principle.
* **Methodology:** Implemented a computational experiment to track the **Information Bottleneck trajectory** (plotting $I(X;T)$ vs. $I(T;Y)$) for both standard and stochastic neural networks.
* **Key Finding:** Demonstrated that noise injection (Stochastic Gradient Langevin Dynamics) promotes the **compression phase** of learning, suggesting a mechanism for improved generalization in Bayesian/stochastic models.
* **Source File:** `Information_Bottleneck.ipynb`


