
## Enviroment Details

This environment is called the Tennis Environment. It consists of two agents (rackets) whose goal is to bounce a ball over a net to each other. If the agent hits the ball over the net, it receives a reward of 0.1; if the ball hits the ground or goes out of bounds, it gets a reward of -0.01. The goal of the agents is to maximise the cumulative reward per episode. The state-space consists of 8 variables corresponding to the position and velocity of the ball and the agent's racket. The action space is a w number vector representing jumping and movement relative to the net. Every entry in the action vector should be a number between -1 and 1. The environment is solved once the agent receives an average score of 0.5 over 100 consecutive episodes. This equates to an average rally of 9 to 10 shots.

## Getting Started

#### Download the Unity enviroment:
    Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip 
    Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip 
    Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip   
    Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip   
            
#### Requirements:    
    tensorflow==1.7.1    
    Pillow>=4.2.1    
    matplotlib    
    numpy>=1.11.0    
    jupyter    
    pytest>=3.2.2    
    docopt    
    pyyaml    
    protobuf==3.5.2    
    grpcio==1.11.0    
    torch==0.4.0    
    pandas    
    scipy    
    ipykernel      
    

## Instructions

In order to run the project, go to Continuous_Contol.ipynb. From there, run all of the code cells.

## Acknowledgements

The code was written making a references to:
GitHub. 2022. ContinousControl/Continuous_Control.ipynb at master · gkowalik/ContinousControl. [online] Available at: <https://github.com/gkowalik/ContinousControl/blob/master/Continuous_Control.ipynb> [Accessed 10 May 2022].
