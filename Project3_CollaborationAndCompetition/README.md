Repository for the final submission of the CONTINUOUS_CONTROL-Project in the Udacity Nanodegree Deep Reinforcement Learning

## Project Details

DRLND Project 3 - Collaboration and Competition (Tennis environment)

![Tennis environment](https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif)

The *state space* for this project consists of 8 continuous values representing the position and velocity of a racket and ball in the X-Y plane.

The *action space* is a vector with two continuous values, clamped between -1 and 1, corresponding to the X and Y movements of the racket in the game, where the goal is to move the racket so it collides with the ball in a manner that causes the ball to move over the net, but not "go out" (collide with the back of the court area). 

Code for the Unity **Tennis** agent can be viewed [here](https://github.com/Unity-Technologies/ml-agents/blob/master/UnitySDK/Assets/ML-Agents/Examples/Tennis/Scripts/TennisAgent.cs)

A reward of +0.1 is provided for each step that the agent's shot goes over the net and not out, while a penalty of -0.01 for any failed shot or when the ball collides with the floor.

The environment is considered solved when the agents have an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents).

### Instructions:

1. Create a conda environment
(If you don't have a environment yet please follow the following instructions:
https://github.com/udacity/deep-reinforcement-learning#dependencies )

2. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

	- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.
(Parts of this readme reuse the instructions from the Udacity Page)

2. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `Navigation.ipynb` to get started with training your own agent!  
