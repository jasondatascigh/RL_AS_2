# Reinforcement Learning Assignment 2 - Gridworld

This repository contains the implementation for **Assignment 2** of the Reinforcement Learning course, focusing on solving a 5×5 Gridworld problem using various algorithms.

## Assignment Overview

We solve two main parts:

### Part 1: Tabular Dynamic Programming
- Evaluate value functions under a random policy using:
  - (1) Bellman equations (matrix inversion)
  - (2) Iterative Policy Evaluation
- Find the optimal policy using:
  - (1) Explicit Bellman optimality equations
  - (2) Policy Iteration
  - (3) Value Iteration

### Part 2: Monte Carlo Methods
- Modify the environment with terminal states
- Estimate optimal policies using:
  - (1) Monte Carlo with Exploring Starts (on-policy)
  - (2) Monte Carlo with ε-soft policy (on-policy)
  - (3) Off-policy Monte Carlo with Importance Sampling

## Getting Started

### Requirements

You only need Python and NumPy:

```bash
pip install numpy
