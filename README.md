# CM-50270-Reinforcement-Learning
Code and relevant files for the final project of CM50270 (Reinforcement Learning) for MSc. in Data Science at University of Bath. 

This is an implementation of DQN, DDQN, DDPG and TD3 on Lunar Lander environment from OpenAI Gym.

## Notes for viewer:
1. DQN and DDQN:
   
   a. Are implemented on Discrete action space.
   
   b. Use "LunarLander-v2"
   
   c. RANDOM_SEED = 42

2. DDPG and TD#:
   
   a. Are implemented for the continuous action space.
   
   b. Use "LunarLanderContinuous-v2"
   
   c. RANDOM_SEED = 101


### Solving Issues related to Box-2d: 
        pip uninstall pygame
         pip install gym[box2d] pygame
#### Still Facing Issues?

Try:
    
        pip uninstall pygame
        pip install swig
        pip install pygame


### For Google Colab:

1. Use these two cells at the begining of the Colab file
   
   [1]: 
        
        !apt-get update

        !apt-get install -y build-essential swig
   
   [2]: 
   
        !pip uninstall -y box2d-py
        
        !pip install -U --no-cache-dir --force-reinstall box2d-p
