# Mountain Car Project

## Overview
This project implements the **Mountain Car** problem, a classic reinforcement learning task. The goal is to train an agent to drive an underpowered car up a mountain by applying the right sequence of actions.

## Project Structure
- **`project_Mountain_car.ipynb`**: The Jupyter notebook containing the full implementation, including:
  - State representation and environment setup
  - Exploration strategies (e.g., epsilon-greedy)
  - Q-learning algorithm implementation
  - Training loop and reward visualization

## Key Features
- **Q-learning**: Implementation of the Q-learning algorithm to solve the continuous control problem.
- **Exploration strategies**: Used epsilon-greedy for balancing exploration vs. exploitation.
- **Visualization**: Shows the learning progress and final performance through reward plots.

## How to Run
To run this project:
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook and execute the cells sequentially.

---

# Windy Grid World Project

## Overview
The **Windy Grid World** is another reinforcement learning problem where an agent navigates a grid world with stochastic winds that affect movement. This project focuses on training an agent using SARSA (State-Action-Reward-State-Action) algorithm.

## Project Structure
- **`Windy_Grid_World.ipynb`**: The Jupyter notebook with the implementation of the Windy Grid World problem, including:
  - Grid environment creation
  - SARSA algorithm for learning optimal policies
  - Visual representation of the agent's path through the environment

## Key Features
- **SARSA algorithm**: Implemented the on-policy SARSA algorithm to learn optimal policies.
- **Grid environment**: Designed a custom grid world environment with windy states that change the agent's behavior.
- **Performance metrics**: Tracked cumulative rewards and the number of steps required to reach the goal.

## How to Run
To run this project:
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook and run all the cells.
