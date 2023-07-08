This project uses Deep Q-Learning to solve cartpole(Gym environment)(solved at episode_reward = 195)
the file "DeepQ_Cartpole_scartch.ipynb"
    - this notebook contain all the code used for training the model
    - contains implementation of Deep Q-Learning algorithm
    - uses Keras's Sequential model as base model

the file "test.ipynb"
    - contain code for testing trained models in 3 steps
    - random testing (average_reward = 27)
    - testing with model trained for 300 episodes (average_reward = 110)
    - testing with model trained for 600 episodes (average_reward = 204)

the folder "models"
    - contains saved models

the folder "outputs"
    - contains outputs such as episode_reward while training

the "RewardVSEpisode.png" image is a plot of episode_rewards vs episode_number while training