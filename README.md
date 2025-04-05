# RL-Based Trading Agent Using PPO and Price Action Signals 📈🤖

This repository contains the implementation of a Reinforcement Learning (RL) trading agent that leverages **Proximal Policy Optimization (PPO)** to make trading decisions using **price action-based technical indicators**. The model is trained to optimize profits while managing risk, simulating real-world trading dynamics.

## 🧠 Key Features

- **Reinforcement Learning (PPO):** Uses Proximal Policy Optimization to balance exploration and exploitation.
- **Price Action Signals:** Incorporates momentum-based indicators including RSI, MACD, and ADX as state features.
- **Custom Trading Environment:** Built using OpenAI Gym to mimic realistic trading scenarios with market constraints.
- **Modular Code Structure:** Easily extendable to new indicators, reward functions, or markets.

## 📊 State Space

- Close Price  
- RSI (Relative Strength Index)  
- MACD (Moving Average Convergence Divergence)  
- ADX (Average Directional Index)  

## 🎯 Actions

- `0`: Buy  
- `1`: Sell  
- `2`: Hold  

## 🏆 Rewards

- Reward = Change in Portfolio Value over the episode

## 🚀 Getting Started

### Prerequisites

Make sure you have the following Python packages installed:


## 📈 Results
The PPO-trained agent demonstrated consistent returns under a variety of market conditions. Detailed evaluation metrics and learning curves are available in the notebooks/ directory.

## 📚 Reference
This repository is based on the paper:

RL-Based Trading Agent Using PPO and Price Action Signals (2023)
Huseynli, Ozturk, Arslan
Presented at: International Conference on Artificial Intelligence and Data Processing (IDAP)

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📜 License
This project is licensed under the MIT License.
