# Snake Game with Deep Q-Learning
This project implements the classic Snake game using Pygame and applies Deep Q-Learning (a type of Reinforcement Learning) to train an AI agent to play the game autonomously. The agent learns to maximize its score by navigating the snake and eating the food while avoiding collisions.

## Project Overview
The Snake game is a classic arcade game where the player controls a snake that grows in size as it eats food. The goal is to prevent the snake from colliding with itself or the walls while maximizing the number of food pieces eaten.

In this project, I combined Pygame for game creation and Deep Q-Learning for training an AI agent to play the game.

## How the AI Works
- Deep Q-Learning (DQN) is a model-free reinforcement learning algorithm. It uses a neural network to approximate the Q-value function, which tells the agent the expected reward of taking a particular action in a given state.
- The game is divided into states (the current position of the snake, the food position, etc.), and the agent must decide on actions (up, down, left, right) to maximize its cumulative reward.
- The agent receives a reward when it eats food and a penalty for colliding with the walls or its own body.
