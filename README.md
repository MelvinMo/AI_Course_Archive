# AI_Course_Archive
This repository contains my undergrad artificial intelligence course activities, primarily theoretical or programming assignments, including the course's final project.

## Assignment 1
It is on topics: #CSP, #TSP, #GeneticAlgorithm, #Nqueens, and #GraphColoring.

## Assignment 2
it is on topics: #ML, #NeuralNetwork, #Backpropagation, and #GradientDescent.

## Assignment 3
It is on topics: #Probability, #Independence, #BayesianNetwork, and #MarkovGame.

## Assignment 4
It is on topics: #MarkovDecisionProcess and #ReinforcementLearning.

## Final Project: Developing an AI Agent to Play Breakout using Deep Reinforcement Learning
This project aimed to develop an artificial intelligence (AI) agent capable of playing the classic arcade game "Breakout" using deep reinforcement learning techniques. The objective was to train the agent to master complex control strategies, break all the bricks, and achieve a high score.

To accomplish this, a deep Q-network (DQN) architecture was implemented with the stable-baselines3 Python library. The Gym Retro environment simulated the Atari 2600 version of Breakout (Breakout V5 of Gymnasium, a maintained fork of OpenAI’s Gym library). The agent received raw 84x84-pixel observations of the game screen and was trained to maximize cumulative rewards by breaking bricks while avoiding ball loss.

Key techniques employed included experience replay, target networks, and epsilon greedy exploration. The neural network comprised three convolutional layers and a fully connected layer to approximate the Q-function. Training took place over episodes, with the epsilon value gradually decreasing. Periodic checkpoints of the model weights were saved for evaluation.

After extensive training, the AI agent achieved a high average score, demonstrating proficiency in breaking bricks across multiple levels. However, it faced challenges with specific types of bricks positioned higher up. Further improvements, such as incorporating techniques like dueling DQN, hold potential for enhancing performance.

<p align="center">
  <img src="https://github.com/MelvinMo/AI_Course_Archive/blob/main/Final%20Project/breakout.gif" alt="GIF" />
</p>
