# Markov Decision Processes (MDPs)

## Overview
This project implements a flexible framework for simulating and analyzing **Markov Decision Processes (MDPs)**.  
It demonstrates classical algorithms such as **Value Iteration**, **Policy Iteration**, **Policy Evaluation**, and **Q-value Iteration** on multiple grid-based environments.

---

## Description
This project provides a practical and extensible environment for studying decision-making under uncertainty.  
It includes two main scenarios:

- **Slippery Tom & Jerry World:** a pursuit–avoidance problem where Tom tries to catch Jerry while avoiding Spike, with stochastic movement controlled by a slip probability.  
- **Customized Robot Navigation Problem:** a parameterized grid environment where a robot must reach a goal while avoiding obstacles.

An automatic generator produces random grid configurations and parameters, enabling repeated experiments with varying MDP setups.  
The framework serves educational and research purposes in reinforcement learning, stochastic control, and artificial intelligence decision systems.

---

## Algorithms Implemented
- Value Iteration  
- Policy Iteration  
- Policy Evaluation  
- Q-value Iteration  

---

## Requirements
- Python 3  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## Usage
```bash
git clone https://github.com/yourusername/MDPs.git
cd MDPs
pip install numpy matplotlib jupyter
jupyter notebook Copy_of_MDPs.ipynb
```
### Results

The notebook visualizes:

State transitions and reward propagation.

Policy evolution across iterations.

Comparison of algorithm convergence behaviors.

### Authors

**Mai Mohamed**

**Wessam Tamer**

Department of Communication and Information Engineering

Zewail City of Science and Technology
