## Overview
This task aims to learn how to deal with Reinforcement Learning
What has been done :

1) Turn this code into a module of functions that can use multiple environments.

2) Tune alpha, gamma, and/or epsilon using a decay over episodes.

3) Implement a grid search to discover the best hyperparameters.


1-Import required packages
            !pip install cmake 'gym[atari]' scipy
            from numpy import array
            from math import inf
            from numpy.linalg import norm
            import gym
            from IPython.display import clear_output
            from time import sleep
            import numpy as np
            import random
            from IPython.display import clear_output



2- learning(the_game, alpha, gamma, epsilon, itritions = 100001)
    2.1 enter inputs  **** more clear in notebook comment****
     basically this function to train our agent

3- evaluating(environment , q_table, episodes)
    3.1 take the game name, q_table, and episodes 


4- grid_search (the_game, itritions ,episodes)
    4.1 take the game name, itritions, and episodes
