# Q-Learning on Cliff Walking

This mini project implements the **Q-Learning** algorithm using the **Gymnasium CliffWalking-v1** environment. The objective is to train an agent to reach the goal while avoiding the cliff and maximizing the total reward.

## About the Project

The agent starts with an empty Q-table and learns by interacting with the environment over multiple episodes. It follows an **ε-greedy policy**, allowing it to balance exploration and exploitation while updating the Q-values using the Bellman equation.

After training, the learned policy is tested by selecting the best action from the Q-table at each state.

## Hyperparameters

* Episodes: **500**
* Learning Rate (α): **0.5**
* Discount Factor (γ): **0.99**
* Exploration Rate (ε): **0.1**

## Concepts Used

* Reinforcement Learning
* Q-Learning
* Q-Table
* ε-Greedy Policy
* Bellman Equation
* Exploration vs Exploitation

## What I Learned

* How Q-Learning updates state-action values based on rewards.
* The importance of balancing exploration and exploitation.
* How an agent improves its policy through repeated interactions with the environment.
* How the Q-table stores the expected reward for each state-action pair.
