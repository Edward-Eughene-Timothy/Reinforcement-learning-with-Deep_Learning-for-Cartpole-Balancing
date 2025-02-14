# Reinforcement-learning-with-Deep_Learning-for-Cartpole-Balancing


This repository contains an implementation of a Deep Q-Network (DQN) to solve the CartPole-v1 environment from OpenAI Gym. The model is trained using PyTorch and leverages reinforcement learning techniques to balance the pole for as long as possible.

Features

Implements Deep Q-Learning with Experience Replay

Uses PyTorch for building and training the neural network

Utilizes OpenAI Gym's CartPole-v1 environment

Includes epsilon-greedy policy for exploration vs. exploitation trade-off

Requirements

Ensure you have the following dependencies installed before running the notebook:

pip install torch gym numpy matplotlib

Training the Model

Run the Jupyter Notebook in Google Colab or a local environment to train the DQN model. The training loop will update the Q-network and visualize the performance over time.

Results

After training, the model is expected to achieve an average reward close to the maximum score of 500, demonstrating its ability to successfully balance the pole.

References

Deep Q-Networks: https://www.nature.com/articles/nature14236

OpenAI Gym: https://gym.openai.com/

PyTorch Documentation: https://pytorch.org/docs/stable/

License

This project is licensed under the MIT License.

