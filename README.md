## Maze_random_walk

Welcome to the `maze_random_walk` project! This Python script generates a maze and employs reinforcement learning techniques to find a path through it. Let's dive into the details:

### Maze Generation
The maze is represented as a 2D array of 0s and 1s, where 0s represent paths and 1s represent walls. The `make_maze` function generates a random maze using a depth-first search algorithm.

### Random Walk
The script simulates a random walk through the maze using reinforcement learning. Here's how it works:
1. **Initialization**: Start at a random position in the maze.
2. **Policy**: Initialize a policy that determines the probability of each action (move) at each position.
3. **Exploration**: Choose a random action based on the policy and move to the next position if it's a valid move.
4. **Learning**: Update the policy based on the actions taken during the walk, using a learning rate to adjust the probabilities.

### Reinforcement Learning
The reinforcement learning algorithm gradually learns a policy that leads to successful navigation through the maze. It updates the policy based on the actions taken and the rewards obtained (i.e., reaching the goal).

### Visualization
The script provides visualizations to help understand the maze, the path found by the algorithm, and the learned policy:
- A plot showing the maze with the path found by the algorithm.
- A plot displaying the number of actions taken during each run of the algorithm.
- A heatmap illustrating the visited cells during the walk.
- A heatmap visualizing the learned policy, indicating the probabilities of each action at each position.

### Dependencies
Make sure you have `numpy`, `matplotlib`, and `pandas` installed to run this script successfully.

Feel free to explore and modify the code to experiment with different maze sizes, learning rates, or reinforcement learning algorithms! If you have any questions or need further assistance, don't hesitate to ask. Happy exploring!
