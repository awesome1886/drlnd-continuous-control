# Project 3: Collaboration and Competition

### Introduction

This project involves training a pair of agents to play a game of tennis. The environment is provided by Unity ML-Agents.

In this environment, two agents control rackets to bounce a ball over a net.
- A reward of +0.1 is given if an agent hits the ball over the net.
- A reward of -0.01 is given if an agent lets the ball hit the ground or hits it out of bounds.

The goal is to train the agents to keep the ball in play for as long as possible. The task is considered solved when the agents achieve an average score of +0.5 over 100 consecutive episodes.

### Getting Started

The project is designed to be run within the Udacity Deep Reinforcement Learning Nanodegree workspace. The `Tennis.ipynb` notebook contains all the necessary code and instructions.

The notebook handles:
1.  Installation of all required packages (PyTorch, unityagents, etc.).
2.  Initialization of the Unity environment.
3.  Implementation of the MADDPG learning agent.
4.  The training loop to train the agents.
5.  Plotting the final scores.

### Instructions to Run

1.  Open the `Tennis.ipynb` notebook in the Udacity workspace.
2.  From the menu, select **Kernel -> Restart & Run All**.
3.  The notebook will execute from top to bottom. The setup cell will take a few minutes to install dependencies.
4.  The training process will begin at the final cell. Wait for the training to complete. The environment is considered solved when the average score reaches +0.5.
5.  Upon completion, the trained model weights (`checkpoint_actor_0.pth`, etc.) will be saved in the root directory.