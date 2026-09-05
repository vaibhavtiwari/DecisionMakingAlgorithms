# Control-to-RL: Algorithm Learning Through Implementation

## Objective

This project is an implementation-focused companion to the **Stanford AA203: Optimal and Learning-Based Control** lectures.

The goal is to build practical intuition for the progression from **optimal control to reinforcement learning**, while focusing on two questions:

1. **Problem formulation — What problem should we solve?**
2. **Algorithm — How do we solve it?**

A key focus is learning how to translate a physical or behavioral requirement into a mathematical problem:

```text
Requirement
    ↓
States & Controls
    ↓
Dynamics
    ↓
Cost / Reward
    ↓
Constraints
    ↓
Optimization / Learning Problem
```

## Approach

Each notebook contains only the theory needed to understand and implement the main idea:

- Intuition and assumptions
- Essential mathematical formulation
- Core algorithm
- Implementation
- Small experiments and visualizations
- Short takeaway

Important algorithmic components are implemented explicitly, while **JAX**, **PyTorch**, and standard numerical tools are used where appropriate.

Simple environments are used to keep the focus on the algorithms. A **2D kinematic car model** and **highway-env** are used for selected control and decision-making experiments.

## Roadmap

The notebooks follow the progression:

```text
Open-Loop Optimal Control
        ↓
Indirect & Direct Methods
        ↓
Dynamic Programming
        ↓
LQR / iLQR / DDP
        ↓
HJB / HJI
        ↓
MPC
        ↓
System Identification & Adaptive Control
        ↓
Imitation Learning
        ↓
RL Foundations
        ↓
Value-Based RL
        ↓
Policy Gradients & Actor-Critic
        ↓
PPO
        ↓
Model-Based RL
```

The emphasis is not on implementing as many algorithms as possible, but on understanding **how problem formulation, optimization, learning, and system behavior are connected**.

> **Guiding principle:** Environment complexity should never exceed what is necessary to understand the algorithm.
