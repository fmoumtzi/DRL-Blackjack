# DRL-Blackjack

Deep Reinforcement Learning Algorithms for Blackjack
This project implements and compares three state-of-the-art reinforcement learning algorithms for playing blackjack: Deep Q-Network (DQN), Proximal Policy Optimization (PPO), and Asynchronous Advantage Actor-Critic (A3C). All algorithms are built from scratch using TensorFlow and trained in an OpenAI Gym environment.

## Project Overview

This is a project created for the undergradute Computer Science course: Computational Inteligence - Deep Reinforcement Learning.

**Objective:** Develop and analyze the performance of advanced RL algorithms in a complex stochstic game environment.

**Environment:** Blackjack simulation using OpenAI Gym.

**Algorithms Implemented:**

**Deep Q-Network (DQN)**
DQN is a value-based reinforcement learning algorithm that leverages deep neural networks to approximate the Q-value function. It introduces experience replay and a target network to stabilize training. DQN has been successfully used in environments like Atari games to learn control policies directly from high-dimensional inputs.

Original Paper: [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)

**Proximal Policy Optimization (PPO)**
PPO is a policy-based reinforcement learning algorithm that strikes a balance between simplicity and performance. It uses a surrogate objective to ensure that policy updates are constrained, preventing large and potentially harmful updates. PPO is widely used due to its ease of implementation and reliable performance across various tasks.

Original Paper: [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)

**Asynchronous Advantage Actor-Critic (A3C)**
A3C is a policy gradient algorithm that trains multiple agents asynchronously in parallel, which helps in stabilizing training and improving performance. It combines the actor-critic approach with the advantage function, making it a strong choice for continuous action spaces and complex environments.

Original Paper: [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783)

**Key Features:**

Custom implementations of DQN, PPO, and A3C algorithms
Integration with OpenAI Gym for standardized environment interaction
Comparative analysis of algorithm performance, stability, and convergence rates
Hyperparameter optimization for each algorithm
Visualizations of learning progress and final performance

**Tech Stack:**
- Python
- TensorFlow
- OpenAI Gym
- NumPy
- Matplotlib (for visualizations)

**Future Work:**

In the future, I plan to enrich this project by implementing additional Deep Reinforcement Learning algorithms. I aim to explore more advanced methods such as Double DQN, Rainbow DQN, Soft Actor-Critic (SAC), and Alpha Zero. By experimenting with a wider variety of algorithms, the goal is to identify the most effective approach for playing Blackjack and further optimize the agent's performance.
