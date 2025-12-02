# LunarLander-DQN
---
This project uses a Deep Q-Network (DQN) to solve the LunarLander-v2 environment from OpenAI Gym. The agent learns to land a spacecraft safely using reinforcement learning.
---
## Project Overview
The goal of the agent is to land the lunar module between the flags with minimal fuel usage and without crashing.

## Features
---
+ Fully implemented DQN agent
+ Replay memory buffer
+ Target network for stable training
+ Reward tracking and performance visualization
+ Model saving & loading
+ Animated gameplay evaluation

## Project Structure
---
```bash
LunarLanderDQN/
├── LunarLandingDQN.ipynb   # Main notebook containing code, training, and evaluation
└── README.md               # Project documentation

```

## Requirements
---
### Install dependencies:
```bash
pip install gym pygame numpy torch matplotlib
```

## How to Run
---
1. Open the notebook
2. Run all cells to:
+ Initialize the environment
+ Train the DQN model
+ Evaluate the trained agent
+ Visualize results
If the notebook includes video rendering, you can watch the agent land the module.

| Parameter     | Value            |
| ------------- | ---------------- |
| Learning Rate | 1e-3             |
| Gamma         | 0.99             |
| Replay Memory | 50,000           |
| Batch Size    | 64               |
| Epsilon Decay | 1 → 0.01         |
| Target Update | every 1000 steps |

## Troubleshooting
---
My agent doesn’t learn
+ Reduce learning rate
+ Increase replay buffer size
+ Increase neural network size
+ Train for more episodes

## References
---
+ OpenAI Gym: LunarLander-v2
+ DeepMind DQN Paper (2015)
+ PyTorch Documentation










