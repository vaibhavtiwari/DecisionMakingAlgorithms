# Control-to-RL: Algorithm Learning Through Implementation

## Objective

This project is an implementation-focused companion to the **Stanford AA203: Optimal and Learning-Based Control** lectures.

The goal is to build practical intuition for the progression from **optimal control to reinforcement learning**, while focusing on two complementary questions:

1. **Problem formulation — What problem should we solve?**
2. **Algorithm — How do we solve it?**

A key objective is learning how to translate a physical or behavioral requirement into a mathematical optimization problem:

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
Parameters
    ↓
Optimization Problem
```

## Approach

Each topic will contain only the theory necessary to understand and implement the algorithm:

* Simple intuition
* Assumptions
* Essential mathematical formulation
* Core algorithm
* JAX implementation
* Small experiment and visualization
* Parameter/constraint experiments
* Short takeaway

Important algorithmic components will be implemented explicitly, while **JAX** will provide tools such as automatic differentiation.

The simplest suitable environment will be used for each algorithm. A lightweight **2D kinematic car model** will be used particularly for trajectory optimization and finite-horizon control, with selected algorithms later tested in **highway-env**.

## Roadmap

The project follows the conceptual progression of AA203:

```text
Open-Loop Control
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
Adaptive & Learning Control
        ↓
Model-Free / Model-Based RL
```

The emphasis is not on implementing as many algorithms as possible, but on understanding **how the problem formulation and solution algorithm together produce the resulting system behavior**.

> **Guiding principle:** Environment complexity should never exceed what is necessary to understand the algorithm.
