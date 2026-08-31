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

## 📈 Model Results

### ResNet50

![ResNet50 Accuracy](Cataract%20Prediction/models/ResNet50/ResNet50%20-%20Accuracy.png)

### VGG19

![VGG19 Accuracy](Cataract%20Prediction/models/VGG19/VGG19%20-%20Accuracy.png)

### MobileNetV2

![MobileNetV2 Accuracy](Cataract%20Prediction/models/MobileNetV2/MobileNetV2%20-%20Accuracy.png)

### DQN

![DQN Accuracy](Cataract%20Prediction/models/DQN/DQN%20-%20Accuracy.png)

### A2C

![A2C Accuracy](Cataract%20Prediction/models/A2C/A2C%20-%20Accuracy.png)

### PPO

![PPO Accuracy](Cataract%20Prediction/models/PPO/PPO%20-%20Accuracy.png)
