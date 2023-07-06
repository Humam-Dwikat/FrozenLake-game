# FrozenLake-game
FrozenLake in Gym and how we can use Reinforcement Learning (RL) using (Q-Learning) with Python 

## This is the first code without fixing the problem

### Reward problem
The agent will take 1 point from the reward if reached the file goal (G)
that makes the training not efficient
### Solution
We will give the agent a simple reward for each step if it was Frozen (F)
and use the discount factor to make the agent try to reach the final goal in the shortest way
