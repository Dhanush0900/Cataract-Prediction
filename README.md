# Cataract Prediction

## 📌 Overview

This project focuses on **AI-based cataract prediction using deep learning and reinforcement learning techniques**.

Multiple machine learning and deep learning models are implemented and evaluated to analyze their performance for cataract prediction.

## 🤖 Models Used

The project includes the following models:

- ResNet50
- VGG19
- MobileNetV2
- DQN (Deep Q-Network)
- A2C (Advantage Actor-Critic)
- PPO (Proximal Policy Optimization)

## 📂 Project Structure

```text
Cataract-Prediction/
│
├── Cataract Prediction/
│   └── models/
│       ├── A2C/
│       ├── DQN/
│       ├── MobileNetV2/
│       ├── PPO/
│       ├── ResNet50/
│       └── VGG19/
│
└── README.md

## 📁 Results

## 📊 Results

The models were evaluated on cataract prediction using classification
performance metrics.

| Model | Accuracy |
|---|---:|
| ResNet50 | 94% |
| VGG19 | 93% |
| MobileNetV2 | 94% |
| DQN | 94.50% |
| A2C | 94% |
| PPO | 91.32% |

### Best Performing Model

Based on the recorded results, **DQN achieved the highest accuracy
at 94.50%** among the evaluated models.

The repository also contains detailed evaluation visualizations for
each model, including confusion matrices, ROC curves, loss curves,
prediction results, and error analysis.
