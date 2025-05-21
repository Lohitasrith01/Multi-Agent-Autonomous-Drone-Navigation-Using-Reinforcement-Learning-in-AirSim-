# Multi-Agent-Autonomous-Drone-Navigation-Using-Reinforcement-Learning-in-AirSim-
1. **Environment Definition**: The `MultiAgentEnv` class defines a grid-based environment where agents (drones) can move autonomously with:
   - Grid-based movement (up, down, left, right)
   - Obstacle avoidance
   - Goal-seeking behavior
   - Collision prevention with other agents

2. **Autonomous Navigation Features**:
   - Each agent has autonomous decision-making capabilities
   - Agents can navigate independently to their goals
   - Obstacle detection and avoidance
   - Collision avoidance with other agents
   - Path planning through the grid

3. **Learning Algorithms**:
   - Double Q-Learning for autonomous decision making
   - DQN (Deep Q-Network) implementation for more complex navigation scenarios
   - Reward-based learning system that encourages:
     - Efficient path finding
     - Goal reaching
     - Obstacle avoidance
     - Collision prevention

4. **State and Action Spaces**:
   - State space: Grid positions of agents
   - Action space: 4 discrete actions (up, down, left, right)
   - Observation space: Current positions and goal status

