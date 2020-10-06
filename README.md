[//]: # (Image References)

[image1]: ./media/agent.gif "Trained Agent"

# Project 1: Navigation

### Introduction

For this project, I train an agent to navigate and collect bananas in a square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent was to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started
0. Clone this repo.

1. Setup the python enviroment following next link: [click here](https://github.com/udacity/deep-reinforcement-learning#dependencies)

2. Copy the content of the `p1_navigation/` folder from this repo to the `p1_navigation/` folder of the udacity/deep-reinforcement-learning repo and replaces or remove existing files.

3. Unzip the Banana_Linux.zip file that is located under the `p1_navigation/` folder under the same directory

4. And finaly for training and testing run all the cells inside the navigation notebook

5. For only testing skip the training section inside the notebook
### Instructions

Follow the instructions in `Navigation.ipynb` to get started with training or test your own agent!  


