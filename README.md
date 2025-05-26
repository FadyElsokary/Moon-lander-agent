# 🧠 MoonLander Agent (DQN with Gymnasium)

This project trains an intelligent agent to land a lunar module safely using reinforcement learning (Deep Q-Network, or DQN). 🚀

## 🎮 Environment

- **Gymnasium**: `LunarLander-v2`
- The agent receives rewards for landing safely and penalties for crashing or flying too much.

## 📚 Techniques Used

- Deep Q-Learning (DQN)
- Epsilon-greedy exploration
- Experience Replay
- Target Network for stable learning

## 📂 Project Structure

- `agent.py` — Contains the `Agent` class and training logic.
- `train.py` — Trains the agent and saves the model.
- `model.py` — Defines the Q-network architecture.
- `checkpoint.pth` — Saved model weights.
- `video/landing.mp4` — Agent successfully landing on the moon! 🌕

## 🧪 Training Result

The environment is considered **solved** when the **average score over 100 episodes** is >= 200.  
My agent solved it in about **XXX episodes**.

## 📹 Demo

![Moon Lander Agent Demo](Landing_on_the_Moon.mp4)

## ▶️ How to Run

Install dependencies:

```bash
pip install -r requirements.txt
