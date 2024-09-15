# rl-codes
Reinforcement learning codes and mini projects

# Reinforcement Learning - Iterative Policy Evaluation

This repository contains Python implementations for policy evaluation in reinforcement learning. The two key concepts covered are:

1. **Iterative Policy Evaluation for Deterministic Policies**: Evaluation of a deterministic policy where actions are taken with certainty in each state.
2. **Iterative Policy Evaluation for Probabilistic Policies**: Evaluation of a probabilistic policy where each action has a certain probability of being chosen in each state.

## Project Structure

### Python Codes:
- **`iterative_policy_evaluation_deterministic.py`**: This file contains the implementation for iterative policy evaluation with a deterministic policy. For each state, there is exactly one action with a probability of 1.
- **`iterative_policy_evaluation_probabilistic.py`**: This file contains the implementation for iterative policy evaluation with a probabilistic policy. For each state, the actions have varying probabilities.

### Grid World Environment:
- The simulations are based on a simple grid world environment.
- The rewards and transition probabilities are predefined and vary between the deterministic and probabilistic environments.

## Dependencies
- Python 3.x
- numpy for matrix operations
- A basic grid world environment

## Concept

### Policy Evaluation

Policy evaluation is the process of computing the value function for a given policy in a Markov Decision Process (MDP). The value function represents the expected return (total reward) for starting in a given state and following a policy thereafter.

### Deterministic Policy

A deterministic policy maps each state to exactly one action. There is no randomness in action selection.

### Probabilistic Policy

A probabilistic policy allows for multiple actions in each state, with a certain probability for each action. The value function is calculated by considering these probabilities.

## Running the Code

To run the probabilistic policy evaluation, execute the following command:

```bash
python iterative_policy_evaluation.py
