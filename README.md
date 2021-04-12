# UdacityFinalProject

This is the final project for the Udacity Reinforcement Learning Nanodegree.

Environment: virtual tennis court
Agent and its actions: two agents aim to play tennis together, and can select continuous actions which have to do with their position with respect to the net.

State space: The observation space has 8 variables describing the position and velocity of the ball and racket. Each agent receives its own, local observation.

Reward Function: If an agent hits the ball over the net, it receives a reward of .01. If the ball hits the ground or is hit out of the bounds, the agent receives a reward of -.01. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

To complete the task, you must get an average score of .5 over 100 consecutive episodes.


To set up your Python environment, go here: https://github.com/udacity/deep-reinforcement-learning#dependencies

To download the Unity Environment, follow the steps here: https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control
