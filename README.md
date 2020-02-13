# Data Clustering With QAOA

The Quantum Approximate Optimization Algorithm (QAOA) is one of the most promising hybrid quantum machine learning algorithms that focuses on solving combinatiorial optimization problems, and hopes to provide speed up over it's classical counterparts in the near term. 

In this repo, we decided to focus on using QAOA solving the Maximum Cut problem, which subsequentially clustered data into two seperate groups. Our implementation was derived from this paper, originally written by Leo Zhou and Sheng-Tao Wang et al. : https://arxiv.org/pdf/1812.01041.pdf


## 1. Problem Statement
(fill out here)

## 2. How QAOA solves this.
The Quantum Approximate Optimization Algorithm doesn't actually solve for the max value, but instead *approximates* it (hence the creative name). Although there are many classical algorithms that can do this already, QAOA has the potential to show speed ups over the classical algorithms as the circuit depth, p -> ∞ . At this point in time, the best performance we've achieved with the QAOA algorithm is at depth p = 1, so there is still much more exploring to do.





