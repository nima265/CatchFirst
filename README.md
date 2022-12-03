# Catch First

A search and found zero player game using ML-Agent.
I was able to by using ML-Agent package and [Code Monkey](https://www.youtube.com/@CodeMonkeyUnity) tutorials, Learning an Agent on a Custom map to catching goals.

![](https://github.com/nima265/CatchFirst/blob/main/overall.gif)

# Positions of Agent and Goal

agent and goal have four different positions that are randomly chosen for the positions of agent and goal, but each wayPoint position has a radius (0.5) that the position 
of agent and goal chosen in this radius of random waypoints position.

![](https://github.com/nima265/CatchFirst/blob/main/waypoints.png)

# Neoral Network model

For learning this NN model for the agent I used a basic configuration but learned it on 3.5 million steps and the best mean reward was 0.993  
You can see more information in the chart below

![Screenshot 2022-12-03 002128](https://user-images.githubusercontent.com/50208317/205384190-ef582953-48fc-4998-bb85-e41d3cc4362c.png)

![Screenshot 2022-12-03 002608](https://user-images.githubusercontent.com/50208317/205384797-c2868dbb-a3ee-4846-baa5-4dd346d4056d.png)

# installations
 ml-agents: 0.29.0
 <br />ml-agents-envs: 0.28.0
 <br />Communicator API: 1.5.0
 <br />PyTorch: 1.7.0+cu110
 <br />Unity: 2020.3.14


# Futures

1.I want to turn this into a chatch first game and pit the player against the agent
<br />2.I want to make this agent smarter and increase its routing probability


<br />
<br />
I would be happy if you have any comments or suggestions for this project
