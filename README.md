


### Deep Q-Learning for Lunar Landing

This project implements a Deep Q-Network (DQN) to train an agent for the Lunar Lander environment using reinforcement learning. The goal is to land the spacecraft safely with minimal fuel consumption.

## Features 

**Environment:** OpenAIOpenAI Gym's LunarLander-v2

**Algorithm:** Deep Q-Learning with Experience Replay

**Neural Network:** Multi-layer perceptron (MLP)

**Replay Buffer:** Stores past experiences for efficient learning

**Training Process:** Rewards maximized by learning from past experiences


## Dependencies

Ensure you have the following installed:

pip install numpy gym torch matplotlib

## Usage

1. **Run the training script:**
Execute the notebook to train the model.


2. **Modify hyperparameters:**
Adjust learning rate, batch size, or replay memory size for experimentation.


3. **Test the trained model:**
Once trained, test the agent’s performance in the Lunar Lander environment.



## Results

The agent learns to land the spacecraft by maximizing rewards.

Training performance is visualized using plots.

The model can be fine-tuned for better stability.


## Future Improvements

Implementing Double DQN for better stability.

Adding Prioritized Experience Replay.

Fine-tuning hyperparameters for optimal performance.


## Author

**Developed by Kabilan.**




