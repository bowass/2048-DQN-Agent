# 2048-DQN-Agent
RL DQN Agent for 2048 (PyTorch)
Implemented PyTorch RL DQN Agent to play the game 2048.

The agent manages to reach 1024 in the vast majority of games, and even makes it to 2048!
There are 2 environments:
* Env2048: contains basic rendering option (prints to console).
    * Quite fast and recommended for training
* WebEnv2048: connects to [this web interface](https://play2048.co/) with selenium.
    * Slower, but nice for testing trained agent.
Model's trained weights in [here](https://github.com/bowass/2048-DQN-Agent/tree/main/Models).

**Usage:**
> Download the notebook and model weights files.

> Train the agent by running all notebook sections, or directly the trained model's weights (in case of using pretrained weights - run every cell besides Train Agent subsection in the Train secion.

> Test and Visualise agent with Env2048 or WebEnv2048 environments (WebEnv2048 works with local notebook or google colab on local runtime - won't work in colab with hosted runtime).
