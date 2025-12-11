
# information-bottleneck - Independent Research in Probabilistic Deep Learning

This repository documents my self-directed research projects focused on the intersection of stochastic processes, Bayesian methods, and the theoretical foundations of deep learning optimization.

For this repository, I introduce : 

### Information Bottleneck Trajectory Analysis

**Project: Information Bottleneck Trajectory Analysis**

* **Goal:** To empirically explore the theoretical link between stochastic optimization and model generalization using the Information Bottleneck (IB) principle.
* **Methodology:** Implemented a computational experiment to track the **Information Bottleneck trajectory** (plotting $I(X;T)$ vs. $I(T;Y)$) for both standard and stochastic neural networks.
* **Key Finding:** Demonstrated that noise injection (Stochastic Gradient Langevin Dynamics) promotes the **compression phase** of learning, suggesting a mechanism for improved generalization in Bayesian/stochastic models.
* **Source File:** `Information_Bottleneck.ipynb`


