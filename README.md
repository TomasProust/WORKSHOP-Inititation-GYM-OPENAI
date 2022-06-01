# Workshop - Initiation Gym openai

## Description (Gym in a few questions)
Gym is an open-source API developed by openai to help you learning reinforcement learning.  

### What is reinforcement learning?
Reinforcement learning (RL) is a sub-category of Machine Learning (ML) where an AI try to figures out the expected behavior in an environment (or the best solution in a problem).

### The environment in reinforcement learning
in Reinforcement Learning the AI interacts with an environment virtual or real (the AI can play a video game like it can controls a drone).
All RL AI follows the same pattern:  
1. the AI receives a **state** from the environment (multiple variables that represents the environment).
2. From the **state** the AI "chooses" a possible **action**.
3. The AI send to the environment the choosen **action**.
4. The environment sends back a **reward** (a variable that tell to the AI how much the choosen **action** was good) and a new **state** (the environement after the action).
5. if not done returns to step 2.

![](https://www.researchgate.net/profile/Roohollah-Amiri/publication/323867253/figure/fig2/AS:606095550738432@1521515848671/Reinforcement-Learning-Agent-and-Environment.png)

For example, a tic-tac-toe AI (that plays with the cross):
1. the AI receives an array that represents all the cells state of the grid (Cross/Circle/Nothing).
2. From this data the AI "chooses" on which cell it will put a cross.
3. The AI put a cross on the choosen cell. 
4. The environment send an new array of cells state that represents the changed environment (with the circle player move) and a reward for the choosen action.
5. If the game is not over then return to step 2.

### And Gym in all of this?
Gym is an API that offers a whole bunch of very varied environments to let apprentice developers focus on step 2: finding an algorithm capable of choosing the best possible action.

## Prerequisites
To start this project, you must have:
- **Python (>=3.7)** you can get it by installing the **python3** package with your favorite package manager (**dnf**, **apt**...)
- **numpy** (only for performance issues) you can install it with:  
    ```
    pip install numpy
    ```
- **matplotlib** (only for comprehension issues) you can install it with:
    ```
    pip install matplotlib
    ```

## Install
To install the gym simply:
```
pip install gym
```

## Getting started

[INSERT]

## Resources

[INSERT]

## I want to discover more

[INSERT]

## A workshop made by

[INSERT]

# THANK YOU FOR YOUR PARTICIPATION!