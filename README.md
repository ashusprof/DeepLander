# DeepLander: Thruster Intelligence for Safe Lunar Descent 🚀

A Deep Reinforcement Learning project that uses Deep Q-Learning (DQN) to train an AI agent to control thrusters for a safe lunar landing using the `LunarLander-v3` environment from `gymnasium`.

---

## 🧠 Project Overview
**DeepLander** simulates a lunar lander controlled by an agent trained using Deep Q-Networks. The environment provides continuous feedback as the agent learns to land safely using optimal thruster control strategies.

---

## 🌌 Key Concepts
- Deep Q-Learning (DQN)
- Experience Replay
- Target Network
- Reward Shaping
- Exploration vs Exploitation
- Environment: `LunarLander-v3` from `gymnasium[box2d]`

---

## 🗂 Files
- `Lunar_Landing.ipynb` – Complete notebook including training, evaluation, and visualizations.
- `README.md` – Project documentation.

---
- `matplotlib`
- `torch` *(or `tensorflow`, depending on the framework used)*

Install dependencies:
```bash
pip install -r requirements.txt
