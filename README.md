# Deep Reinforcement Learning

**Coursework in deep RL with Gymnasium, Stable-Baselines3 and PyTorch. It covers custom environments, PPO and DQN baselines, n-step SARSA and Q-learning, and DQN against Double DQN.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-4B8BBE)

## Contents

| Folder | Topic | What's inside |
|---|---|---|
| [`homework/01-intro-gymnasium`](homework/01-intro-gymnasium) | RL fundamentals | PPO on MountainCar-v0 (including a modified goal velocity), DQN vs. PPO on FrozenLake with Stable-Baselines3, a **custom Gymnasium environment**, and a bonus Pygame environment. |
| [`homework/02-td-learning-and-dqn`](homework/02-td-learning-and-dqn) | Temporal-difference learning | **n-step SARSA and n-step Q-learning** on CliffWalking (n = 1, 2, 5), the exploration–exploitation trade-off and regret under ε-greedy policies; **DQN vs. Double DQN** implemented in PyTorch on CartPole-v1, with experience replay, target networks and a study of value overestimation. |
| [`workshops/01-gymnasium-sb3-pygame`](workshops/01-gymnasium-sb3-pygame) | Tooling | MDPs in Gymnasium, action and observation spaces, wrappers, Stable-Baselines3 (DQN, PPO, SAC), TensorBoard monitoring, hyperparameter tuning, and a Pygame primer. |

Each homework folder contains the problem statement (`HW*_Questions.pdf`) and my completed notebooks.
The assignment templates come from the [DeepRLCourse](https://github.com/DeepRLCourse) materials.

## Running

The notebooks run on Google Colab (use the badge at the top of each notebook) or locally:

```bash
pip install "gymnasium[classic-control,toy-text]" stable-baselines3 torch matplotlib seaborn pygame jupyter
jupyter lab
```

## Related work

Deep RL is also the core of my M.Sc. thesis on **task offloading in edge computing**, where DQN, DRQN and distributional agents decide which tasks to offload.

## Author

**Mohammad Javad Amin** · [GitHub](https://github.com/mj-amin-ece)
