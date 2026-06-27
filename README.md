# CS 370 Portfolio Submission

## Project Overview

This repository contains my CS 370 portfolio artifact for the Treasure Hunt Game project. In this project, I worked with an intelligent pirate agent that had to learn how to find the treasure in a maze before the player. The goal was to train the pirate to find the best possible path to the treasure using deep Q-learning.

The project focused on reinforcement learning, neural networks, and decision-making. Instead of giving the pirate a fixed path, the agent learned through experience by exploring the maze, receiving rewards or penalties, and improving its choices over time.

## Work Completed on This Project

For this project, I was given starter code in a Jupyter Notebook. The starter code included the basic treasure hunt game structure, the maze environment, and several helper functions. I was also given two Python classes: TreasureMaze.py and GameExperience.py. TreasureMaze.py represented the maze environment, including the maze matrix and the agent’s possible movements. GameExperience.py stored the agent’s experiences so they could be reused for learning.

The code I created myself was the deep Q-learning implementation inside the qtrain() function. I completed the training logic that allowed the pirate agent to learn how to navigate the maze. This included resetting the maze at random starting points, observing the current environment state, selecting actions, applying actions to the maze, tracking wins and losses, storing episodes in memory, training the neural network, updating the target model, adjusting the exploration rate, and checking whether the agent could successfully solve the maze.

I also worked with training settings such as the number of epochs, memory size, data size, target model update frequency, and epsilon values. These settings helped control how the agent balanced exploration and exploitation while learning.

## Connection to Computer Science

Computer scientists solve problems by designing, building, testing, and improving software systems. Their work matters because computer science is used in many areas of everyday life, including education, business, healthcare, entertainment, transportation, and security. Computer scientists create tools and systems that help people complete tasks, analyze information, automate processes, and make better decisions.

This project connects to the larger field of computer science because it shows how artificial intelligence can be used to solve decision-making problems. The pirate agent had to evaluate different possible moves and learn which actions were most likely to lead to success. This same idea can be applied to real-world systems such as robotics, navigation tools, game AI, recommendation systems, and automated decision-making programs.

## My Approach as a Computer Scientist

When I approach a problem as a computer scientist, I first try to understand the goal of the program and the rules of the system. For this project, I needed to understand how the maze worked, how the pirate could move, how rewards were assigned, and how the agent would learn from previous actions.

After understanding the problem, I broke the work into smaller steps. I focused on getting the agent to choose valid actions, interact with the environment, store experiences, and train the neural network. I also tested the program by observing the win rate and using the completion check to make sure the agent was not just winning occasionally, but was consistently learning how to solve the maze.

This project helped me understand that computer science is not only about writing code. It is also about testing, debugging, improving, and making sure a solution works correctly. Reinforcement learning especially requires patience because the agent improves over time through repeated attempts.

## Ethical Responsibilities

As a computer scientist, I have ethical responsibilities to both the end user and the organization. To the end user, I have a responsibility to create software that is reliable, safe, fair, and useful. Users should be able to trust that the system works as intended and does not cause unnecessary harm. In an artificial intelligence project, this means making sure the model is tested carefully and that its results are understood before relying on it.

To the organization, I have a responsibility to create software that meets requirements, protects data, and supports the purpose of the project. I should write code that is understandable, maintainable, and honest in what it can and cannot do. If an AI system has limitations, those limitations should be clearly recognized.

This project showed me that even a small intelligent agent depends on choices made by the developer. The reward system, training process, exploration rate, and testing method all affect how the agent behaves. Because of that, computer scientists must think carefully about the systems they create and the impact those systems may have.

## Final Reflection

Overall, this project helped me better understand how reinforcement learning and neural networks can work together to train an intelligent agent. I learned how an agent can improve through trial and error, using feedback from rewards and penalties to make better decisions.

This project is a strong portfolio artifact because it demonstrates my ability to work with artificial intelligence concepts, complete a deep Q-learning algorithm, use a Jupyter Notebook, and explain how machine learning connects to the larger field of computer science.
