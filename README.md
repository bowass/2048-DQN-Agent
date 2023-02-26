# 2048-DQN-Agent
RL DQN Agent for 2048 (PyTorch)
Implemented PyTorch RL DQN Agent to play the game 2048.
The agent manages to reach 1024 in the vast majority of games, and even makes it to 2048!
There are 2 environments:
* Env2048: contains basic rendering option (prints to console).
    * Quite fast and recommended for training
* WebEnv2048: connects to [this web interface](https://play2048.co/).
    * Slower, but nice for testing trained agent.

model's trained weights in [here](https://github.com/barvaisman/2048-DQN-Agent/tree/main/Models).
