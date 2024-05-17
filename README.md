# CM-50270-Reinforcement-Learning
Code and relevant files for the final project of CM50270 (Reinforcement Learning) for MSc. in Data Science at University of Bath. 
This is an implementation of DQN, DDQN, DDPG and TD3 on Lunar Lander environment from OpenAI Gym.

** Notes for viewer: **
1. DQN and DDQN:
   a. Are implemented on Discrete action space.
   b. Use "LunarLander-v2"
   c. RANDOM_SEED = 42
2. DDPG and TD#:
   a. Are implemented for the continuous action space.
   b. Use "LunarLanderContinuous-v2"
   c. RANDOM_SEED = 101


** If you are facing any issues related to Box-2d: **
1. pip uninstall pygame
2. pip install gym[box2d] pygame
3. If above things dont work:
   a. pip uninstall pygame
   b. pip install swig
   c. pip install pygame


** If using the code on Google Colab: **
1. Add the following 2 cells at the begining of the file
   [1]: !apt-get update
        !apt-get install -y build-essential swig
   [2]: !pip uninstall -y box2d-py
        !pip install -U --no-cache-dir --force-reinstall box2d-p
