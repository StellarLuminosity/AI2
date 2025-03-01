# 🏆 AI² Tournament: Reinforcement Learning Agent for Fighting Game AI

## Challenge Overview
This project was developed for the **AI² Tournament**, where the goal was to train reinforcement learning (RL) agents to compete in a **1v1 fighting game** similar to Brawhalla. The agents learned to optimize their strategies through self-play and carefully designed reward functions.

🚀 **Our agent was awarded the AI² Crown**, recognizing it as one of the top 3 reinforcement learning agents in the competition.

## How Our Agent Works
Our approach combined **deep reinforcement learning** with strategic **hard-coded behavior** to ensure robustness in various combat scenarios. 

### **Core Features of Our Agent**
- **Proximal Policy Optimization (PPO)**: Agent trained using a deep neural network with PPO, a leading policy optimization algorithm.
- **Multi-Layer Perceptron (MLP) Policy**: The agent’s decision-making was powered by a deep MLP policy and value network optimized for fighting games.
- **Adaptive Movement**: The agent learned to approach opponents, execute multi-hit combos, and dodge attacks.
- **Survival Mechanism**: Hard-coded logic prevented the agent from falling off the platform by detecting edges and adjusting movement accordingly.
- **Reward-Based Learning**: The agent was rewarded for successful attacks, minimizing damage taken, executing combos, winning matches, and knocking out opponents.

### Agent Architecture
The agent's neural network follows a **deep hierarchical structure**, with separate architectures for **policy learning** and **value estimation**:

This repository incudes the env_final.ipynb notebook which includes the reward functions used, core agent architecture, and the training code. 
UTMIST_AI2_Env_OFFICIAL.ipynb is the original version of the notebook, with the basic environment configurations and agent class implementations.

### Acknowledgments
This Tournament and most of the code in the notebooks was written and designed by UTMist (University of Toronto Machine Intelligence Team) Members. A huge thanks for creating this exciting challenge!
