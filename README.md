# UdacityFinalProject

This is the final project for the Udacity Reinforcement Learning Nanodegree.

Environment: virtual tennis court
Agent and its actions: two agents aim to play tennis together, and can select continuous actions which have to do with their position with respect to the net.

State space: The observation space has 24 variables describing the position and velocity of the ball and racket. Each agent receives its own, local observation.

Reward Function: If an agent hits the ball over the net, it receives a reward of .01. If the ball hits the ground or is hit out of the bounds, the agent receives a reward of -.01. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

To complete the task, you must get an average score of .5 over 100 consecutive episodes.


To set up your Python environment, go here: https://github.com/udacity/deep-reinforcement-learning#dependencies

To download the Unity Tennis Environment, choose one of the following options depending on your operating system:

Windows 64: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip
Windows 32: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip
Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip
Mac: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip



To run the code, open Tennis.ipynb and run all cells.
