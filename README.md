# Catch First!

A search-and-find zero-player game using ML-Agents.
Huge thanks to the ML-Agents package devs and [Code Monkey](https://www.youtube.com/@CodeMonkeyUnity) tutorials for teaching how to train an agent on a custom map to catch goals.

![](https://github.com/nima265/CatchFirst/blob/main/overall.gif)

# Positions of Agent and Goal

The agent and goal have four different positions that are randomly chosen, but each waypoint position has a radius (0.5) within which the positions of the agent and goal are randomly selected.

![](https://github.com/nima265/CatchFirst/blob/main/waypoints.png)

# Neural Network Model

For training this neural network model for the agent, I used a basic configuration and trained it for 3.5 million steps. The best mean reward achieved was 0.993.  
You can see more information in the charts below.

![Screenshot 2022-12-03 002128](https://user-images.githubusercontent.com/50208317/205384190-ef582953-48fc-4998-bb85-e41d3cc4362c.png)

![Screenshot 2022-12-03 002608](https://user-images.githubusercontent.com/50208317/205384797-c2868dbb-a3ee-4846-baa5-4dd346d4056d.png)

# Installation
- ML-Agents: 0.29.0
<br />ml-agents-envs: 0.28.0
<br />Communicator API: 1.5.0
<br />PyTorch: 1.7.0+cu110
<br />Unity: 2020.3.14

# Future Plans

1. I want to turn this into a "Catch First" game and pit the player against the agent.
<br />2. I want to make the agent smarter and increase its routing probability.

<br />
<br />
I would be happy to hear any comments or suggestions you have for this project.
