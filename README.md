# AI-Maze-Solver
This is my python notebook where I have used reinforcement learning to train a bot solve a maze. 

Reinforcement Learning (RL) is a type of machine learning paradigm that teaches agents how to make decisions by taking actions in an environment to achieve some goals. It is distinguished by how agents learn: through interaction with their environment and using feedback from their own actions and experiences, rather than from being explicitly taught the correct actions. This feedback comes in the form of rewards, which are signals that tell the agent how well it is doing at any given moment in achieving its goal.

### Key Concepts:
- Agent: The learner or decision-maker that interacts with the environment.
- Environment: The world through which the agent moves and learns. The environment provides states and rewards to the agent.
- State: A representation of the current situation or condition of the environment. It is what the agent observes and uses to make decisions.
- Action: A set of all possible moves that the agent can make. An action affects the state of the environment.
- Reward: A signal that the agent receives from the environment after taking an action. It is a measure of success or failure and guides the agent in learning.
- Policy: A strategy that the agent employs to determine its actions. A policy maps states of the environment to actions the agent should take when in those states.
- Value Function: It estimates how good it is for the agent to be in a given state (or how good it is to perform a certain action in a given state). It's closely related to the expected return from that state or state-action pair.
- Q-value or Action-Value Function: It represents the value of taking a particular action in a particular state, considering the future rewards.

This is my initial maze

<img width="419" alt="Screenshot 2024-03-06 at 10 29 29 AM" src="https://github.com/Prajyot9501/AI-Maze-Solver/assets/60104217/1c31edac-d337-485a-987d-308c1e08c126">

and I have kept rewards as goal_reward = 100; wall_penalty = -10; step_penalty = -1

### When I first ran the agent without any reinforcement learning, we see that it took a lot of steps (235) and the reward was also very low (-1223)

<img width="425" alt="Screenshot 2024-03-06 at 10 30 45 AM" src="https://github.com/Prajyot9501/AI-Maze-Solver/assets/60104217/299a04e4-8882-4b4c-ab6f-b7de0ad24840">

### After performing the reinforcement, we see the following improvement:

<img width="1003" alt="Screenshot 2024-03-06 at 10 33 01 AM" src="https://github.com/Prajyot9501/AI-Maze-Solver/assets/60104217/ecf155f1-0273-419c-9185-c8a8447a35f5">

### Thus, After the reinforcement loop, the agent gives the following results:

<img width="417" alt="Screenshot 2024-03-06 at 10 33 44 AM" src="https://github.com/Prajyot9501/AI-Maze-Solver/assets/60104217/51407234-d5ae-4f0f-b069-c29fe8a5cf7c">
