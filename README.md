# Project 2: Continuous Control

### Project Details

This project involves training a reinforcement learning agent to control a double-jointed arm in the "Reacher" Unity environment.

- **Goal:** The agent's goal is to move the arm's hand to target locations and keep it there for as long as possible.
- **Environment:** The environment provides a continuous state space of 33 dimensions (position, rotation, velocity, etc.) and a continuous action space of 4 dimensions (torque for the two joints).
- **Solving Criteria:** The environment is considered solved when the agent achieves an average score of +30 over 100 consecutive episodes.

### Getting Started

1.  **Dependencies:** This project requires Python 3 and several Python libraries. You can install the dependencies using pip:
    ```
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file containing `numpy`, `torch`, `unityagents`, and `matplotlib`)*

2.  **Download the Environment:** Download the 20-agent Reacher environment for your operating system from the links provided by Udacity and place it in the root of this repository.

### Instructions

- **To train the agent:** Open the `Continuous_Control.ipynb` notebook and run all the cells. The training process will begin, and the notebook will save the trained model weights (`checkpoint_actor.pth` and `checkpoint_critic.pth`) upon completion.

- **To watch a trained agent:** (Optional) A separate notebook, `WatchAgent.ipynb`, can be used to load the saved weights and watch the trained agent perform.